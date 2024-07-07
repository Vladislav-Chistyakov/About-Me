<script>
import Education from './Education/index.vue'
import Achievements from './Achievements/index.vue'
import ToolsAndSkills from './ToolsAndSkills/index.vue'
import LatestProjects from './LatestProjects/index.vue'
import CertificatesAndAwards from './CertificatesAndAwards/index.vue'


export default {
  name: "index",
  components: {
    Education,
    Achievements,
    ToolsAndSkills,
    LatestProjects,
    CertificatesAndAwards
  },
  data () {
    return {
      text: '11111'
    }
  },
  computed: {
    test () {
      return 'test 111123123123123' + this.text
    }
  }
}
</script>

<template>
  <div class="main-block">
    <div class="main-block__wrapper">
      <section class="main-block__section section">
        <div class="section__long">
          <span class="section__long-circle">
            <span class="section__long-circle-center" />
          </span>
          <span class="section__long-line"></span>
        </div>
        <div class="section__info">
          <Education></Education>
        </div>
      </section>
      <section class="main-block__section section">
        <div class="section__long">
          <span class="section__long-circle">
            <span class="section__long-circle-center" />
          </span>
          <span class="section__long-line"></span>
        </div>
        <div class="section__info">
          <Achievements></Achievements>
        </div>
      </section>
      <section class="main-block__section section">
        <div class="section__long">
          <span class="section__long-circle">
            <span class="section__long-circle-center" />
          </span>
          <span class="section__long-line"></span>
        </div>
        <div class="section__info">
          <ToolsAndSkills></ToolsAndSkills>
        </div>
      </section>
      <section class="main-block__section section">
        <div class="section__long">
          <span class="section__long-circle">
            <span class="section__long-circle-center" />
          </span>
          <span class="section__long-line"></span>
        </div>
        <div class="section__info">
          <LatestProjects></LatestProjects>
        </div>
      </section>
      <section class="main-block__section section">
        <div class="section__long">
          <span class="section__long-circle">
            <span class="section__long-circle-center" />
          </span>
          <span class="section__long-line"></span>
        </div>
        <div class="section__info">
          <CertificatesAndAwards></CertificatesAndAwards>
        </div>
      </section>
    </div>
  </div>
</template>

<style scoped>
.main-block {
  padding: 0 48px 0 32px;
}

.main-block__wrapper {
  padding-top: 64px;

  .section {
    display: flex;
    flex-direction: row;
    gap: 32px;
  }

  .section__long {
    display: flex;
    flex-direction: column;
    align-items: center;

    .section__long-circle {
      display: flex;
      align-items: center;
      justify-content: center;
      width: 32px;
      min-height: 32px;
      background: #F9F9F9;
      border-radius: 100%;
      .section__long-circle-center {
        border-radius: 100%;
        background: #5531A7;
        min-height: 8px;
        width: 8px;
      }
    }

    .section__long-line {
      display: block;
      width: 1px;
      background: #E2E6EE;
      height: 100%;
    }
  }

  .section__info {
    width: 100%;
    padding-bottom: 42px;
  }
}
</style>
