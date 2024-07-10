<script>

const educationArray = [
  {
    name: 'Chandigarh University',
    icon: '/src/assets/main/education/chandigarh.png',
    description: 'Bachelor in Computer Science Engineering',
    date: '2020 - 2024',
    percentage: '9 CGPA'
  },
  {
    name: 'Suditi Global Academy',
    icon: '/src/assets/main/education/akanksha.png',
    description: 'Intermediate XI - XII (CBSE)',
    date: '2018 - 2020',
    percentage: '85%'
  },
  {
    name: 'Akanksha Global Acadmey',
    icon: '/src/assets/main/education/suditi.png',
    description: 'High School IX - X (CBSE)',
    date: '2016 - 2018',
    percentage: '92%'
  }
]
  export default {
    name: 'index',
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
      <li v-for="(item, index) in educationArray" :key="index" class="education__item">
        <div class="education__company">
          <img class="education__company-icon" :src="item.icon" :alt="item.name" />
          <p class="education__company-name">{{ item.name }}</p>
        </div>
        <div class="education__info">
          <strong class="education__info-description">{{ item.description}}</strong>
          <p class="education__info-date">{{ item.date }}</p>
          <p class="education__info-percentage">Percentage <span class="education__info-percentage-value">- {{ item.percentage }}</span></p>
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

.education__item {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  gap: 8px;
  background-color: #F7F9FC;
  padding: 16px 24px;
}

.education__company {
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 16px;
}

.education__company-icon {
  display: flex;
}

.education__company-name {
  font-weight: 600;
  font-size: 14px;
  line-height: 18px;
  color: #2E2E48;
}

.education__info {
  display: flex;
  flex-direction: column;
  gap: 2px;
}

.education__info-description {
  color: #2E2E48;
  font-size: 14px;
  line-height: 18px;
}

.education__info-date {
  color: #79819A;
  font-size: 10px;
  line-height: 14px;
}

.education__info-percentage {
  color: #5D5FEF;
  font-size: 12px;
  line-height: 16px;
}

.education__info-percentage-value {
  color: #79819A;
  font-size: 12px;
  line-height: 16px;
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
