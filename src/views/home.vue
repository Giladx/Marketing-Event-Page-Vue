<template>
  <div class="home-container">
    <app-navigation></app-navigation>
    <main class="home-main">
      <div class="home-hero section-container">
        <div class="home-max-width max-content-container">
          <div class="home-content-container">
            <h1 class="home-text">
              <span class="home-text01">PURE CLEAN AIR DUCT FOR</span>
              <span class="heading1"><span v-html="rawevt6"></span></span>
              <span class="home-text03 heading1">HEALTHY LIFE</span>
              <span class="heading1"><span v-html="rawsqf9"></span></span>
            </h1>
            <div class="home-btns-container">
              <button class="home-primary button-primary button-lg button">
                <span>
                  <span>CONTACT US</span>
                  <br />
                </span>
              </button>
              <button class="button button-outline button-lg-border">
                <span>
                  <span>order service</span>
                  <br />
                </span>
              </button>
            </div>
          </div>
        </div>
      </div>
      <div class="home-sponsors section-container">
        <div class="home-max-width1 max-content-container">
          <div class="home-container1">
            <img
              alt="image"
              src="/playground_assets/toprated-solid-border-1000w.png"
              class="home-image"
            />
            <img
              alt="image"
              src="/playground_assets/soap-solid-border-1000w.png"
              class="home-image1"
            />
            <img
              alt="image"
              src="/playground_assets/elite-solid-border-1000w.png"
              class="home-image2"
            />
          </div>
          <div class="home-container2"></div>
        </div>
      </div>
      <div class="home-location">
        <div class="home-container3"></div>
        <div class="home-content-container1 section-container">
          <div class="home-container4">
            <span class="home-text11">
              <span>AIR DUCT CLEANING</span>
              <br />
            </span>
            <span class="home-text14">Air duct cleaning is essential,</span>
            <div class="home-container5">
              <span class="home-text15">
                in order to take full advantage of the
              </span>
              <span class="home-text16">
                <span>cooling &amp; heating system.</span>
                <br />
              </span>
            </div>
            <div class="home-container6">
              <span class="home-text19">
                The air ducts and filters
                <span v-html="rawhegy"></span>
              </span>
              <span class="home-text20 content">
                must be kept clean. Air ducts and filters accumulate dust, odors
                and even dust mites which can trigger allergies. How can you enjoy
                a cool interior if it’s causing you to sneeze? When the air ducts
                or filters are dirty the system works inefficiently and uses extra
                electricity. After our service, you can breathe easy and enjoy the
                cool air.
              </span>
              <div class="home-btns-container1">
                <a
                  href="tel:+18885031722"
                  class="home-register button-secondary button button-md"
                >
                  <span class="home-text21">
                    <span>call now</span>
                    <br />
                  </span>
                </a>
                <button
                  class="home-learn-more button button-outline button-md-border"
                >
                  learn more
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="home-workshops">
        <div class="home-content-container2">
          <div class="home-container7">
            <h1 class="home-text24">
              <span class="home-text25">
                register for
                <span v-html="rawjcnc"></span>
              </span>
              <br class="heading2" />
              <span class="home-text27 heading2">super insightful</span>
              <span class="heading2"><span v-html="raw2znd"></span></span>
              <br class="heading2" />
              <span class="home-text30">
                workshops for
                <span v-html="rawxmds"></span>
              </span>
              <br class="heading2" />
              <span class="home-text32">your team</span>
            </h1>
            <span class="home-text33">
              get early discounts and group discounts
            </span>
            <span class="home-text34">
              Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet
              sint. Velit officia consequat duis enim velit mollit. Exercitation
              veniam consequat sunt nostrud amet.
            </span>
            <button class="button button-md button-outline home-learn-more1">
              learn more
            </button>
          </div>
        </div>
        <div class="home-container8"></div>
      </div>
      <div class="home-previous-events section-container">
        <div class="home-max-width2 max-content-container">
          <div class="home-heading-container">
            <h1 class="home-text35 heading2"><span>previous events</span></h1>
            <span class="home-text37">
              Take a tour of our previous conferences
            </span>
          </div>
        </div>
        <div data-type="slider" class="home-slider">
          <app-slide rootClassName="slide-root-class-name4"></app-slide>
          <app-slide
            heading="Slide #2"
            rootClassName="slide-root-class-name1"
          ></app-slide>
          <app-slide
            heading="Slide #3"
            rootClassName="slide-root-class-name"
          ></app-slide>
          <app-slide
            heading="Slide #4"
            rootClassName="slide-root-class-name3"
          ></app-slide>
          <app-slide
            heading="Slide #5"
            rootClassName="slide-root-class-name2"
          ></app-slide>
        </div>
        <div class="home-slider-controls">
          <div data-action="previousSlide" class="home-go-left">
            <svg viewBox="0 0 1024 1024" class="home-icon">
              <path d="M250 176l92-90 426 426-426 426-92-90 338-336z"></path>
            </svg>
          </div>
          <div data-action="nextSlide" class="home-go-right">
            <svg viewBox="0 0 1024 1024" class="home-icon2">
              <path d="M250 176l92-90 426 426-426 426-92-90 338-336z"></path>
            </svg>
          </div>
        </div>
      </div>
    </main>
    <app-footer rootClassName="footer-root-class-name"></app-footer>
  </div>
</template>

<script>
import AppNavigation from '../components/navigation'
import AppSlide from '../components/slide'
import AppFooter from '../components/footer'

export default {
  name: 'Home',
  components: {
    AppNavigation,
    AppSlide,
    AppFooter,
  },

  data() {
    return {
      rawevt6: ' ',
      rawsqf9: ' ',
      rawhegy: ' ',
      rawjcnc: ' ',
      raw2znd: ' ',
      rawxmds: ' ',
    }
  },

  metaInfo: {
    title: 'Marketing Event Page',
    meta: [
      {
        property: 'og:title',
        content: 'Marketing Event Page',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  display: flex;
  position: relative;
  min-height: 100vh;
  overflow-x: hidden;
  align-items: center;
  flex-direction: column;
}
.home-main {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-hero {
  height: 886px;
  position: relative;
  padding-top: 128px;
  background-size: cover;
  background-image: url("/playground_assets/bg2.svg");
}
.home-max-width {
  z-index: 1;
  align-items: stretch;
}
.home-content-container {
  flex: 1;
  display: flex;
  max-width: 45%;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.home-text {
  font-size: 64px;
  font-style: normal;
  font-family: IBM Plex Sans Condensed;
  font-weight: 700;
  line-height: 1.1;
  margin-bottom: var(--dl-space-space-fiveunits);
  text-transform: uppercase;
  text-decoration: none;
}
.home-text01 {
  color: var(--dl-color-scheme-black);
}
.home-text03 {
  color: var(--dl-color-scheme-pink);
  font-size: 64px;
  font-style: normal;
  font-family: IBM Plex Sans Condensed;
  font-weight: 700;
  line-height: 1.1;
  text-transform: uppercase;
  text-decoration: none;
}
.home-btns-container {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
}
.home-primary {
  margin-right: var(--dl-space-space-oneandhalfunits);
}
.home-sponsors {
  flex: 0 0 auto;
  display: flex;
  padding-top: var(--dl-space-space-threeunits);
  border-color: rgba(144, 149, 167, 0.1);
  border-width: 0px;
  flex-direction: column;
  padding-bottom: var(--dl-space-space-threeunits);
  border-bottom-width: 1px;
}
.home-max-width1 {
  flex-direction: column;
}
.home-container1 {
  flex: 0 0 auto;
  width: 80%;
  display: flex;
  flex-wrap: wrap;
  align-items: flex-start;
  flex-direction: row;
  justify-content: space-between;
}
.home-image {
  object-fit: cover;
}
.home-image1 {
  object-fit: cover;
}
.home-image2 {
  object-fit: cover;
}
.home-container2 {
  flex: 0 0 auto;
  width: 100%;
  border: 2px dashed rgba(120, 120, 120, 0.4);
  height: 100px;
  display: none;
  align-items: flex-start;
}
.home-location {
  width: 100%;
  display: flex;
  align-items: stretch;
  flex-direction: row;
}
.home-container3 {
  flex: 0 0 auto;
  width: 50%;
  border: 2px dashed rgba(120, 120, 120, 0.4);
  height: auto;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-content-container1 {
  flex: 1;
  display: flex;
  align-items: stretch;
  padding-top: 100px;
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: row;
}
.home-container4 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-text11 {
  color: var(--dl-color-scheme-white);
  font-size: 56px;
  font-style: normal;
  font-weight: 600;
  line-height: 1.1;
  margin-left: -100px;
  padding-top: 4px;
  padding-left: 18px;
  margin-bottom: 6px;
  padding-right: 11px;
  padding-bottom: 6px;
  background-color: var(--dl-color-scheme-lightblue);
}
.home-text14 {
  color: rgb(0, 0, 0);
  font-size: 56px;
  font-style: normal;
  font-weight: 300;
  line-height: 1.1;
}
.home-container5 {
  display: flex;
  align-items: flex-end;
  margin-bottom: var(--dl-space-space-twounits);
  flex-direction: column;
}
.home-text15 {
  color: var(--dl-color-scheme-pink);
  font-size: 56px;
  font-style: normal;
  font-weight: 600;
  line-height: 1.1;
  margin-left: var(--dl-space-space-fiveunits);
}
.home-text16 {
  color: var(--dl-color-scheme-pink);
  font-size: 56px;
  align-self: center;
  font-style: normal;
  font-weight: 600;
  line-height: 1.1;
  margin-left: -36px;
}
.home-container6 {
  flex: 1;
  width: 100%;
  display: flex;
  max-width: 350px;
  align-items: flex-start;
  margin-left: 124px;
  flex-direction: column;
}
.home-text19 {
  color: rgb(0, 0, 0);
  font-size: 18px;
  font-style: normal;
  font-weight: 600;
  margin-bottom: var(--dl-space-space-halfunit);
}
.home-text20 {
  color: rgb(0, 0, 0);
  margin-bottom: var(--dl-space-space-twounits);
}
.home-btns-container1 {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
}
.home-register {
  text-decoration: none;
}
.home-learn-more {
  color: #000000;
  transition: 0.3s;
  border-color: #000000;
}
.home-learn-more:hover {
  border-color: var(--dl-color-scheme-pink);
}
.home-workshops {
  flex: 1;
  width: 100%;
  display: flex;
  flex-direction: row;
}
.home-content-container2 {
  flex: 1;
  display: flex;
  align-items: flex-end;
  flex-direction: column;
  justify-content: center;
  background-color: rgba(144, 149, 167, 0.08);
}
.home-container7 {
  flex: 0 0 auto;
  display: flex;
  max-width: 366px;
  align-items: flex-start;
  margin-right: 107px;
  flex-direction: column;
}
.home-text24 {
  margin-bottom: 42px;
}
.home-text27 {
  color: var(--dl-color-scheme-pink);
}
.home-text33 {
  font-size: 18px;
  font-style: normal;
  font-weight: 600;
  margin-bottom: var(--dl-space-space-halfunit);
}
.home-text34 {
  margin-bottom: var(--dl-space-space-threeunits);
  text-transform: none;
}
.home-container8 {
  flex: 0 0 auto;
  width: 50%;
  border: 2px dashed rgba(120, 120, 120, 0.4);
  height: auto;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-previous-events {
  display: flex;
  position: relative;
  flex-direction: column;
  padding-bottom: 150px;
}
.home-max-width2 {
  flex-direction: column;
}
.home-heading-container {
  flex: 0 0 auto;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-fourunits);
  flex-direction: column;
}
.home-text35 {
  text-align: center;
}
.home-text37 {
  color: var(--dl-color-scheme-lightblue);
  font-style: normal;
  text-align: center;
  font-weight: 500;
}
.home-slider {
  flex: 0 0 auto;
  width: 100%;
  height: 420px;
  display: flex;
  position: relative;
  transition: 0.5s;
  align-items: stretch;
  flex-direction: row;
  justify-content: center;
}
.home-slider-controls {
  top: calc(50% + 24px);
  width: calc(60% + 48px);
  height: 48px;
  display: flex;
  position: absolute;
  align-self: center;
  justify-content: space-between;
}
.home-go-left {
  flex: 0 0 auto;
  width: 48px;
  cursor: pointer;
  height: 48px;
  display: flex;
  z-index: 1;
  transition: 0.3s;
  align-items: center;
  border-color: rgba(144, 149, 167, 0.24);
  border-width: 1px;
  border-radius: var(--dl-radius-radius-round);
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-scheme-white);
}
.home-go-left:hover {
  border-color: var(--dl-color-scheme-lightblue);
  background-color: var(--dl-color-scheme-white80);
}
.home-icon {
  width: 24px;
  height: 24px;
  transform: rotate(180deg);
}
.home-go-right {
  flex: 0 0 auto;
  width: 48px;
  cursor: pointer;
  height: 48px;
  display: flex;
  z-index: 1;
  transition: 0.3s;
  align-items: center;
  border-color: rgba(144, 149, 167, 0.24);
  border-width: 1px;
  border-radius: var(--dl-radius-radius-round);
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-scheme-white);
}
.home-go-right:hover {
  border-color: var(--dl-color-scheme-lightblue);
  background-color: var(--dl-color-scheme-white80);
}
.home-icon2 {
  width: 24px;
  height: 24px;
}
@media(max-width: 1600px) {
  .home-text15 {
    align-self: flex-end;
    margin-left: 0px;
  }
}
@media(max-width: 1200px) {
  .home-text {
    font-size: 64px;
    font-style: normal;
    font-family: IBM Plex Sans Condensed;
    font-weight: 700;
    line-height: 1.1;
    text-transform: uppercase;
    text-decoration: none;
  }
  .home-text14 {
    color: var(--dl-color-scheme-black);
  }
  .home-text16 {
    color: var(--dl-color-scheme-black);
    align-self: flex-end;
    font-style: normal;
    font-weight: 300;
    margin-left: 0px;
  }
  .home-text19 {
    color: var(--dl-color-scheme-black);
  }
  .home-text20 {
    color: var(--dl-color-scheme-black);
  }
  .home-text21 {
    color: var(--dl-color-scheme-black);
  }
  .home-text24 {
    font-size: 42px;
    font-family: IBM Plex Sans Condensed;
    font-weight: 700;
    line-height: 1.1;
    text-transform: uppercase;
    text-decoration: none;
  }
  .home-text25 {
    color: var(--dl-color-scheme-black);
  }
  .home-text30 {
    color: var(--dl-color-scheme-black);
  }
  .home-text32 {
    color: var(--dl-color-scheme-black);
  }
  .home-text33 {
    color: var(--dl-color-scheme-black);
    font-size: 18px;
    font-style: normal;
    font-weight: 600;
  }
  .home-text34 {
    color: var(--dl-color-scheme-black);
  }
  .home-learn-more1 {
    color: var(--dl-color-scheme-black);
    border-color: var(--dl-color-scheme-black);
  }
  .home-text35 {
    color: var(--dl-color-scheme-black);
  }
}
@media(max-width: 991px) {
  .home-max-width {
    flex-direction: column;
  }
  .home-content-container {
    max-width: 100%;
    margin-bottom: 42px;
  }
  .home-container2 {
    display: flex;
  }
  .home-location {
    flex-direction: column;
  }
  .home-content-container1 {
    padding-top: 0px;
    padding-left: var(--dl-space-space-threeunits);
  }
  .home-container4 {
    margin-top: -100px;
    align-items: center;
  }
  .home-container6 {
    max-width: 100%;
    margin-left: 0px;
  }
  .home-container7 {
    margin-right: var(--dl-space-space-unit);
  }
  .home-slider-controls {
    width: calc(75% + 48px);
  }
}
@media(max-width: 767px) {
  .home-text {
    font-size: 48px;
  }
  .home-content-container1 {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-text11 {
    margin-left: -24px;
  }
  .home-btns-container1 {
    width: 100%;
    align-items: stretch;
    flex-direction: column;
  }
  .home-workshops {
    flex-direction: column-reverse;
    padding-bottom: var(--dl-space-space-twounits);
  }
  .home-container7 {
    max-width: 100%;
    padding-top: var(--dl-space-space-twounits);
    margin-right: 0px;
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .home-previous-events {
    padding-bottom: var(--dl-space-space-sixunits);
  }
  .home-slider-controls {
    width: calc(80% + 48px);
  }
}
@media(max-width: 479px) {
  .home-max-width1 {
    position: relative;
  }
  .home-container1 {
    justify-content: center;
  }
}
</style>
