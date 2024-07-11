<script>
import ToolsAndSkillsElement from "./ToolsAndSkillsElement.vue";

const toolsAndSkillsArray = [
  {
    name: 'Figma',
    description: 'Web UI Design, Prototyping',
    icon: '/src/assets/main/skills/figma.svg'

  },
  {
    name: 'Java',
    description: 'Software Development',
    icon: '/src/assets/main/skills/java.svg'

  },
  {
    name: 'Python',
    description: 'Design workspace',
    icon: '/src/assets/main/skills/python.svg'
  },
  {
    name: 'HTML 5',
    description: 'Structural Design',
    icon: '/src/assets/main/skills/html.svg'

  },
  {
    name: 'CSS 3',
    description: 'Style Design',
    icon: '/src/assets/main/skills/css.svg'

  },
  {
    name: 'Wordpress',
    description: 'Web development',
    icon: '/src/assets/main/skills/wordpress.svg'

  },
  {
    name: 'VS Code',
    description: 'Code editor',
    icon: '/src/assets/main/skills/vs.svg'

  },
  {
    name: 'Notion',
    description: 'Project managment',
    icon: '/src/assets/main/skills/notion.svg'

  }
]
export default {
  name: 'index',
  components: { ToolsAndSkillsElement },
  data () {
    return {
      toolsAndSkillsArray: toolsAndSkillsArray,
    }
  }
}
</script>

<template>
  <div class="tools-and-skills">
    <h2 class="tools-and-skills__title heading">Tools/Skills</h2>
    <ul class="tools-and-skills__list">
      <ToolsAndSkillsElement v-for="(item, index) in toolsAndSkillsArray"
                      :key="index"
                      :description="item.description"
                      :name="item.name"
                      :company="item.name"
                      :icon="item.icon" />
    </ul>
  </div>
</template>

<style scoped>

.heading {
  font-family: "Outfit";
  font-weight: 500;
  font-size: 24px;
  line-height: 32px;
  color: #2e2e48;
  margin-bottom: 22px;
}

.tools-and-skills__list {
  display: grid;
  grid-template-columns: 1fr;
  border-radius: 6px;
  overflow: hidden;
  gap: 8px;
}

@media screen and (min-width: 576px){
  .tools-and-skills__list {
    grid-template-columns: 1fr 1fr;
  }
}

@media screen and (min-width: 768px){
  .tools-and-skills__list {
    grid-template-columns: 1fr 1fr 1fr 1fr;
  }
}

@media screen and (min-width: 1024px){
  .heading {
    font-weight: 500;
    font-size: 24px;
    line-height: 32px;
    margin-bottom: 32px;
  }

  .tools-and-skills__list {
    display: flex;
    flex-wrap: wrap;
    border-radius: 6px;
    overflow: hidden;
    gap: 8px;
  }
}

</style>
