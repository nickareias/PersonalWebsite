<template>
  <div class="landing-page__container">
    <div class="landing-page__header-section">
      <div class="landing-page__header-section__title-container">
        Fullstack Developer<br>&amp; Designer &nbsp;
      </div>
      <div class="landing-page__header-section__name-container">
        Nick<br>
        Areias
      </div>
      <div class="landing-page__header-section__down-arrow">
        <div @click="scrollDown">
          <i class="fal fa-chevron-down down-arrow--animation" style="font-size: 2.5em; width: 60px; cursor: pointer;"></i>
        </div>
      </div>
    </div>
    <div class="landing-page__client-section">
      <div class="landing-page__section__floating-title--container">
        <div class="landing-page__section__floating-title" id="clients-tag">
          Clients
        </div>
      </div>
      <div class="landing-page__section">
        <div class="landing-page__demo-container">
          <div class="landing-page__demo-container__left-box">
            <div class="left-box__content-container">
              <h1>wrkprty <img class="wrkprty-logo" src="https://res.cloudinary.com/dgr55ydgq/image/upload/v1533852674/personal-site/WrkprtyLogoDarker.svg"></h1>
              <p>Pop up co-working<br>marketplace and community</p>
              <table class="tech-list-table">
                <tr>
                  <td>Vue.js</td>
                  <td class="image-cell"><img class="vue-logo" src="https://res.cloudinary.com/dgr55ydgq/image/upload/v1533853711/personal-site/Vue.js_Logo.svg"></td>
                </tr>
                <tr>
                  <td>Django</td>
                  <td class="image-cell"><img class="django-logo" src="https://res.cloudinary.com/dgr55ydgq/image/upload/v1533853495/personal-site/django-logo-negative.svg"></td>
                </tr>
              </table>
              <div class="visit-button">
                <a href="https://wrkprty.com" target="_blank" style="color: #5D7AEA">wrkprty.com</a>
              </div>
            </div>
          </div>
          <div class="landing-page__demo-container__right-box">
            <!-- <div class="background-stripe-1">
            </div> -->
            <div class="phone-container">
              <img class="wrkprty-phone" src="https://res.cloudinary.com/dgr55ydgq/image/upload/v1533854945/personal-site/WrkprtyPhoneSmall.svg">
              <img class="phone-shadow" src="https://res.cloudinary.com/dgr55ydgq/image/upload/v1533953405/DropShadow.svg">
              <!-- <div class="phone-shadow"></div> -->
            </div>
          </div>
        </div>
      </div>
      <div class="landing-page__section section--dark landing-page__section--psychometric">
        <div class="landing-page__demo-container">
          <div class="landing-page__demo-container__left-box" style="padding-left: 0px;">
            <div class="left-box__content-container psychometric-container">
              <h1 style="margin-left: -3px;">Psychometric</h1>
              <p>SaaS solution to screen employees during hiring process</p>
              <table class="tech-list-table">
                <tr>
                  <td>Vue.js</td>
                  <td class="image-cell"><img class="vue-logo" src="https://res.cloudinary.com/dgr55ydgq/image/upload/v1533853711/personal-site/Vue.js_Logo.svg"></td>
                </tr>
                <tr>
                  <td>Nuxt.js</td>
                  <td class="image-cell"><img class="nuxt-logo" src="https://res.cloudinary.com/dgr55ydgq/image/upload/v1533853522/personal-site/nuxt-seeklogo.com.svg"></td>
                </tr>
                <tr>
                  <td>Firebase</td>
                  <td class="image-cell"><img class="firebase-logo" src="https://res.cloudinary.com/dgr55ydgq/image/upload/v1533853516/personal-site/firebase-logo-logomark.svg"></td>
                </tr>
              </table>
              <div class="visit-button">
                <a href="https://gopsychometric.com" target="_blank" style="color: #5D7AEA">gopsychometric.com</a>
              </div>
            </div>
          </div>
          <div class="landing-page__demo-container__right-box">
            <div class="phone-container">
              <img class="psych-phone" src="https://res.cloudinary.com/dgr55ydgq/image/upload/v1533951890/personal-site/PsychPhoneSmall.svg">
              <img class="phone-shadow--psych" src="https://res.cloudinary.com/dgr55ydgq/image/upload/v1533953405/DropShadow.svg">
              <!-- <div class="phone-shadow phone-shadow--dark"></div> -->
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="landing-page__skills-list-section">
      <!-- <div class="landing-page__section__floating-title--container">
        <div class="landing-page__section__floating-title">
          Personal Projects
        </div>
      </div> -->
      <div class="angled-background-1">
      </div>
      <!-- <div class="angled-background-2">
      </div> -->
      <div class="angled-background-3">
      </div>
      <!-- <div class="angled-background-4">
      </div> -->
      <div class="angled-background-5">
      </div>
      <div class="angled-background-6">
      </div>
      <div class="angled-background-7">
      </div>
      <div class="skills-list-container">
        <div class="skills-list-header">
          Modern web development
        </div>
        <div class="skills-list-item">
          <i class="fal fa-tachometer skills-list-item__icon"></i>
          <h2>Single Page Applications</h2>
          <p>Modern responsive web apps that load quickly and keep users engaged</p>
        </div>
        <div class="skills-list-item">
          <i class="fal fa-search skills-list-item__icon"></i>
          <h2>End-to-End Testing</h2>
          <p>Stable web sites that work consistently amidst constant change</p>
        </div>
        <div class="skills-list-item">
          <i class="fal fa-sync skills-list-item__icon"></i>
          <h2>Progressive Web Apps</h2>
          <p>Web apps that can send push notifications and work while the user is offline</p>
        </div>
        <div class="skills-list-item">
          <i class="fal fa-globe skills-list-item__icon"></i>
          <h2>SEO Optimized</h2>
          <p>Pages built to load content quickly for web crawlers</p>
        </div>
        <div class="skills-list-item">
          <i class="fal fa-database skills-list-item__icon"></i>
          <h2>Reactive Databases</h2>
          <p>Data that updates and reacts in real time without reloading the page</p>
        </div>
        <div class="skills-list-item">
          <i class="fal fa-users skills-list-item__icon"></i>
          <h2>UI / UX Focused</h2>
          <p>Snappy easy to understand user interfaces that lead to engaging user experiences</p>
        </div>
      </div>
      <div class="landing-page__section--final">
        <div class="final-section-container">
          <div class="final-section__portrait-container">
            <div class="final-section__portrait">
            </div>
            <div class="final-section__social-icons">
              <a href="https://www.linkedin.com/in/nick-areias-639959b4/" target="_blank">
                <i class="fab fa-linkedin linkedin-icon"></i>
              </a>
              <a href="https://twitter.com/nickareias/" target="_blank">
                <i class="fab fa-twitter-square twitter-icon"></i>
              </a>
            </div>
          </div>
          <div class="final-section__text-container">
            <p>I've been a fullstack developer for a year and a half, using Vue.js and various backend frameworks. I specialize in web apps with lots of user interactivity.</p>
            <p>I have experience building projects from the ground up from inception to production. And I've joined existing teams, learning their workflow and project structure.</p>
            <p>I am highly focused on asthetics, with a keen eye for details. I can accurately implement existing designs and frontend functionality, and I'm confident designing my own web pages and user interfaces.</p>
            <p class="final-section__email">nicholasareias@gmail.com</p>
          </div>
        </div>
      </div>
    </div>
    <!-- <div class="landing-page__section section--dark">
    </div> -->
    <!-- <div class="landing-page__section landing-page__section--final">
    </div> -->
  </div>
</template>

<script>
export default {
  data () {
    return {
    }
  },
  mounted () {
  },
  computed: {
    isMobile () {
      return this.$vuetify.breakpoint.xs
    }
  },
  methods: {
    scrollDown () {
      var el = document.getElementById('clients-tag')
      el.scrollIntoView({
        behavior: 'smooth',
        block: 'start'
      })
    }
  }
}
</script>

<style lang="scss">
.landing-page__container {
  min-heght: 100vh;
  min-width: 100vw;
  max-width: 100vw;
  background-color: #EEE;
  overflow: hidden;
  overflow-y: scroll;
  position: relative;
}
.landing-page__header-section {
  height: 100vh;
  width: 100%;
  min-height: 400px;
  background: url('https://res.cloudinary.com/dgr55ydgq/image/upload/v1533845063/personal-site/annie-spratt-210713-unsplash.jpg');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: left 50% top 10%;
  position: relative;
  -ms-interpolation-mode: bicubic;

  color: #DDD;
  font-family: 'Libre Baskerville', serif;
}
.landing-page__header-section__name-container {
  position: absolute;
  bottom: 60px;
  left: 90px;
  font-size: 5.5em;
  line-height: 1.0em;
}
.landing-page__header-section__title-container {
  position: absolute;
  top: 70px;
  right: 130px;
  font-size: 2.3em;
  line-height: 1.0em;
}
.landing-page__header-section__down-arrow {
  position: absolute;
  bottom: 0;
  width: 100%;
  text-align: center;
}
.down-arrow--animation {
  animation: arrow-bounce 1s alternate ease-out infinite;
  -webkit-animation: arrow-bounce 1s alternate ease-out infinite;
  position: relative;
}
@-webkit-keyframes arrow-bounce {
  from {bottom: 16px;}
  to {bottom: 23px;}
}

@keyframes arrow-bounce {
  from {bottom: 16px;}
  to {bottom: 23px;}
}

@media screen and (max-width: 600px) {
  @-webkit-keyframes arrow-bounce {
    from {bottom: 24px;}
    to {bottom: 32px;}
  }

  @keyframes arrow-bounce {
    from {bottom: 24px;}
    to {bottom: 32px;}
  }
  .landing-page__header-section__title-container {
    top: 50px;
    left: 0;
    width: 100%;
    display: flex;
    justify-content: center;
    text-align: center;
    font-size: 1.5em;
  }
  .landing-page__header-section__name-container {
    position: absolute;
    bottom: 80px;
    left: 0;
    width: 100%;
    text-align: center;
    padding-top: 30px;
    font-size: 4.0em;
  }
}
.landing-page__client-section {
  z-index: 10;
  position: relative;
  width: 100%;
}
.landing-page__section__floating-title--container {
  width: 100%;
  display: flex;
  justify-content: center;
  // position: sticky;
  top: 0;
  height: 0;
}
.landing-page__section__floating-title {
  height: 35px;
  width: 200px;
  color: #666;
  background-color: #FAFAFA;
  border-left: 2px solid rgba(0,0,0,0.3);
  border-right: 2px solid rgba(0,0,0,0.3);
  border-bottom: 2px solid rgba(0,0,0,0.3);
  box-shadow: 0 1px 1px 1px rgba(0,0,0,0.15);
  border-bottom-left-radius: 10px;
  border-bottom-right-radius: 10px;
  font-family: 'Montserrat', sans-serif;
  font-size: 1.15em;
  display: flex;
  justify-content: center;
  align-items: center;
}
.landing-page__section {
  background-color: #EEE;
  padding: 150px 0;
  // width: 100%;
}
.section--dark {
  // background-color: #324252;
  // background-color: #28373E;
  background-color: #172830;
}
.landing-page__demo-container {
  height: 100%;
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  padding: 0 50px;
  position: relative;
}

.landing-page__demo-container__left-box {
  flex-grow: 2;
  display: flex;
  justify-content: center;
  // padding-left: 20px;
}
.left-box__content-container {
  width: 500px;
  font-family: 'Montserrat', sans-serif;
  h1 {
    display: flex;
    align-items: center;
    font-weight: 400;
    font-size: 4.2em;
    color: #333;
  }
  p {
    margin-top: 10px;
    font-size: 1.5em;
    line-height: 1.1em;
    font-weight: 200;
    color: #666;
  }
}
.left-box__content-container.psychometric-container {
  width: 500px;
}
.landing-page__section--psychometric {
  box-shadow: 0 0px 7px 2px rgba(0,0,0,0.6);
  .left-box__content-container {
    h1 {
      color: #CCC;
    }
    p {
      color: #DDD;
    }
  }
  .tech-list-table {
    width: 359px;
    td {
      font-family: 'Montserrat', sans-serif;
      font-size: 1.5em;
      line-height: 1.1em;
      font-weight: 200;
      color: #DDD;
    }
  }
}

.landing-page__demo-container__right-box {
  flex-grow: 2;
  display: flex;
  justify-content: center;
  padding-top: 30px;
  // padding-right: 7%;
  position: relative;
  z-index: 10;
}

.wrkprty-phone {
  height: 400px;
}

.psych-phone {
  height: 450px;
}

.tech-list-table {
  width: 359px;
  td {
    font-family: 'Montserrat', sans-serif;
    font-size: 1.5em;
    line-height: 1.1em;
    font-weight: 200;
    color: #666;
    padding-top: 12px;
    padding-bottom: 12px;
  }
  .image-cell {
    text-align: center;
    width: 80px;
  }
}
.landing-page__demo-container__list-item {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 50%;
}
.wrkprty-logo {
  margin-left: 10px;
  height: 80px;
  width: 80px;
}
.vue-logo {
  height: 40px;
}
.django-logo {
  height: 30px;
}
.nuxt-logo {
  height: 35px;
}
.firebase-logo {
  height: 55px;
}

@media screen and (max-width: 900px) {
  .left-box__content-container {
    width: 350px;
  }
  .landing-page__demo-container__right-box {
    width: 500px;
  }
  .landing-page__section {
    padding: 20px;
  }
  .landing-page__section--psychometric {
    .landing-page__demo-container__left-box {
      font-size: 0.9em;
      margin-top: 60px;
      h1 {
        font-size: 3.0em;
      }
      p {
        margin-top: 5px;
        margin-bottom: 15px;
      }
      td {
        padding-top: 5px;
        padding-bottom: 5px;
      }
    }
    .left-box__content-container {
    }
    .tech-list-table {
      width: 100%;
    }
    .landing-page__demo-container__right-box {
      width: 500px;
      margin-top: 30px;
      margin-bottom: 40px;
      padding: 0;
    }
  }
}

@media screen and (max-width: 750px) {
  .landing-page__demo-container {
    padding: 0 20px;
  }
  .landing-page__demo-container__left-box {
    margin-top: 60px;
    width: 280px;
    font-size: 0.8em;
    padding-left: 10px;
    p {
      margin-top: 5px;
      margin-bottom: 15px;
    }
    td {
      padding-top: 5px;
      padding-bottom: 5px;
    }
  }
  .left-box__content-container {
    width: 280px;
  }
  .landing-page__demo-container__right-box {
    margin-top: 30px;
    margin-bottom: 30px;
    padding: 0;
  }
  .landing-page__section {
    padding: 0;
    // width: 100%;
  }
  .tech-list-table {
    width: 100%;
  }
  .landing-page__section--psychometric {
    .landing-page__demo-container__left-box {
      margin-top: 60px;
      width: 300px;
      p {
        margin-top: 5px;
        margin-bottom: 15px;
      }
      td {
        padding-top: 5px;
        padding-bottom: 5px;
      }
    }
    .left-box__content-container {
      width: 300px;
    }
    .tech-list-table {
      width: 100%;
    }
    .landing-page__demo-container__right-box {
      margin-top: 30px;
      margin-bottom: 40px;
      padding: 0;
    }
  }
}

@media screen and (max-width: 500px) {
  .psychometric-container {
    font-size: 0.8em;
  }
  .landing-page__section--psychometric {
    .left-box__content-container {
      width: 280px;
    }
    .tech-list-table {
      width: 103%;
    }
  }
}
.phone-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  position: relative;
  z-index: 10;
}
.phone-shadow {
  margin-top: -15px;
  width: 250px;
  height: 100px;
}
.phone-shadow--psych {
  margin-top: -10px;
  width: 280px;
  height: 100px;
}

.landing-page__skills-list-section {
  position: relative;
  overflow: hidden;
}
.skills-list-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  background-color: #FFF;
  box-shadow: 0 2px 7px 1px rgba(0,0,0,0.2);
  border-radius: 5px;
  align-items: center;
  margin: 60px;
  margin-bottom: 5px;
  position: relative;
  z-index: 10;
}
.skills-list-header {
  width: 100%;
  font-size: 4.0em;
  color: #666;
  text-align: center;
  font-family: 'Montserrat', sans-serif;
  margin: 50px 10px 25px 10px;
}
.skills-list-item {
  height: 220px;
  width: 300px;
  margin: 30px 40px;
  // background-color: #FFF;
  // box-shadow: 0 0 10px 3px #AAA;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
  padding: 10px;
  h2 {
    text-align: center;
    color: #333;
    font-size: 1.15em;
    font-family: 'Montserrat', sans-serif;
    margin: 10px 0 3px 0;
  }
  p {
    text-align: center;
    color: #555;
    font-size: 0.95em;
    width: 300px;
    font-family: 'Montserrat', sans-serif;
  }
}
.skills-list-item__icon {
  margin: 10px 0;
  font-size: 5.0em;
  color: #444;
}

@media screen and (max-width: 930px) {
  .skills-list-header {
    font-size: 3.5em;
  }
  .skills-list-container {
    margin: 30px;
    margin-bottom: 5px;
  }
  .skills-list-item {
    height: 250px;
    width: 250px;
    margin: 20px;
    font-size: 0.9em;
    p {
      width: 250px;
    }
  }
}
@media screen and (max-width: 700px) {
  .skills-list-header {
    font-size: 3.0em;
  }
  .skills-list-container {
    margin: 20px 10px;
    margin-bottom: 5px;
  }
  .skills-list-item {
    height: 250px;
    width: 150px;
    margin: 10px;
    p {
      width: 150px;
    }
  }
}
@media screen and (max-width: 400px) {
  .skills-list-header {
    font-size: 2.7em;
  }
}

.landing-page__section--final {
  // min-height: 100vh;
  // min-height: 480px;
  position: relative;
  padding: 60px;
}
.final-section-container {
  min-height: calc(100vh - 120px);
  // min-height: calc(480px - 120px);
  width: 100%;
  background-color: #FFF;
  box-shadow: 0 2px 7px 1px rgba(0,0,0,0.2);
  border-radius: 5px;
  position: relative;
  z-index: 10;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
}

@media screen and (min-width: 1800px) {
  .final-section-container {
    min-height: 550px;
  }
}

.final-section__text-container {
  margin: 20px 50px 20px 50px;
  width: 50%;
  p {
    font-size: 1.5em;
    color: #555;
    font-family: 'Cabin', sans-serif;
  }
  .final-section__email {
    font-family: 'Montserrat', sans-serif;
    margin-top: 40px;
    font-size: 1.3em;
  }
}
.final-section__portrait-container {
  margin: 50px 50px 20px 50px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  p {
    color: #555;
    font-size: 1.3em;
    font-family: 'Cabin', sans-serif;
  }
}
.final-section__portrait {
  height: 300px;
  width: 300px;
  border-radius: 100%;
  box-shadow: 0px 3px 10px 2px rgba(0,0,0,0.5);
  background: url('https://res.cloudinary.com/dgr55ydgq/image/upload/v1534277680/personal-site/DSC_6578_2.jpg');
  background-size: cover;
}
.final-section__social-icons {
  margin: 20px 0 8px 0;
}
.linkedin-icon {
  color: #0077B5!important;
  font-size: 3.0em;
  margin: 5px;
  cursor: pointer;
}
.twitter-icon {
  color: #1DA1F2!important;
  font-size: 3.0em;
  margin: 5px;
  cursor: pointer;
}

@media screen and (max-width: 930px) {
  .landing-page__section--final {
    padding: 30px;
  }
  .final-section-container {
    min-height: calc(100vh - 60px);
  }
  .final-section__text-container {
    margin: 20px;
    width: 70%;
    p {
      font-size: 1.5em;
    }
  }
}
@media screen and (max-width: 700px) {
  .landing-page__section--final {
    padding: 20px 10px;
  }
  .final-section-container {
    min-height: calc(100vh - 40px);
  }
  .final-section__text-container {
    margin: 20px;
    width: 80%;
    p {
      font-size: 1.3em;
    }
    .final-section__email {
      font-size: 1.2em;
    }
  }
}
@media screen and (max-width: 400px) {
  .final-section__portrait {
    height: 250px;
    width: 250px;
  }
}

.angled-background-1 {
  background-color: #DD885E;
  height: 800px;
  width: 200vw;
  position: absolute;
  right: 0;
  z-index: 4;
  -moz-transform: translateX(calc(450px + 50vw)) translateY(-500px) rotate(45deg);
  -o-transform: translateX(calc(450px + 50vw)) translateY(-500px) rotate(45deg);
  -webkit-transform: translateX(calc(450px + 50vw)) translateY(-500px) rotate(45deg);
  transform: translateX(calc(450px + 50vw)) translateY(-500px) rotate(45deg);
}
.angled-background-2 {
  // background-color: #EF4564;
  background-color: #6E826F;
  height: 4000px;
  width: 600vw;
  position: absolute;
  right: 0;
  z-index: 2;
  transform: translateX(calc(1000px + 200vw)) translateY(calc(150px)) rotate(-15deg);
}
@media screen and (max-width: 600px) {
  .angled-background-2 {
    transform: translateX(calc(1000px + 200vw)) translateY(calc(-50px)) rotate(-15deg);   
  }
}
.angled-background-3 {
  // background-color: #D41D49;
  background-color: #F04965;
  height: 800px;
  width: 200vw;
  position: absolute;
  right: 0;
  z-index: 1;
  transform: translateX(calc(390px + 50vw)) translateY(-500px) rotate(45deg);
}
.angled-background-4 {
  background-color: #091E28;
  height: 3000px;
  width: 400vw;
  position: absolute;
  right: 0;
  z-index: 0;
  transform: translateX(calc(390px + 100vw)) translateY(700px) rotate(-20deg);
}
.angled-background-5 {
  background-color: #DD885E;
  height: 600px;
  width: 400vw;
  position: absolute;
  right: 0;
  z-index: 4;
  transform: translateX(calc(100px + 100vw)) translateY(1200px) rotate(45deg);
}
.angled-background-6 {
  background-color: #EF4564;
  height: 630px;
  width: 400vw;
  position: absolute;
  right: 0;
  z-index: 3;
  transform: translateX(calc(115px + 100vw)) translateY(1200px) rotate(45deg);
}
.angled-background-7 {
  background-color: #5D7AEA;
  height: 640px;
  width: 400vw;
  position: absolute;
  right: 0;
  z-index: 2;
  transform: translateX(calc(120px + 100vw)) translateY(1200px) rotate(45deg);
}
.background-stripe-1 {
  background-color: #DD885E;
  height: 170px;
  width: 100px;
  position: absolute;
  right: 10%;
  bottom: 230px;
  z-index: 0;
}
.visit-button {
  text-decoration: underline;
  text-transform: none!important;
  color: #5D7AEA!important;
  margin: 15px 3px;
  font-size: 1.2em;
  font-family: 'Montserrat', sans-serif;
}
@media screen and (min-width: 1500px) {
  .skills-list-item {
    font-size: 1.05em;
  }
}
@media screen and (min-width: 2000px) {
  .landing-page__container {
    font-size: 1.15em;
  }
  .skills-list-item {
    height: 260px;
  }
}

@media all and (-ms-high-contrast: none), (-ms-high-contrast: active) {
  .angled-background-1 {
    display: none;
  }
  .angled-background-2 {
    display: none;
  }
  .angled-background-3 {
    display: none;
  }
  .angled-background-4 {
    display: none;
  }
  .angled-background-5 {
    display: none;
  }
  .angled-background-6 {
    display: none;
  }
  .angled-background-7 {
    display: none;
  }
  .final-section-container {
    min-height: 0;
  }
  .landing-page__demo-container {
    display: flex;
    justify-content: center;
    width: 100vw;
    padding: 0;
    margin: 0;
  }
  .landing-page__demo-container__left-box {
    width: 350px;
    display: block;
    flex-grow: 0;
  }
  .left-box__content-container {
    width: 350;
  }
  .landing-page__demo-container__right-box {
    width: 300px;
    display: block;
    flex-grow: 0;
    padding-left: 100px;
    padding-top: 120px;
  }
  .landing-page__section--psychometric {
    .landing-page__demo-container__right-box {
      width: 500px;
    } 
  }
  .landing-page__section {
    padding: 50px 0;
  }
}
@media screen and (max-width: 900px) and (-ms-high-contrast: none), (-ms-high-contrast: active) {
  .landing-page__demo-container__right-box {
    width: 700px;
    padding-left: 0;
    padding-top: 20px;
  }
  .landing-page__section--psychometric {
    .landing-page__demo-container__left-box {
      width: 500px;
    }
  }
  .landing-page__demo-container__left-box {
    width: 350px;
  }
  .landing-page__section {
    padding: 25px 0;
  }
}
@media screen and (max-width: 750px) and (-ms-high-contrast: none), (-ms-high-contrast: active) {
  .landing-page__demo-container__left-box {
    width: 300px;
  }
  .landing-page__section--psychometric {
    .landing-page__demo-container__left-box {
      width: 300px;
    }
  }
  .landing-page__section {
    padding: 10px 0;
  }
}
</style>