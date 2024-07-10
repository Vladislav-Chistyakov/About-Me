<script>

const certificatesAndAwards = [
  {
    name: 'freeCodeCamp',
    company: 'Responsive Web Design',
    icon: '/src/assets/main/certificates/responsiveWebDesign.svg',
    date: 'Dec 2021 - Feb 2022'
  },
  {
    name: 'Data Strcture & Algorithms',
    company: 'Google',
    icon: '/src/assets/main/certificates/google.svg',
    date: 'Mar 2021 - Jun 2021'
  }
]
export default {
  name: 'index',
  data () {
    return {
      certificatesAndAwards: certificatesAndAwards,
    }
  }
}
</script>

<template>
  <div class="certificates-and-awards">
    <h2 class="certificates-and-awards__title heading">Certificates & Awards</h2>
    <ul class="certificates-and-awards__list">
      <li v-for="(item, index) in certificatesAndAwards" :key="index" class="certificates-and-awards__item">
        <div class="certificates-and-awards__block">
          <img :src="item.icon" :alt="item.name" class="certificates-and-awards__icon" />
          <div class="certificates-and-awards__info">
            <p class="certificates-and-awards__info-description">{{ item.name }}</p>
            <strong class="certificates-and-awards__info-strong">{{ item.company }}</strong>
          </div>
        </div>
        <p class="certificates-and-awards__dade">{{ item.date }}</p>
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

.certificates-and-awards__list {
  display: grid;
  grid-template-columns: 1fr;
  gap: 8px;
}

.certificates-and-awards__item {
  background-color: #F7F9FC;
  padding: 15px 23px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  gap: 12px;
}

.certificates-and-awards__item:first-child {
  border-radius: 6px 6px 0 0;
}

.certificates-and-awards__item:last-child {
  border-radius: 0 0 6px 6px;
}

.certificates-and-awards__block {
  display: flex;
  flex-direction: row;
  gap: 12px;
  align-items: center;
}

.certificates-and-awards__icon {
  display: flex;
}

.certificates-and-awards__info {
  display: flex;
  flex-direction: column;
  gap: 4px;
}

.certificates-and-awards__info-strong {
  font-size: 15px;
  line-height: 19px;
  color: #2E2E48;
}

.certificates-and-awards__info-description {
  font-weight: 400;
  font-size: 13px;
  line-height: 17px;
  color: #79819A;
}

.certificates-and-awards__dade {
  font-size: 12px;
  line-height: 16px;
  color: #47516B;
}

@media screen and (min-width: 1024px){
  .heading {
    font-weight: 500;
    font-size: 24px;
    line-height: 32px;
    margin-bottom: 32px;
  }

  .certificates-and-awards__list {
    padding: 0 24px;
  }
}
</style>
