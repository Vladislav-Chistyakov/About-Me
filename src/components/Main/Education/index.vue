<script>
import Educationelement from "./Educationelement.vue";

const educationArray = [
  {
    name: 'Chandigarh University',
    icon: '/main/education/chandigarh.png',
    description: 'Bachelor in Computer Science Engineering',
    date: '2020 - 2024',
    percentage: '9 CGPA'
  },
  {
    name: 'Suditi Global Academy',
    icon: '/main/education/akanksha.png',
    description: 'Intermediate XI - XII (CBSE)',
    date: '2018 - 2020',
    percentage: '85%'
  },
  {
    name: 'Akanksha Global Acadmey',
    icon: '/main/education/suditi.png',
    description: 'High School IX - X (CBSE)',
    date: '2016 - 2018',
    percentage: '92%'
  }
]
  export default {
    name: 'index',
    components: {Educationelement},
    data () {
      return {
        educationArray: educationArray
      }
    }
  }
</script>

<template>
  <div class="education">
    <h2 class="education__title heading">Education</h2>
    <ul class="education__list">
      <Educationelement  v-for="(item, index) in educationArray"
                         :key="index"
                         :percentage="item.percentage"
                         :date="item.date"
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

.education__list {
  display: grid;
  grid-template-columns: 1fr;
  gap: 8px;
  border-radius: 6px;
  overflow: hidden;
}

@media screen and (min-width: 1024px){
  .heading {
    font-weight: 500;
    font-size: 24px;
    line-height: 32px;
    margin-bottom: 32px;
  }

  .education__list {
    grid-template-columns: 1fr 1fr 1fr;
  }
}
</style>
