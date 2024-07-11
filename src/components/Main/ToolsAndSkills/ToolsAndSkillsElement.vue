<script>
export default {
  name: "ToolsAndSkills",
  props: {
    icon: {
      type: String,
      required: true
    },
    company: {
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
    }
  }
}
</script>

<template>
  <li class="tools-and-skills__item">
    <img :src="icon" :alt="company" class="tools-and-skills__icon" />
    <div class="tools-and-skills__info">
      <strong class="tools-and-skills__strong">{{ name }}</strong>
      <p class="tools-and-skills__description">{{ description }}</p>
    </div>
  </li>
</template>

<style scoped>
.tools-and-skills__item {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 8px;
  padding: 28px;
  background-color: #F7F9FC;
}

.tools-and-skills__icon {
  display: flex;
}

.tools-and-skills__info {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.tools-and-skills__strong {
  font-size: 14px;
  line-height: 18px;
  color: #2E2E48;
}

.tools-and-skills__description {
  font-size: 10px;
  line-height: 14px;
  color: #79819A;
}

@media screen and (min-width: 576px) {
  .tools-and-skills__item {
    padding: 22px;
  }
}

@media screen and (min-width: 768px) {
  .tools-and-skills__item {
    padding: 20px;
  }
}

@media screen and (min-width: 1024px) {
  .tools-and-skills__item {
    flex: 1 1 calc(33.33% - 16px);
    display: flex;
    flex-direction: column;
    gap: 8px;
    justify-content: center;
    align-items: center;
    padding: 13px;
    background-color: #F7F9FC;
  }

  .tools-and-skills__item:nth-child(n+4) {
    flex-basis: calc(20% - 16px);
  }
}
</style>
