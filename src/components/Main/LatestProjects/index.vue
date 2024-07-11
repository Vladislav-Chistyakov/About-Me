<script>
import LatestProjectsElement from "./LatestProjectsElement.vue";

const latestProjectsArray = [
  {
    name: 'Alexa Dev Community Landing Page',
    description: 'Web UI design for alexa developers comunity',
    icon: '/src/assets/main/latestProjects/figma.svg',
    labelLink: 'https://figma.com',
    link: 'https://www.figma.com/design/v3aL1mm9ha6234w4fIi19N/MARVEL-STUDIOS?node-id=2-6&t=P5x9FNrtceyb6xOf-0',
    iconLink: '/src/assets/main/latestProjects/figma-link.svg'
  },
  {
    name: 'Portfolio Webpage',
    description: 'Personal Portfolio webpage with resume and blog',
    icon: '/src/assets/main/latestProjects/webpage.svg',
    labelLink: 'https://anuragyadav365.github.io/',
    link: 'https://anuragyadav365.github.io/portfolio.html',
    iconLink: '/src/assets/main/latestProjects/site-link.svg'
  }
]
export default {
  name: 'index',
  components: {LatestProjectsElement},
  data () {
    return {
      latestProjectsArray: latestProjectsArray,
    }
  }
}
</script>

<template>
  <div class="latest-projects">
    <h2 class="latest-projects__title heading">Latest projects</h2>
    <ul class="latest-projects__list">
      <LatestProjectsElement v-for="(item, index) in latestProjectsArray"
                             :key="index"
                             :link="item.link"
                             :label-link="item.labelLink"
                             :icon-link="item.iconLink"
                             :description="item.description"
                             :name="item.name"
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

.latest-projects__list {
  border-radius: 6px;
  overflow: hidden;
  display: grid;
  grid-template-columns: 1fr;
  gap: 12px;
}

@media screen and (min-width: 1024px){
  .heading {
    font-weight: 500;
    font-size: 24px;
    line-height: 32px;
    margin-bottom: 32px;
  }

  .latest-projects__list {
    grid-template-columns: 1fr 1fr;
  }
}
</style>
