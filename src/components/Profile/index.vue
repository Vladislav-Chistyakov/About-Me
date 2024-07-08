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
          <svg class="contacts-list__svg" width="33" height="33" viewBox="0 0 33 33" fill="none" xmlns="http://www.w3.org/2000/svg">
            <g clip-path="url(#clip0_7_41)">
              <rect x="0.404037" y="0.0555573" width="32.2694" height="32.2694" rx="16.1347" fill="#E2E6EE"/>
              <path d="M23.2615 22.913H9.81592C8.8877 22.913 8.13522 22.1606 8.13522 21.2323V11.0751C8.17439 10.1755 8.91551 9.46661 9.81592 9.46747H23.2615C24.1897 9.46747 24.9422 10.2199 24.9422 11.1482V21.2323C24.9422 22.1606 24.1897 22.913 23.2615 22.913ZM9.81592 12.7179V21.2323H23.2615V12.7179L16.5387 17.1987L9.81592 12.7179ZM10.4882 11.1482L16.5387 15.1818L22.5892 11.1482H10.4882Z" fill="#79819A"/>
            </g>
            <defs>
              <clipPath id="clip0_7_41">
                <rect x="0.404037" y="0.0555573" width="32.2694" height="32.2694" rx="16.1347" fill="white"/>
              </clipPath>
            </defs>
          </svg>
          <div class="contacts-list__block-contact">
            <p class="contacts-list__description text-regular">Email</p>
            <a class="contacts-list__link text-medium" href="mailto:anuragyadavmnp@gmail.com">
              anuragyadavmnp@gmail.com
            </a>
            <a></a>
          </div>
        </li>

        <li class="contacts-list__item">
<!--          <svg class="contacts-list__svg" width="33" height="34" viewBox="0 0 33 34" fill="none" xmlns="http://www.w3.org/2000/svg">-->
<!--            <g clip-path="url(#clip0_7_49)">-->
<!--              <rect x="0.404037" y="0.942757" width="32.2694" height="32.2694" rx="16.1347" fill="#E2E6EE"/>-->
<!--              <path d="M13.5681 24.2498C11.8688 24.2498 10.3368 23.2262 9.68634 21.6563C9.03593 20.0863 9.39519 18.2792 10.5966 17.0774L12.3798 15.2942L13.5681 16.4825L11.7857 18.2648C11.1488 18.9018 10.9 19.8301 11.1332 20.7002C11.3663 21.5702 12.0459 22.2498 12.9159 22.483C13.786 22.7161 14.7144 22.4674 15.3513 21.8304L17.1337 20.0481L18.3219 21.2371L16.5395 23.0195C15.753 23.8099 14.6831 24.2529 13.5681 24.2498ZM14.1622 20.6422L12.974 19.4539L18.9161 13.5118L20.1043 14.7001L14.163 20.6413L14.1622 20.6422ZM20.6993 18.8598L19.5102 17.6715L21.2926 15.8892C21.9382 15.2541 22.1936 14.3216 21.9617 13.4463C21.7298 12.5709 21.0462 11.8871 20.1709 11.655C19.2955 11.4229 18.363 11.6781 17.7278 12.3236L15.9446 14.1059L14.7563 12.9177L16.5395 11.1345C18.1825 9.50586 20.8329 9.51166 22.4687 11.1475C24.1045 12.7833 24.1103 15.4336 22.4817 17.0766L20.6993 18.859V18.8598Z" fill="#79819A"/>-->
<!--            </g>-->
<!--            <defs>-->
<!--              <clipPath id="clip0_7_49">-->
<!--                <rect x="0.404037" y="0.942757" width="32.2694" height="32.2694" rx="16.1347" fill="white"/>-->
<!--              </clipPath>-->
<!--            </defs>-->
<!--          </svg>-->
          <svg class="contacts-list__svg" width="33" height="34" viewBox="0 0 33 34" fill="none" xmlns="http://www.w3.org/2000/svg">
            <g clip-path="url(#clip0_25_49)">
              <rect x="0.404037" y="0.942757" width="32.2694" height="32.2694" rx="16.1347" fill="#E2E6EE"/>
              <path d="M13.5681 24.2498C11.8688 24.2498 10.3368 23.2262 9.68634 21.6563C9.03593 20.0863 9.39519 18.2792 10.5966 17.0774L12.3798 15.2942L13.5681 16.4825L11.7857 18.2648C11.1488 18.9018 10.9 19.8301 11.1332 20.7002C11.3663 21.5702 12.0459 22.2498 12.9159 22.483C13.786 22.7161 14.7144 22.4674 15.3513 21.8304L17.1337 20.0481L18.3219 21.2371L16.5395 23.0195C15.753 23.8099 14.6831 24.2529 13.5681 24.2498ZM14.1622 20.6422L12.974 19.4539L18.9161 13.5118L20.1043 14.7001L14.163 20.6413L14.1622 20.6422ZM20.6993 18.8598L19.5102 17.6715L21.2926 15.8892C21.9382 15.2541 22.1936 14.3216 21.9617 13.4463C21.7298 12.5709 21.0462 11.8871 20.1709 11.655C19.2955 11.4229 18.363 11.6781 17.7278 12.3236L15.9446 14.1059L14.7563 12.9177L16.5395 11.1345C18.1825 9.50586 20.8329 9.51166 22.4687 11.1475C24.1045 12.7833 24.1103 15.4336 22.4817 17.0766L20.6993 18.859V18.8598Z" fill="#79819A"/>
            </g>
            <defs>
              <clipPath id="clip0_25_49">
                <rect x="0.404037" y="0.942757" width="32.2694" height="32.2694" rx="16.1347" fill="white"/>
              </clipPath>
            </defs>
          </svg>
          <div class="contacts-list__block-contact text-regular">
            <p class="contacts-list__description">Website</p>
            <a class="contacts-list__link text-medium" href="https://anuragyadav365.github.io/portfolio.html" target="_blank">
              https://anuragyadav365.github.io/portfolio.html
            </a>
          </div>
        </li>

        <li class="contacts-list__item">
          <svg class="contacts-list__svg" width="33" height="34" viewBox="0 0 33 34" fill="none" xmlns="http://www.w3.org/2000/svg">
            <g clip-path="url(#clip0_7_57)">
              <rect x="0.404037" y="0.829956" width="32.2694" height="32.2694" rx="16.1347" fill="#E2E6EE"/>
              <path d="M22.4191 23.6874C15.2495 23.6976 9.80829 18.1911 9.81596 11.0843C9.81596 10.6202 10.1922 10.2419 10.6563 10.2419H12.8743C13.2907 10.2419 13.6445 10.5478 13.7057 10.9598C13.8522 11.9471 14.1397 12.9082 14.5593 13.8139L14.6456 14.0003C14.7657 14.2595 14.6843 14.5674 14.4519 14.7334C13.765 15.2239 13.5025 16.2113 14.0376 16.9817C14.7091 17.9485 15.5556 18.7948 16.5222 19.466C17.2925 20.001 18.2798 19.7385 18.7703 19.0518C18.9364 18.8192 19.2445 18.7378 19.5038 18.8579L19.6893 18.9438C20.5951 19.3634 21.5563 19.6509 22.5437 19.7974C22.9557 19.8585 23.2615 20.2123 23.2615 20.6288V22.8471C23.2615 23.3112 22.8844 23.6874 22.4202 23.6874L22.4191 23.6874Z" fill="#79819A"/>
            </g>
            <defs>
              <clipPath id="clip0_7_57">
                <rect x="0.404037" y="0.829956" width="32.2694" height="32.2694" rx="16.1347" fill="white"/>
              </clipPath>
            </defs>
          </svg>
          <div class="contacts-list__block-contact text-regular">
            <p class="contacts-list__description">Phone</p>
            <a class="contacts-list__link text-medium" href="tel:+919815533309">(+91) 981 5533 309</a>
          </div>
        </li>

        <li class="contacts-list__item">
          <svg class="contacts-list__svg" width="33" height="33" viewBox="0 0 33 33" fill="none" xmlns="http://www.w3.org/2000/svg">
            <g clip-path="url(#clip0_7_65)">
              <rect x="0.404037" y="0.0656433" width="32.2694" height="32.2694" rx="16.1347" fill="#E2E6EE"/>
              <path d="M16.5387 23.7634C15.4773 22.8581 14.4935 21.8655 13.5975 20.7962C12.2529 19.1903 10.6563 16.7986 10.6563 14.5196C10.6551 12.1394 12.0884 9.99299 14.2875 9.08206C16.4865 8.17113 19.0178 8.6752 20.7001 10.3591C21.8064 11.4604 22.4261 12.9586 22.4212 14.5196C22.4212 16.7986 20.8245 19.1903 19.4799 20.7962C18.584 21.8655 17.6001 22.8581 16.5387 23.7634ZM16.5387 11.9986C15.638 11.9986 14.8058 12.4791 14.3554 13.2591C13.9051 14.0391 13.9051 15.0001 14.3554 15.7801C14.8058 16.5602 15.638 17.0407 16.5387 17.0407C17.9311 17.0407 19.0598 15.912 19.0598 14.5196C19.0598 13.1273 17.9311 11.9986 16.5387 11.9986Z" fill="#79819A"/>
            </g>
            <defs>
              <clipPath id="clip0_7_65">
                <rect x="0.404037" y="0.0656433" width="32.2694" height="32.2694" rx="16.1347" fill="white"/>
              </clipPath>
            </defs>
          </svg>
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
            <svg width="33" height="33" viewBox="0 0 33 33" fill="none" xmlns="http://www.w3.org/2000/svg">
              <rect x="0.404037" y="0.814758" width="32.2694" height="32.2694" rx="16.1347" fill="url(#paint0_radial_7_77)"/>
              <rect x="0.404037" y="0.814758" width="32.2694" height="32.2694" rx="16.1347" fill="url(#paint1_radial_7_77)" fill-opacity="0.2"/>
              <path d="M13.1781 16.9498C13.1781 15.0934 14.6827 13.588 16.5391 13.588C18.3956 13.588 19.9009 15.0934 19.9009 16.9498C19.9009 18.8063 18.3956 20.3116 16.5391 20.3116C14.6827 20.3116 13.1781 18.8063 13.1781 16.9498V16.9498ZM11.3608 16.9498C11.3608 19.8098 13.6791 22.1282 16.5391 22.1282C19.3991 22.1282 21.7174 19.8098 21.7174 16.9498C21.7174 14.0899 19.3991 11.7715 16.5391 11.7715C13.6791 11.7715 11.3609 14.0897 11.3609 16.9498H11.3608ZM20.7124 11.5662C20.7123 11.8056 20.7831 12.0396 20.916 12.2386C21.0489 12.4377 21.2379 12.5929 21.459 12.6845C21.6801 12.7762 21.9234 12.8003 22.1581 12.7537C22.3929 12.7071 22.6086 12.5919 22.7779 12.4227C22.9472 12.2536 23.0625 12.038 23.1093 11.8033C23.1561 11.5685 23.1322 11.3252 23.0407 11.104C22.9492 10.8829 22.7942 10.6938 22.5952 10.5608C22.3963 10.4277 22.1623 10.3566 21.923 10.3565H21.9225C21.6017 10.3567 21.294 10.4842 21.0671 10.711C20.8402 10.9378 20.7126 11.2454 20.7124 11.5662V11.5662ZM12.465 25.1585C11.4817 25.1138 10.9473 24.95 10.5922 24.8116C10.1214 24.6283 9.78544 24.41 9.43224 24.0573C9.07904 23.7046 8.8604 23.369 8.67791 22.8981C8.53947 22.5432 8.3757 22.0086 8.331 21.0254C8.28211 19.9624 8.27235 19.6431 8.27235 16.95C8.27235 14.2569 8.28292 13.9385 8.331 12.8746C8.37578 11.8914 8.54076 11.3579 8.67791 11.0019C8.86121 10.5311 9.07952 10.1951 9.43224 9.84191C9.78496 9.48871 10.1206 9.27007 10.5922 9.08758C10.9472 8.94914 11.4817 8.78537 12.465 8.74067C13.5279 8.69178 13.8473 8.68202 16.5391 8.68202C19.231 8.68202 19.5506 8.69243 20.6145 8.74084C21.5977 8.78561 22.1312 8.95059 22.4872 9.08775C22.9581 9.27024 23.294 9.48935 23.6472 9.84207C24.0004 10.1948 24.2182 10.5312 24.4015 11.002C24.54 11.357 24.7038 11.8916 24.7485 12.8748C24.7973 13.9387 24.8071 14.2571 24.8071 16.9502C24.8071 19.6432 24.7973 19.9617 24.7485 21.0255C24.7037 22.0088 24.5391 22.5432 24.4015 22.8983C24.2182 23.3691 23.9999 23.7051 23.6472 24.0575C23.2945 24.4099 22.9581 24.6285 22.4872 24.8118C22.1323 24.9502 21.5977 25.114 20.6145 25.1587C19.5515 25.2076 19.2322 25.2173 16.5391 25.2173C13.8461 25.2173 13.5276 25.2076 12.465 25.1587V25.1585ZM12.3815 6.92634C11.3079 6.97523 10.5743 7.14545 9.93364 7.39475C9.27056 7.65218 8.70849 7.99756 8.14722 8.55794C7.58595 9.11832 7.24146 9.68048 6.98402 10.3444C6.73473 10.9854 6.56451 11.7186 6.51562 12.7922C6.46592 13.8674 6.45454 14.2112 6.45454 16.9498C6.45454 19.6885 6.46592 20.0323 6.51562 21.1075C6.56451 22.1812 6.73473 22.9143 6.98402 23.5553C7.24146 24.2184 7.58603 24.7816 8.14722 25.3417C8.70841 25.9019 9.26976 26.2468 9.93364 26.5049C10.5755 26.7542 11.3079 26.9245 12.3815 26.9734C13.4573 27.0222 13.8005 27.0344 16.5391 27.0344C19.2778 27.0344 19.6215 27.0231 20.6968 26.9734C21.7704 26.9245 22.5035 26.7542 23.1446 26.5049C23.8077 26.2468 24.3698 25.9021 24.931 25.3417C25.4923 24.7814 25.8361 24.2184 26.0942 23.5553C26.3435 22.9143 26.5145 22.1811 26.5626 21.1075C26.6115 20.0315 26.6229 19.6885 26.6229 16.9498C26.6229 14.2112 26.6115 13.8674 26.5626 12.7922C26.5137 11.7185 26.3435 10.985 26.0942 10.3444C25.8361 9.68128 25.4914 9.11921 24.931 8.55794C24.3706 7.99667 23.8077 7.65218 23.1454 7.39475C22.5035 7.14545 21.7704 6.97442 20.6976 6.92634C19.6222 6.87721 19.2786 6.86526 16.5403 6.86526C13.8021 6.86526 13.4577 6.87664 12.3819 6.92634" fill="white"/>
              <defs>
                <radialGradient id="paint0_radial_7_77" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse" gradientTransform="translate(2.49248 32.3772) scale(40.9701)">
                  <stop offset="0.09" stop-color="#FA8F21"/>
                  <stop offset="0.78" stop-color="#D82D7E"/>
                </radialGradient>
                <radialGradient id="paint1_radial_7_77" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse" gradientTransform="translate(16.5387 32.0757) scale(25.2104)">
                  <stop offset="0.713542" stop-color="#8C3AAA" stop-opacity="0"/>
                  <stop offset="1" stop-color="#8C3AAA"/>
                </radialGradient>
              </defs>
            </svg>
            <div class="socials__block">
              <span class="socials__span text-regular">Instagram</span>
              <a class="socials__link text-medium" target="_blank" href="https://www.instagram.com/">@anurag.yadav.007</a>
            </div>
          </li>

          <li class="socials__item">
            <svg width="33" height="33" viewBox="0 0 33 33" fill="none" xmlns="http://www.w3.org/2000/svg">
              <rect x="0.404037" y="0.0167847" width="32.2694" height="32.2694" rx="16.1347" fill="white"/>
              <path d="M17.1421 5.05887C11.2408 5.05887 6.45454 9.84423 6.45454 15.7464C6.45454 20.4686 9.51653 24.4746 13.764 25.8881C14.2974 25.9869 14.4702 25.6556 14.4702 25.3742V23.3845C11.4973 24.0311 10.8783 22.1234 10.8783 22.1234C10.392 20.8881 9.6911 20.5594 9.6911 20.5594C8.7212 19.8959 9.76502 19.9101 9.76502 19.9101C10.8382 19.985 11.4029 21.0119 11.4029 21.0119C12.3559 22.6453 13.9029 22.1732 14.513 21.8998C14.6083 21.2096 14.8853 20.7375 15.1916 20.4712C12.8181 20.1996 10.3226 19.2831 10.3226 15.1889C10.3226 14.0213 10.7403 13.0683 11.4234 12.3202C11.3129 12.0503 10.9469 10.9629 11.5276 9.49154C11.5276 9.49154 12.4253 9.20476 14.4676 10.587C15.3199 10.3501 16.2337 10.2317 17.1421 10.2272C18.0506 10.2317 18.9652 10.3501 19.8194 10.587C21.8598 9.20476 22.7558 9.49154 22.7558 9.49154C23.3373 10.9638 22.9713 12.0512 22.8609 12.3202C23.5466 13.0683 23.9608 14.0222 23.9608 15.1889C23.9608 19.2938 21.4608 20.1978 19.081 20.4623C19.464 20.7937 19.814 21.4438 19.814 22.4413V25.3742C19.814 25.6583 19.985 25.9923 20.5274 25.8872C24.7713 24.472 27.8297 20.4668 27.8297 15.7464C27.8297 9.84423 23.0443 5.05887 17.1421 5.05887Z" fill="#24292E"/>
            </svg>
            <div class="socials__block">
              <span class="socials__span text-regular">Github</span>
              <a class="socials__link text-medium" target="_blank" href="https://github.com/Vladislav-Chistyakov/About-Me">@anuragyadav365</a>
            </div>
          </li>

          <li class="socials__item">
            <svg width="33" height="33" viewBox="0 0 33 33" fill="none" xmlns="http://www.w3.org/2000/svg">
              <rect x="0.404037" y="0.218811" width="32.2694" height="32.2694" rx="16.1347" fill="#00ACEE"/>
              <path d="M23.2573 11.8896C24.0106 11.4392 24.5743 10.7301 24.843 9.8946C24.1352 10.3146 23.3607 10.6105 22.5531 10.7694C21.4334 9.58495 19.6594 9.29671 18.2223 10.0657C16.7852 10.8348 16.0408 12.4707 16.4051 14.0594C13.5056 13.9138 10.8042 12.5441 8.97307 10.2912C8.01746 11.9395 8.5058 14.0466 10.0891 15.1064C9.51653 15.088 8.95671 14.933 8.45626 14.6543C8.45626 14.6695 8.45626 14.6846 8.45626 14.6997C8.45659 16.4167 9.66667 17.8956 11.3496 18.2359C10.8185 18.3804 10.2615 18.4016 9.72098 18.2981C10.1943 19.7664 11.5475 20.7723 13.0899 20.8023C11.8125 21.805 10.2348 22.3487 8.61088 22.346C8.32304 22.3464 8.03542 22.3299 7.74953 22.2965C9.39862 23.3562 11.318 23.9186 13.2782 23.9166C16.0053 23.9354 18.6262 22.8602 20.5545 20.9317C22.4829 19.0032 23.5578 16.3823 23.5388 13.6552C23.5388 13.4988 23.5352 13.3434 23.5279 13.1888C24.2342 12.6783 24.8437 12.046 25.3279 11.3215C24.6699 11.6132 23.972 11.8046 23.2573 11.8896Z" fill="white"/>
            </svg>
            <div class="socials__block">
              <span class="socials__span text-regular">Twitter</span>
              <a class="socials__link text-medium" target="_blank" href="https://x.com/?lang=ru">@anuragmnp</a>
            </div>
          </li>

          <li class="socials__item">
            <svg width="33" height="33" viewBox="0 0 33 33" fill="none" xmlns="http://www.w3.org/2000/svg">
              <rect x="0.404037" y="0.420837" width="32.2694" height="32.2694" rx="16.1347" fill="#0077B5"/>
              <path d="M17.3791 24.1186H14.0177V14.0345H17.3791V15.7152C18.0956 14.8036 19.1821 14.2602 20.3413 14.2336C22.4259 14.2452 24.1079 15.9415 24.1019 18.0261V24.1186H20.7405V18.4463C20.606 17.5073 19.8007 16.8106 18.8522 16.8126C18.4373 16.8258 18.0457 17.0074 17.7677 17.3157C17.4897 17.624 17.3494 18.0322 17.3791 18.4463V24.1186ZM12.337 24.1186H8.97559V14.0345H12.337V24.1186ZM10.6563 12.3538C9.72806 12.3538 8.97559 11.6013 8.97559 10.6731C8.97559 9.74484 9.72806 8.99237 10.6563 8.99237C11.5845 8.99237 12.337 9.74484 12.337 10.6731C12.337 11.1188 12.1599 11.5463 11.8447 11.8615C11.5295 12.1767 11.102 12.3538 10.6563 12.3538Z" fill="white"/>
            </svg>
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
            <svg class="learning__svg" width="33" height="25" viewBox="0 0 33 25" fill="none" xmlns="http://www.w3.org/2000/svg">
              <mask id="mask0_7_110" style="mask-type:luminance" maskUnits="userSpaceOnUse" x="0" y="0" width="33" height="25">
                <rect x="0.404037" y="0.203674" width="32.2694" height="24.202" fill="white"/>
              </mask>
              <g mask="url(#mask0_7_110)">
                <path fill-rule="evenodd" clip-rule="evenodd" d="M0.404037 0.203674V24.4057H32.6734V0.203674H0.404037Z" fill="#F7FCFF"/>
                <mask id="mask1_7_110" style="mask-type:luminance" maskUnits="userSpaceOnUse" x="0" y="0" width="33" height="25">
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M0.404037 0.203674V24.4057H32.6734V0.203674H0.404037Z" fill="white"/>
                </mask>
                <g mask="url(#mask1_7_110)">
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M0.404037 0.203674V8.27101H32.6734V0.203674H0.404037Z" fill="#FF8C1A"/>
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M0.404037 16.3384V24.4057H32.6734V16.3384H0.404037Z" fill="#5EAA22"/>
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M12.5051 12.3047C12.5051 14.5324 14.311 16.3383 16.5387 16.3383C18.7665 16.3383 20.5724 14.5324 20.5724 12.3047C20.5724 10.0769 18.7665 8.271 16.5387 8.271C14.311 8.271 12.5051 10.0769 12.5051 12.3047ZM19.564 12.3047C19.564 13.9755 18.2095 15.3299 16.5387 15.3299C14.8679 15.3299 13.5135 13.9755 13.5135 12.3047C13.5135 10.6339 14.8679 9.27944 16.5387 9.27944C18.2095 9.27944 19.564 10.6339 19.564 12.3047Z" fill="#3D58DB"/>
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M16.5332 13.1726L15.6922 16.2722L16.1847 13.0985L14.1557 15.5881L15.8964 12.8891L13.0303 14.3382L15.7183 12.5806L12.5105 12.7386L15.6811 12.2262L12.6863 11.0659L15.7912 11.8874L13.5273 9.6093L16.0296 11.6226L14.888 8.62069L16.355 11.4777L16.5332 8.271L16.7113 11.4777L18.1784 8.62069L17.0368 11.6226L19.5391 9.6093L17.2752 11.8874L20.38 11.0659L17.3853 12.2262L20.5558 12.7386L17.3481 12.5806L20.0361 14.3382L17.1699 12.8891L18.9107 15.5881L16.8817 13.0985L17.3741 16.2722L16.5332 13.1726Z" fill="#3D58DB"/>
                </g>
              </g>
            </svg>

            <div class="learning__block">
              <span class="learning__span text-medium">Hindi</span>
              <p class="learning__description text-regular">Native</p>
            </div>
          </li>

          <li class="learning__item">
            <svg class="learning__svg" width="33" height="25" viewBox="0 0 33 25" fill="none" xmlns="http://www.w3.org/2000/svg">
              <g clip-path="url(#clip0_7_129)">
                <mask id="mask0_7_129" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="-3" y="-2" width="39" height="29">
                  <path d="M31.777 -1.61115H1.3004C-0.679804 -1.61115 -2.28508 0.0743948 -2.28508 2.15361V22.8598C-2.28508 24.939 -0.679804 26.6245 1.3004 26.6245H31.777C33.7572 26.6245 35.3625 24.939 35.3625 22.8598V2.15361C35.3625 0.0743948 33.7572 -1.61115 31.777 -1.61115Z" fill="white"/>
                </mask>
                <g mask="url(#mask0_7_129)">
                  <path d="M31.777 -1.61115H1.3004C-0.679804 -1.61115 -2.28508 0.0743948 -2.28508 2.15361V22.8598C-2.28508 24.939 -0.679804 26.6245 1.3004 26.6245H31.777C33.7572 26.6245 35.3625 24.939 35.3625 22.8598V2.15361C35.3625 0.0743948 33.7572 -1.61115 31.777 -1.61115Z" fill="#22438B"/>
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M3.09314 0.27124L-0.538956 0.320182L-0.492344 4.036L29.952 24.7949L33.6038 24.7252L33.5357 21.032L3.09314 0.27124Z" fill="white"/>
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M1.3004 0.27124L-0.49234 2.15362L31.777 24.7422L33.5698 22.8598L1.3004 0.27124Z" fill="#C7152A"/>
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M29.9843 0.27124H33.5698V4.036C33.5698 4.036 12.505 17.9581 3.12541 24.7949C3.01247 24.8777 -0.456485 24.8005 -0.456485 24.8005L-0.73436 21.2221L29.9843 0.27124Z" fill="white"/>
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M31.8541 0.218506L33.5698 2.15359L1.3004 24.7421L-0.49234 22.8598L31.8541 0.218506Z" fill="#C7152A"/>
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M12.0569 0.27124H21.0206V7.80076H33.5698V17.2127H21.0206V24.7422H12.0569V17.2127H-0.49234V7.80076H12.0569V0.27124Z" fill="white"/>
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M13.8496 0.27124H19.2278V9.68314H33.5698V15.3303H19.2278V24.7422H13.8496V15.3303H-0.49234V9.68314H13.8496V0.27124Z" fill="#C7152A"/>
                  <path d="M31.777 -0.669983H1.3004C-0.184761 -0.669983 -1.38872 0.594172 -1.38872 2.15359V22.8598C-1.38872 24.4192 -0.184761 25.6833 1.3004 25.6833H31.777C33.2622 25.6833 34.4661 24.4192 34.4661 22.8598V2.15359C34.4661 0.594172 33.2622 -0.669983 31.777 -0.669983Z" stroke="black" stroke-opacity="0.1" stroke-width="2.01683"/>
                </g>
              </g>
              <defs>
                <clipPath id="clip0_7_129">
                  <rect width="37.6476" height="28.2357" fill="white" transform="translate(-2.28508 -1.61115)"/>
                </clipPath>
              </defs>
            </svg>

            <div class="learning__block">
              <span class="learning__span text-medium">English</span>
              <p class="learning__description text-regular">Professional working</p>
            </div>
          </li>

          <li class="learning__item">
            <svg class="learning__svg" width="33" height="25" viewBox="0 0 33 25" fill="none" xmlns="http://www.w3.org/2000/svg">
              <g clip-path="url(#clip0_7_146)">
                <mask id="mask0_7_146" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="0" y="0" width="33" height="25">
                  <path d="M29.6001 0.607727H3.47731C1.77999 0.607727 0.404037 2.05248 0.404037 3.83466V21.5828C0.404037 23.365 1.77999 24.8097 3.47731 24.8097H29.6001C31.2974 24.8097 32.6734 23.365 32.6734 21.5828V3.83466C32.6734 2.05248 31.2974 0.607727 29.6001 0.607727Z" fill="white"/>
                </mask>
                <g mask="url(#mask0_7_146)">
                  <path d="M29.6001 0.607727H3.47731C1.77999 0.607727 0.404037 2.05248 0.404037 3.83466V21.5828C0.404037 23.365 1.77999 24.8097 3.47731 24.8097H29.6001C31.2974 24.8097 32.6734 23.365 32.6734 21.5828V3.83466C32.6734 2.05248 31.2974 0.607727 29.6001 0.607727Z" fill="#CD0B20"/>
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M0.404037 7.06158H32.6734V18.3559H0.404037V7.06158Z" fill="#FFCB00"/>
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M14.2338 10.6467V14.7127C14.2338 15.8421 13.2012 16.7456 11.9288 16.7456H8.85555C7.58629 16.7424 6.5506 15.834 6.5506 14.7094V10.6435C6.5506 9.72059 7.23901 8.94936 8.18558 8.69927C8.47139 7.86027 9.35035 8.61214 10.3922 8.61214C11.4402 8.61214 12.313 7.86511 12.5988 8.70088C13.5423 8.95742 14.2338 9.73028 14.2338 10.6467Z" fill="#C8B47C"/>
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M14.2338 11.902H15.7704V16.7424H14.2338V11.902ZM5.01396 11.902H6.5506V16.7424H5.01396V11.902Z" fill="#B5B5B5"/>
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M14.2338 15.1289H15.7704V16.7424H14.2338V15.1289ZM5.01396 15.1289H6.5506V16.7424H5.01396V15.1289Z" fill="#165C96"/>
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M14.2338 10.2885H15.7704V11.902H14.2338V10.2885ZM5.01396 10.2885H6.5506V11.902H5.01396V10.2885Z" fill="#A0790A"/>
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M8.08722 10.2885H9.62386V12.7087H8.08722V10.2885ZM11.1605 13.5154H12.6971V15.9357H11.1605V13.5154Z" fill="#D20636"/>
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M11.1605 10.2885H12.6971V12.7087H11.1605V10.2885Z" fill="#A18793"/>
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M8.08722 13.5154H9.62385V15.9356H8.08722V13.5154Z" fill="#FFE100"/>
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M9.62386 10.2885L8.08722 8.67505H12.6971L11.1605 10.2885H9.62386Z" fill="#B6161A"/>
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M9.62386 7.06158H11.1605V8.67505H9.62386V7.06158Z" fill="#AC9300"/>
                </g>
              </g>
              <defs>
                <clipPath id="clip0_7_146">
                  <rect width="32.2694" height="24.202" fill="white" transform="translate(0.404037 0.607727)"/>
                </clipPath>
              </defs>
            </svg>

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
            <svg class="hobbies__svg" width="35" height="35" viewBox="0 0 35 35" fill="none" xmlns="http://www.w3.org/2000/svg">
              <circle cx="17.5471" cy="17.2727" r="12.8573" stroke="black" stroke-width="2.85718" stroke-linecap="round" stroke-linejoin="round"/>
              <path d="M13.9757 21.6396V12.9057C13.9757 11.7437 15.2891 11.0678 16.2346 11.7432L22.3483 16.1102C23.146 16.6799 23.146 17.8654 22.3483 18.4351L16.2346 22.8021C15.2891 23.4775 13.9757 22.8016 13.9757 21.6396Z" stroke="black" stroke-width="2.85718" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
            <p class="hobbies__description text-medium">Gaming</p>
          </li>

          <li class="hobbies__item">
            <svg class="hobbies__svg" width="35" height="35" viewBox="0 0 35 35" fill="none" xmlns="http://www.w3.org/2000/svg">
              <circle cx="17.5471" cy="17.6935" r="12.8573" stroke="black" stroke-width="2.85718" stroke-linecap="round" stroke-linejoin="round"/>
              <path d="M18.9757 4.90491C18.4785 5.32333 18.0306 5.81712 17.6495 6.38286C15.4455 9.65469 16.3111 14.0937 19.583 16.2978C19.8412 16.4717 20.1068 16.6266 20.3779 16.7626C23.2614 18.2095 24.3623 16.2594 25.9235 17.3111C26.9362 17.9933 27.2042 19.3673 26.522 20.38C25.8071 21.4413 24.69 21.9793 24.8833 23.7176C24.9924 24.6987 25.5951 25.5442 26.3761 26.2651" stroke="black" stroke-width="2.85718" stroke-linecap="round" stroke-linejoin="round"/>
              <path d="M6.11839 13.8078C7.66396 14.1839 9.09415 15.0761 10.127 16.4448C11.228 17.9038 11.6844 19.6484 11.544 21.337C11.4696 22.2313 12.0528 23.134 12.8033 23.626C13.166 23.8637 13.4945 24.1668 13.7707 24.5328C14.9936 26.1534 14.7496 28.4237 13.2613 29.7519" stroke="black" stroke-width="2.85718" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
            <p class="hobbies__description text-medium">Travelling</p>
          </li>

          <li class="hobbies__item">
            <svg class="hobbies__svg" width="35" height="36" viewBox="0 0 35 36" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M6.11839 25.2573C6.11839 22.8904 8.0372 20.9716 10.4042 20.9716V20.9716C12.7711 20.9716 14.6899 22.8904 14.6899 25.2573V25.2573C14.6899 27.6243 12.7711 29.5431 10.4042 29.5431H6.68538C6.37224 29.5431 6.11839 29.2893 6.11839 28.9761V27.4002V25.2573V25.2573Z" stroke="black" stroke-width="2.85718" stroke-linecap="round" stroke-linejoin="round"/>
              <path d="M11.8328 20.6204L22.6755 8.57291C23.7706 7.35616 25.662 7.30642 26.8196 8.46394L27.0086 8.65297L27.1976 8.842C28.3551 9.99952 28.3054 11.891 27.0887 12.9861L15.0412 23.8288" stroke="black" stroke-width="2.85718" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
            <p class="hobbies__description text-medium">Sketching/Graffitti</p>
          </li>

          <li class="hobbies__item">
            <svg class="hobbies__svg" width="35" height="35" viewBox="0 0 35 35" fill="none" xmlns="http://www.w3.org/2000/svg">
              <rect x="6.11839" y="6.10657" width="22.8575" height="22.8575" rx="4.28577" stroke="black" stroke-width="2.85718" stroke-linecap="round"/>
              <path d="M6.11839 20.3925H13.2613" stroke="black" stroke-width="2.85718" stroke-linecap="round" stroke-linejoin="round"/>
              <path d="M21.8329 20.3925H28.9759" stroke="black" stroke-width="2.85718" stroke-linecap="round" stroke-linejoin="round"/>
              <path d="M21.5745 20.4297C21.2728 21.2586 20.7227 21.9742 19.9992 22.4789C19.2758 22.9835 18.4143 23.2527 17.5322 23.2496C16.6501 23.2465 15.7905 22.9714 15.0706 22.4617C14.3507 21.9519 13.8056 21.2325 13.5097 20.4015" stroke="black" stroke-width="2.85718" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
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
    .profile-block__wrapper {
      padding: 16px;

      .profile-info {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        margin-bottom: 16px;

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
      }

      .description {
        padding: 0 38px;
        margin-bottom: 24px;
        .description__span {
          font-family: "Outfit";
          text-align: center;
          display: block;
          line-height: 24px;
          font-size: 18px;
        }
      }

      .contacts-list {
        display: flex;
        flex-direction: column;
        gap: 24px;
        min-width: 270px;
        margin-bottom: 32px;

        .contacts-list__item {
          display: flex;
          flex-direction: row;
          gap: 16px;
          align-items: center;
        }

        .contacts-list__svg {
          min-width: 33px;
          min-height: 33px;
        }

        .contacts-list__block-contact {
          display: flex;
          flex-direction: column;
          gap: 4px;
        }

        .contacts-list__description {
        }

        .contacts-list__link {
          word-break: break-all;
        }
      }

      .socials {
        margin-bottom: 32px;

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

        .twitter {
          background: #00ACEE;
          padding: 10px;
          border-radius: 100%;
        }
        .linkedin {

          background: #0077B5;
          padding: 10px;
          border-radius: 100%;
        }

        .socials__svg {
          width: 32px;
          height: 32px;
        }


        .socials__block {
          display: flex;
          flex-direction: column;
          gap: 4px;
        }

        .socials__span {
        }

        .socials__link {
        }
      }

      .learning {
        margin-bottom: 32px;

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

        .learning__svg {
          border-radius: 6px;
        }

        .learning__block {
          display: flex;
          flex-direction: column;
          gap: 4px;
        }

        .learning__span {
        }

        .learning__description {
        }
      }

      .hobbies {

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

        .hobbies__svg {
        }

        .hobbies__description {
        }
      }
    }
  }

  @media screen and (min-width: 1024px) {
    .profile-block {
      .profile-block__wrapper {
        max-width: 380px;
        padding: 48px;

        .profile-info {
          display: block;
          margin-bottom: 32px;
          .profile-info__img {
            max-width: fit-content;
          }
        }

        .description {
          padding: 0;
          margin-bottom: 10px;
          .description__span {
            text-align: start;
          }
        }
      }
    }
  }
</style>
