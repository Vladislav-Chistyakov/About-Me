<script>
import CertificatesAndAwardsElement from "./CertificatesAndAwardsElement.vue";

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
  components: {CertificatesAndAwardsElement},
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
      <CertificatesAndAwardsElement
          v-for="(item, index) in certificatesAndAwards"
          :key="index"
          :date="item.date"
          :company="item.company"
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

.certificates-and-awards__list {
  display: grid;
  grid-template-columns: 1fr;
  gap: 8px;
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
