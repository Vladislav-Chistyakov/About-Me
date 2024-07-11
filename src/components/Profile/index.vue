<script>
export default {
  name: "index"
}
</script>

<template>
  <div class="profile-block">
    <div class="profile-block__wrapper">
      <div class="profile-block__profile-info profile-info">
        <img alt="profile"
             src="../../assets/profile/profile.png"
             class="profile-info__img"
        >
        <h1 class="profile-info__heading">Anurag Yadav</h1>
      </div>
      <div class="profile-block__description description">
        <span class="description__span text-medium">
          A well-organized, creative and goaloriented graduate possessing excellent communication,
          problem-solving and leadership skills with a flair to explore Computer Science
          Engineering
        </span>
      </div>

      <ul class="profile-block__contacts-list contacts-list border-block">
        <li class="contacts-list__item">

          <img src="../../assets/profile/contacts/mail.svg" alt="mail">

          <div class="contacts-list__block-contact">
            <p class="contacts-list__description text-regular">Email</p>
            <a class="contacts-list__link text-medium" href="mailto:anuragyadavmnp@gmail.com">
              anuragyadavmnp@gmail.com
            </a>
            <a></a>
          </div>
        </li>

        <li class="contacts-list__item">
          <img src="../../assets/profile/contacts/site.svg" alt="site">

          <div class="contacts-list__block-contact text-regular">
            <p class="contacts-list__description">Website</p>
            <a class="contacts-list__link text-medium" href="https://anuragyadav365.github.io/portfolio.html" target="_blank">
              https://anuragyadav365.github.io/portfolio.html
            </a>
          </div>
        </li>

        <li class="contacts-list__item">
          <img src="../../assets/profile/contacts/mobile.svg" alt="mobile">

          <div class="contacts-list__block-contact text-regular">
            <p class="contacts-list__description">Phone</p>
            <a class="contacts-list__link text-medium" href="tel:+919815533309">(+91) 981 5533 309</a>
          </div>
        </li>

        <li class="contacts-list__item">
          <img src="../../assets/profile/contacts/location.svg" alt="location">

          <div class="contacts-list__block-contact text-regular">
            <p class="contacts-list__description">Address</p>
            <a class="contacts-list__link text-medium" href="#">Hallomajra, Chandigarh, India</a>
          </div>
        </li>
      </ul>
      <div class="profile-block__socials socials border-block">
        <h3 class="socials__heading text-regular">Socials</h3>

        <ul class="socials__list">
          <li class="socials__item">
            <img src="../../assets/profile/socials/inst.svg" alt="instagram">

            <div class="socials__block">
              <span class="socials__span text-regular">Instagram</span>
              <a class="socials__link text-medium" target="_blank" href="https://www.instagram.com/">@anurag.yadav.007</a>
            </div>
          </li>

          <li class="socials__item">
            <img src="../../assets/profile/socials/github.svg" alt="github">

            <div class="socials__block">
              <span class="socials__span text-regular">Github</span>
              <a class="socials__link text-medium" target="_blank" href="https://github.com/Vladislav-Chistyakov/About-Me">@anuragyadav365</a>
            </div>
          </li>

          <li class="socials__item">
            <img src="../../assets/profile/socials/x.svg" alt="x">

            <div class="socials__block">
              <span class="socials__span text-regular">Twitter</span>
              <a class="socials__link text-medium" target="_blank" href="https://x.com/?lang=ru">@anuragmnp</a>
            </div>
          </li>

          <li class="socials__item">
            <img src="../../assets/profile/socials/in.svg" alt="linkedin">

            <div class="socials__block">
              <span class="socials__span text-regular">Linkedin</span>
              <a class="socials__link text-medium" target="_blank" href="https://ru.linkedin.com/">@anuragyadav</a>
            </div>
          </li>
        </ul>
      </div>

      <div class="profile-block__learning learning border-block">
        <h3 class="learning__heading text-regular">Languages</h3>
        <ul class="learning__list">
          <li class="learning__item">
            <img src="../../assets/profile/languages/india.svg" alt="india">

            <div class="learning__block">
              <span class="learning__span text-medium">Hindi</span>
              <p class="learning__description text-regular">Native</p>
            </div>
          </li>

          <li class="learning__item">
            <img src="../../assets/profile/languages/eu.svg" alt="eu">

            <div class="learning__block">
              <span class="learning__span text-medium">English</span>
              <p class="learning__description text-regular">Professional working</p>
            </div>
          </li>

          <li class="learning__item">
            <img src="../../assets/profile/languages/spain.svg" alt="spain">

            <div class="learning__block">
              <span class="learning__span text-medium">Spanish</span>
              <p class="learning__description text-regular">Elementary</p>
            </div>
          </li>
        </ul>
      </div>

      <div class="profile-block__hobbies hobbies">
        <h3 class="hobbies__heading text-regular">Hobbies & Interests</h3>

        <ul class="hobbies__list">
          <li class="hobbies__item">
            <img src="../../assets/profile/hobbies/play.svg" alt="play">

            <p class="hobbies__description text-medium">Gaming</p>
          </li>

          <li class="hobbies__item">
            <img src="../../assets/profile/hobbies/earth.svg" alt="earth">

            <p class="hobbies__description text-medium">Travelling</p>
          </li>

          <li class="hobbies__item">
            <img src="../../assets/profile/hobbies/brush.svg" alt="brush">

            <p class="hobbies__description text-medium">Sketching/Graffitti</p>
          </li>

          <li class="hobbies__item">
            <img src="../../assets/profile/hobbies/inbox.svg" alt="inbox">

            <p class="hobbies__description text-medium">Blogging</p>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style scoped>
  .text-regular {
    color: #79819A;
    font-size: 12px;
    line-height: 16px;
    font-weight: 400;
  }

  .text-medium {
    color: #47516B;
    font-size: 14px;
    line-height: 18px;
    font-weight: 500;
  }

  .border-block {
    border-top: 1px solid #E2E6EE;
    padding-top: 32px;
    margin-bottom: 32px;
  }

  .profile-block {
    width: fit-content;
    background: #F7F9FC;
  }

  .profile-block__wrapper {
    padding: 16px;
  }

  .profile-info {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    margin-bottom: 16px;
  }

  .profile-info__img {
    display: block;
    max-width: 120px;
    margin-bottom: 16px;
  }

  .profile-info__heading {
    font-family: "Outfit";
    line-height: 40px;
    font-size: 32px;
    font-weight: 500;
    color: #2E2E48;
  }

  .description {
    padding: 0 38px;
    margin-bottom: 24px;
  }

  .description__span {
    font-family: "Outfit";
    text-align: center;
    display: block;
    line-height: 24px;
    font-size: 18px;
  }

  .contacts-list {
    display: flex;
    flex-direction: column;
    gap: 24px;
    min-width: 270px;
    margin-bottom: 32px;
  }

  .contacts-list__item {
    display: flex;
    flex-direction: row;
    gap: 16px;
    align-items: center;
  }

  .contacts-list__block-contact {
    display: flex;
    flex-direction: column;
    gap: 4px;
  }

  .contacts-list__link {
    word-break: break-all;
  }

  .socials {
    margin-bottom: 32px;
  }

  .socials__heading {
    margin-bottom: 20px;
  }

  .socials__list {
    display: flex;
    flex-direction: column;
    gap: 24px;
  }

  .socials__item {
    display: flex;
    flex-direction: row;
    gap: 16px;
    align-items: center;
  }

  .socials__block {
    display: flex;
    flex-direction: column;
    gap: 4px;
  }

  .learning {
    margin-bottom: 32px;
  }

  .learning__heading {
    margin-bottom: 20px;
  }

  .learning__list {
    display: flex;
    flex-direction: column;
    gap: 24px;
  }

  .learning__item {
    display: flex;
    flex-direction: row;
    gap: 16px;
    align-items: center;
  }

  .learning__block {
    display: flex;
    flex-direction: column;
    gap: 4px;
  }

  .hobbies__heading {
    margin-bottom: 16px;
  }

  .hobbies__list {
    display: flex;
    flex-direction: column;
    gap: 24px;
  }

  .hobbies__item {
    display: flex;
    flex-direction: row;
    gap: 16px;
    align-items: center;
  }

  @media screen and (min-width: 1024px) {
    .profile-block__wrapper {
      max-width: 380px;
      padding: 48px;
    }

    .profile-info {
      display: block;
      margin-bottom: 32px;
    }

    .profile-info__img {
      max-width: fit-content;
    }

    .description {
      padding: 0;
      margin-bottom: 10px;
    }

    .description__span {
      text-align: start;
    }
  }
</style>
