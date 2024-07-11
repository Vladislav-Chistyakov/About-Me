<script>
export default {
  name: "CertificatesAndAwardsElement",
  props: {
    icon: {
      type: String,
      required: true
    },
    name: {
      type: String,
      required: true
    },
    company: {
      type: String,
      required: true
    },
    date: {
      type: String,
      required: true
    }
  }
}
</script>

<template>
  <li class="certificates-and-awards__item">
    <div class="certificates-and-awards__block">
      <img :src="icon" :alt="name" class="certificates-and-awards__icon" />
      <div class="certificates-and-awards__info">
        <p class="certificates-and-awards__info-description">{{ name }}</p>
        <strong class="certificates-and-awards__info-strong">{{ company }}</strong>
      </div>
    </div>
    <p class="certificates-and-awards__dade">{{ date }}</p>
  </li>
</template>

<style scoped>
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

</style>
