<script>

import AchivementsElement from "./AchivementsElement.vue";

const achievementsArray = [
  {
    present: true,
    date: null,
    location: 'Chandigarh',
    company: 'Alexa Dev Community',
    icon: '/main/achievements/alexa.svg',
    speciality: 'Graphic Designer',
    description: 'Creatively Designing and Developing web UI for Chandigarh University’s Alexa Developer Community, upcoming big launch of full website. '
  },
  {
    present: false,
    date: 'Oct 2021 - Nov 2021',
    location: 'Online',
    company: 'Github',
    icon: '/main/achievements/github.svg',
    speciality: 'Hacktoberfest Contributor',
    description: 'Contributed 8 PR’s in various open source projects. Great experience and learning alot about working with Github and open-source. Connecting with developers'
  },
  {
    present: false,
    date: 'Jan 2021 - March 2021',
    location: 'Online',
    company: 'Winter of Code',
    icon: '/main/achievements/WOC.svg',
    speciality: 'Contributor',
    description: 'Overwhelming to be a part of DSC NSEC project - DSC NSEC Algorithms for Winter of Code 2020. First introduction to Git and Github. How github is used by most of the programmers in order to manage the projects.'
  },
  {
    present: false,
    date: 'Oct 2020 - Dec 2020',
    location: 'Online',
    company: 'Google',
    icon: '/main/achievements/google.svg',
    speciality: '30Days of Google Cloud',
    description: 'Hands on practice on Google Cloud Platform - the tool that powers apps like Google Search, Gmail and YouTube.\n' +
        'As part of the program had learned the concepts like computing, application development, big data & machine learning using cloud.'
  }
]
export default {
  name: 'index',
  components: {AchivementsElement},
  data () {
    return {
      achievementsArray: achievementsArray
    }
  }
}
</script>

<template>
  <div class="achievements">
    <h2 class="achievements__title heading">Achievements</h2>
    <ul class="achievements__list">
      <AchivementsElement v-for="(item, index) in achievementsArray"
                          :key="index"
                          :description="item.description"
                          :speciality="item.speciality"
                          :company="item.company"
                          :icon="item.icon"
                          :location="item.location"
                          :date="item.date"
                          :present="item.present" />
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

@media screen and (min-width: 1024px){
  .heading {
    font-weight: 500;
    font-size: 24px;
    line-height: 32px;
    margin-bottom: 32px;
  }
}

</style>
