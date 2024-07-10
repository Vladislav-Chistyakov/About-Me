<script>

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
      <li v-for="(item, index) in latestProjectsArray" :key="index" class="latest-projects__item">
        <div class="latest-projects__block-info">
          <img :src="item.icon" :alt="item.name" class="latest-projects__block-info-icon" />
          <div class="latest-projects__block-info-name-and-description">
            <strong class="latest-projects__block-info-name">{{ item.name }}</strong>
            <p class="latest-projects__block-info-description">{{ item.description }}</p>
          </div>
        </div>
        <div class="latest-projects__block-link">
          <img :src="item.iconLink" :alt="item.labelLink" class="latest-projects__block-link-icon" />
          <a target="_blank" :href="item.link" class="latest-projects__block-link-project">{{ item.labelLink }}</a>
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

.latest-projects__list {
  border-radius: 6px;
  overflow: hidden;
  display: grid;
  grid-template-columns: 1fr;
  gap: 12px;
}

.latest-projects__item {
  display: flex;
  flex-direction: column;
  gap: 16px;
  padding: 24px;
  background-color: #F7F9FC;
}

.latest-projects__block-info {
  display: flex;
  flex-direction: row;
  gap: 16px;
}

.latest-projects__block-info-icon {
  display: flex;
}

.latest-projects__block-info-name-and-description {
  display: flex;
  flex-direction: column;
  gap: 4px;
}

.latest-projects__block-info-name {
  font-size: 16px;
  line-height: 20px;
  color: #2E2E48;
}

.latest-projects__block-info-description {
  font-size: 14px;
  line-height: 18px;
  color: #78819A;
}

.latest-projects__block-link {
  display: flex;
  flex-direction: row;
  gap: 16px;
  align-items: center;
  word-break: break-all;
}

.latest-projects__block-link-icon {
  display: flex;
}

.latest-projects__block-link-project {
  font-weight: 600;
  font-size: 16px;
  line-height: 20px;
  color: #516CF7;
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
