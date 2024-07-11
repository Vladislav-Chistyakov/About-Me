<script>
export default {
  name: "Educationelement",
  props: {
    icon: {
      type: String,
      required: true
    },
    name: {
      type: String,
      required: true
    },
    description: {
      type: String,
      required: true
    },
    date: {
      type: String,
      required: true
    },
    percentage: {
      type: String,
      required: true
    },
  }
}
</script>

<template>
  <li class="education__item">
    <div class="education__company">
      <img class="education__company-icon" :src="icon" :alt="name" />
      <p class="education__company-name">{{ name }}</p>
    </div>
    <div class="education__info">
      <strong class="education__info-description">{{ description}}</strong>
      <p class="education__info-date">{{ date }}</p>
      <p class="education__info-percentage">Percentage <span class="education__info-percentage-value">- {{ percentage }}</span></p>
    </div>
  </li>
</template>

<style scoped>

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
</style>
