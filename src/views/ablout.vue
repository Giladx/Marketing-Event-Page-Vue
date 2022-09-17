<template>
  <div class="ablout-container">
    <app-navigation></app-navigation>
    <main class="ablout-main">
      <div class="ablout-hero section-container">
        <div class="ablout-container1">
          <span class="ablout-text heading1">about</span>
        </div>
      </div>
      <div class="ablout-location">
        <div class="ablout-container2"></div>
        <div class="ablout-content-container section-container">
          <div class="ablout-container3">
            <span class="ablout-text01">berlin, germany</span>
            <span class="ablout-text02">7-8 MARCH 2023</span>
            <div class="ablout-container4">
              <span class="ablout-text03"><span>— mob-x</span></span>
              <span class="ablout-text05"><span>conference</span></span>
              <span class="ablout-text07"><span>center</span></span>
            </div>
            <div class="ablout-container5">
              <span class="ablout-text09">beautiful, vibrant berlin</span>
              <span class="ablout-text10">
                <span>
                  Amet minim mollit non deserunt ullamco est sit aliqua dolor do
                  amet sint. Velit officia consequat duis enim velit mollit.
                  Exercitation veniam consequat sunt nostrud amet.
                </span>
                <br />
                <span></span>
                <br />
                <span>
                  Lorem Ipsum, Velit officia consequat duis enim velit mollit.
                  Exercitation veniam consequat sunt nostrud amet.
                </span>
              </span>
              <div class="ablout-btns-container">
                <button class="button-secondary button button-md">
                  register
                </button>
                <button
                  class="ablout-learn-more button button-outline button-md-border"
                >
                  learn more
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="ablout-workshops">
        <div class="ablout-content-container1">
          <div class="ablout-container6">
            <h1 class="ablout-text14 heading2">
              <span>
                register for
                <span v-html="rawkuei"></span>
              </span>
              <br />
              <span class="ablout-text17">super insightful</span>
              <span><span v-html="rawc8q2"></span></span>
              <br />
              <span>
                workshops for
                <span v-html="rawotih"></span>
              </span>
              <br />
              <span>your team</span>
            </h1>
            <span class="ablout-text23">
              get early discounts and group discounts
            </span>
            <span class="ablout-text24">
              Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet
              sint. Velit officia consequat duis enim velit mollit. Exercitation
              veniam consequat sunt nostrud amet.
            </span>
            <button class="button button-md button-outline">learn more</button>
          </div>
        </div>
        <div class="ablout-container7"></div>
      </div>
      <div class="ablout-previous-events section-container">
        <div data-type="slider" class="ablout-slider">
          <app-slide rootClassName="slide-root-class-name5"></app-slide>
          <app-slide
            heading="Slide #2"
            rootClassName="slide-root-class-name6"
          ></app-slide>
          <app-slide
            heading="Slide #3"
            rootClassName="slide-root-class-name7"
          ></app-slide>
          <app-slide
            heading="Slide #4"
            rootClassName="slide-root-class-name8"
          ></app-slide>
          <app-slide
            heading="Slide #5"
            rootClassName="slide-root-class-name9"
          ></app-slide>
        </div>
        <div class="ablout-slider-controls">
          <div data-action="previousSlide" class="ablout-go-left">
            <svg viewBox="0 0 1024 1024" class="ablout-icon">
              <path d="M250 176l92-90 426 426-426 426-92-90 338-336z"></path>
            </svg>
          </div>
          <div data-action="nextSlide" class="ablout-go-right">
            <svg viewBox="0 0 1024 1024" class="ablout-icon2">
              <path d="M250 176l92-90 426 426-426 426-92-90 338-336z"></path>
            </svg>
          </div>
        </div>
      </div>
    </main>
    <app-footer rootClassName="footer-root-class-name1"></app-footer>
  </div>
</template>

<script>
import AppNavigation from '../components/navigation'
import AppSlide from '../components/slide'
import AppFooter from '../components/footer'

export default {
  name: 'Ablout',
  components: {
    AppNavigation,
    AppSlide,
    AppFooter,
  },

  data() {
    return {
      rawkuei: ' ',
      rawc8q2: ' ',
      rawotih: ' ',
    }
  },

  metaInfo: {
    title: 'Ablout - Marketing Event Page',
    meta: [
      {
        property: 'og:title',
        content: 'Ablout - Marketing Event Page',
      },
    ],
  },
}
</script>

<style scoped>
.ablout-container {
  width: 100%;
  display: flex;
  position: relative;
  min-height: 100vh;
  overflow-x: hidden;
  align-items: center;
  flex-direction: column;
}
.ablout-main {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.ablout-hero {
  position: relative;
  align-self: center;
  margin-top: var(--dl-space-space-sixunits);
  padding-top: var(--dl-space-space-sixunits);
  background-color: var(--dl-color-scheme-darkgray);
}
.ablout-container1 {
  flex: 0 0 auto;
  width: 100%;
  height: 100px;
  display: flex;
  align-items: flex-start;
}
.ablout-text {
  color: var(--dl-color-scheme-lightblue);
  width: 100%;
  text-align: center;
}
.ablout-location {
  width: 100%;
  display: flex;
  align-items: stretch;
  flex-direction: row;
}
.ablout-container2 {
  flex: 0 0 auto;
  width: 50%;
  border: 2px dashed rgba(120, 120, 120, 0.4);
  height: auto;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.ablout-content-container {
  flex: 1;
  display: flex;
  align-items: stretch;
  padding-top: 100px;
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: row;
}
.ablout-container3 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.ablout-text01 {
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
.ablout-text02 {
  color: var(--dl-color-scheme-lightblue);
  font-size: 56px;
  font-style: normal;
  font-weight: 300;
  line-height: 1.1;
}
.ablout-container4 {
  display: flex;
  align-items: flex-end;
  margin-bottom: var(--dl-space-space-twounits);
  flex-direction: column;
}
.ablout-text03 {
  color: var(--dl-color-scheme-pink);
  font-size: 56px;
  font-style: normal;
  font-weight: 600;
  line-height: 1.1;
  margin-left: var(--dl-space-space-fiveunits);
}
.ablout-text05 {
  color: var(--dl-color-scheme-pink);
  font-size: 56px;
  font-style: normal;
  font-weight: 600;
  line-height: 1.1;
  margin-left: -36px;
}
.ablout-text07 {
  color: var(--dl-color-scheme-pink);
  font-size: 56px;
  font-style: normal;
  font-weight: 600;
  line-height: 1.1;
  margin-left: var(--dl-space-space-fiveunits);
}
.ablout-container5 {
  flex: 1;
  width: 100%;
  display: flex;
  max-width: 350px;
  align-items: flex-start;
  margin-left: 124px;
  flex-direction: column;
}
.ablout-text09 {
  color: var(--dl-color-scheme-lightblue);
  font-size: 18px;
  font-style: normal;
  font-weight: 600;
  margin-bottom: var(--dl-space-space-halfunit);
}
.ablout-text10 {
  color: var(--dl-color-scheme-lightblue);
  margin-bottom: var(--dl-space-space-twounits);
  text-transform: none;
}
.ablout-btns-container {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
}
.ablout-learn-more {
  color: var(--dl-color-scheme-lightblue);
  transition: 0.3s;
  border-color: var(--dl-color-scheme-lightblue);
}
.ablout-learn-more:hover {
  border-color: var(--dl-color-scheme-pink);
}
.ablout-workshops {
  flex: 1;
  width: 100%;
  display: flex;
  flex-direction: row;
}
.ablout-content-container1 {
  flex: 1;
  display: flex;
  align-items: flex-end;
  flex-direction: column;
  justify-content: center;
  background-color: rgba(144, 149, 167, 0.08);
}
.ablout-container6 {
  flex: 0 0 auto;
  display: flex;
  max-width: 366px;
  align-items: flex-start;
  margin-right: 107px;
  flex-direction: column;
}
.ablout-text14 {
  margin-bottom: 42px;
}
.ablout-text17 {
  color: var(--dl-color-scheme-pink);
}
.ablout-text23 {
  font-size: 18px;
  font-style: normal;
  font-weight: 600;
  margin-bottom: var(--dl-space-space-halfunit);
}
.ablout-text24 {
  margin-bottom: var(--dl-space-space-threeunits);
  text-transform: none;
}
.ablout-container7 {
  flex: 0 0 auto;
  width: 50%;
  border: 2px dashed rgba(120, 120, 120, 0.4);
  height: auto;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.ablout-previous-events {
  display: flex;
  position: relative;
  flex-direction: column;
  padding-bottom: 150px;
}
.ablout-slider {
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
.ablout-slider-controls {
  top: calc(50% + 24px);
  width: calc(60% + 48px);
  height: 48px;
  display: flex;
  position: absolute;
  align-self: center;
  justify-content: space-between;
}
.ablout-go-left {
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
.ablout-go-left:hover {
  border-color: var(--dl-color-scheme-lightblue);
  background-color: var(--dl-color-scheme-white80);
}
.ablout-icon {
  width: 24px;
  height: 24px;
  transform: rotate(180deg);
}
.ablout-go-right {
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
.ablout-go-right:hover {
  border-color: var(--dl-color-scheme-lightblue);
  background-color: var(--dl-color-scheme-white80);
}
.ablout-icon2 {
  width: 24px;
  height: 24px;
}
@media(max-width: 1200px) {
  .ablout-container2 {
    width: 50%;
    height: auto;
  }
  .ablout-content-container {
    background-color: var(--dl-color-scheme-darkgray);
  }
  .ablout-text02 {
    color: var(--dl-color-scheme-lightblue);
  }
  .ablout-text09 {
    color: var(--dl-color-scheme-lightblue);
  }
  .ablout-text10 {
    color: var(--dl-color-scheme-lightblue);
  }
  .ablout-learn-more {
    color: var(--dl-color-scheme-lightblue);
    border-color: var(--dl-color-scheme-lightblue);
  }
  .ablout-container7 {
    width: 50%;
    height: auto;
  }
}
@media(max-width: 991px) {
  .ablout-location {
    flex-direction: column;
  }
  .ablout-content-container {
    padding-top: 0px;
    padding-left: var(--dl-space-space-threeunits);
  }
  .ablout-container3 {
    margin-top: -100px;
    align-items: center;
  }
  .ablout-container5 {
    max-width: 100%;
    margin-left: 0px;
  }
  .ablout-container6 {
    margin-right: var(--dl-space-space-unit);
  }
  .ablout-slider-controls {
    width: calc(75% + 48px);
  }
}
@media(max-width: 767px) {
  .ablout-content-container {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .ablout-text01 {
    margin-left: -24px;
  }
  .ablout-btns-container {
    width: 100%;
    align-items: stretch;
    flex-direction: column;
  }
  .ablout-workshops {
    flex-direction: column-reverse;
    padding-bottom: var(--dl-space-space-twounits);
  }
  .ablout-container6 {
    max-width: 100%;
    padding-top: var(--dl-space-space-twounits);
    margin-right: 0px;
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .ablout-previous-events {
    padding-bottom: var(--dl-space-space-sixunits);
  }
  .ablout-slider-controls {
    width: calc(80% + 48px);
  }
}
</style>
