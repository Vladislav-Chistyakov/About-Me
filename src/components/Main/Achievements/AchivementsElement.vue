<script>
export default {
  name: "AchivementsElement",
  props: {
    present: {
      type: String,
      required: true
    },
    date: {
      type: String,
      required: true
    },
    location: {
      type: String,
      required: true
    },
    icon: {
      type: String,
      required: true
    },
    company: {
      type: String,
      required: true
    },
    speciality: {
      type: String,
      required: true
    },
    description: {
      type: String,
      required: true
    }
  }
}
</script>

<template>
  <li class="achievements__item">
    <div class="achievements__long">
          <span class="achievements__long-circle">
            <span class="achievements__long-circle-center" />
          </span>
      <span class="achievements__long-line"></span>
    </div>
    <div class="achievements__item-block">
      <div class="achievements__item-block-wrapper">
        <div class="achievements__item-block-info">
          <span v-if="present" class="achievements__item-block-present">Present</span>
          <span v-if="date" class="achievements__item-block-date">{{ date }}</span>
          <div v-if="location" class="achievements__item-block-location">
            <svg width="8" height="11" viewBox="0 0 8 11" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M3.52861 10.046C2.89176 9.50281 2.30146 8.90728 1.76388 8.26566C0.957143 7.30212 -0.000854047 5.86714 -0.000854047 4.49973C-0.0015691 3.07158 0.858442 1.78375 2.17787 1.2372C3.49729 0.690637 5.01606 0.99308 6.02545 2.00339C6.68922 2.66421 7.06105 3.56311 7.05809 4.49973C7.05809 5.86714 6.10007 7.30212 5.29334 8.26566C4.75576 8.90728 4.16546 9.50281 3.52861 10.046ZM3.52861 2.9871C2.9882 2.9871 2.48884 3.27541 2.21864 3.74342C1.94843 4.21142 1.94843 4.78803 2.21864 5.25604C2.48884 5.72405 2.9882 6.01236 3.52861 6.01236C4.36401 6.01236 5.04123 5.33513 5.04123 4.49973C5.04123 3.66433 4.36401 2.9871 3.52861 2.9871Z" fill="#79819A"/>
            </svg>
            <span class="achievements__item-block-location-info">{{ location }}</span>
          </div>
        </div>
        <div class="achievements__item-block-company">
          <img :src="icon" :alt="company" class="achievements__item-block-company-icon" />

          <div class="achievements__item-block-company-info">
            <p class="achievements__item-block-company-speciality">{{ speciality }}</p>
            <strong class="achievements__item-block-company-name">{{ company }}</strong>
          </div>
        </div>
      </div>
      <p class="achievements__item-description">
        {{ description }}
      </p>
    </div>
  </li>
</template>

<style scoped>

.achievements__item {
  display: flex;
  flex-direction: row;
  gap: 8px;
}

.achievements__item-block {
  display: flex;
  flex-direction: column;
  align-items: start;
  gap: 8px;
  padding-top: 6px;
  padding-bottom: 20px;
}

.achievements__item-block-wrapper {
  min-width: 220px;
}

.achievements__item-block-info {
  display: flex;
  align-items: center;
  gap: 6px;
  margin-bottom: 8px;
}

.achievements__item-block-present {
  border-radius: 4px;
  background: #EFE2F9;
  padding: 2px;
  color: #9251F7;
  font-size: 11px;
}

.achievements__item-block-date {
  font-size: 11px;
  color: #47516B;
}

.achievements__item-block-location {
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 4px;
}

.achievements__item-block-location-info {
  font-size: 11px;
  color: #79819A;
}

.achievements__item-block-company {
  display: flex;
  align-items: center;
  gap: 16px;
}

.achievements__item-block-company-info {
  display: flex;
  flex-direction: column;
  gap: 4px;
}

.achievements__item-block-company-icon {
  display: flex;
}

.achievements__item-block-company-name {
  font-size: 14px;
  line-height: 18px;
  color: #2E2E48;
}

.achievements__item-block-company-speciality {
  font-size: 12px;
  line-height: 16px;
  color: #79819A;
}

.achievements__item-description {
  font-size: 12px;
  line-height: 16px;
  color: #79819A;
}

.achievements__long {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.achievements__long-circle {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 24px;
  min-height: 24px;
  background: #FFFFFF;
  border-radius: 100%;
}

.achievements__long-line {
  display: block;
  width: 1px;
  background: #F7F9FC;
  height: 100%;
}

.achievements__long-circle-center {
  border-radius: 100%;
  background: #2E2E48;
  min-height: 8px;
  width: 8px;
}

@media screen and (min-width: 1024px) {
  .achievements__item {
    display: flex;
    flex-direction: row;
    gap: 16px;
  }

  .achievements__item-block {
    flex-direction: column;
    align-items: start;
    gap: 16px;
    padding-top: 6px;
    padding-bottom: 20px;
  }

  .achievements__item-block-wrapper {
    min-width: 250px;
  }
}

</style>
