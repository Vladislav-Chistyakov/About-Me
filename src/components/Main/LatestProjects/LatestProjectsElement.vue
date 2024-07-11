<script>
export default {
  name: "LatestProjectsElement",
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
    iconLink: {
      type: String,
      required: true
    },
    labelLink: {
      type: String,
      required: true
    },
    link: {
      type: String,
      required: true
    }
  }
}
</script>

<template>
  <li class="latest-projects__item">
    <div class="latest-projects__block-info">
      <img :src="icon" :alt="name" class="latest-projects__block-info-icon" />
      <div class="latest-projects__block-info-name-and-description">
        <strong class="latest-projects__block-info-name">{{ name }}</strong>
        <p class="latest-projects__block-info-description">{{ description }}</p>
      </div>
    </div>
    <div class="latest-projects__block-link">
      <img :src="iconLink" :alt="labelLink" class="latest-projects__block-link-icon" />
      <a target="_blank" :href="link" class="latest-projects__block-link-project">{{ labelLink }}</a>
    </div>
  </li>
</template>

<style scoped>
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
</style>
