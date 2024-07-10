<script>

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
      <li class="tools-and-skills__item" v-for="(item, index) in toolsAndSkillsArray" :key="index">
        <img :src="item.icon" :alt="item.company" class="tools-and-skills__icon" />
        <div class="tools-and-skills__info">
          <strong class="tools-and-skills__strong">{{ item.name }}</strong>
          <p class="tools-and-skills__description">{{ item.description }}</p>
        </div>
      </li>
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

.tools-and-skills__item {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 8px;
  padding: 28px;
  background-color: #F7F9FC;
}

.tools-and-skills__icon {
  display: flex;
}

.tools-and-skills__info {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.tools-and-skills__strong {
  font-size: 14px;
  line-height: 18px;
  color: #2E2E48;
}

.tools-and-skills__description {
  font-size: 10px;
  line-height: 14px;
  color: #79819A;
}

@media screen and (min-width: 576px){
  .tools-and-skills__list {
    grid-template-columns: 1fr 1fr;
  }

  .tools-and-skills__item {
    padding: 22px;
  }
}
@media screen and (min-width: 768px){
  .tools-and-skills__list {
    grid-template-columns: 1fr 1fr 1fr 1fr;
  }

  .tools-and-skills__item {
    padding: 20px;
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

  .tools-and-skills__item {
    flex: 1 1 calc(33.33% - 16px);
    display: flex;
    flex-direction: column;
    gap: 8px;
    justify-content: center;
    align-items: center;
    padding: 13px;
    background-color: #F7F9FC;
  }

  .tools-and-skills__item:nth-child(n+4) {
    flex-basis: calc(20% - 16px);
  }
}

</style>
