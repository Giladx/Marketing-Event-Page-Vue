<template>
  <div class="ablout-container">
    <app-navigation></app-navigation>
    <main class="ablout-main">
      <div class="ablout-hero section-container">
        <div class="ablout-blue-background"></div>
      </div>
      <div class="ablout-location">
        <img
          alt="image"
          src="https://images.unsplash.com/photo-1564347288827-3e4293543e07?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDE2fHxiZXJsaW58ZW58MHx8fHwxNjQzNzEzNjQ5&amp;ixlib=rb-1.2.1&amp;w=1500"
          class="ablout-image"
        />
        <div class="ablout-content-container section-container">
          <div class="ablout-container1">
            <span class="ablout-text">berlin, germany</span>
            <span class="ablout-text01">7-8 MARCH 2023</span>
            <div class="ablout-container2">
              <span class="ablout-text02"><span>— mob-x</span></span>
              <span class="ablout-text04"><span>conference</span></span>
              <span class="ablout-text06"><span>center</span></span>
            </div>
            <div class="ablout-container3">
              <span class="ablout-text08">beautiful, vibrant berlin</span>
              <span class="ablout-text09">
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
          <div class="ablout-container4">
            <h1 class="ablout-text13 heading2">
              <span>
                register for
                <span v-html="rawdeqq"></span>
              </span>
              <br />
              <span class="ablout-text16">super insightful</span>
              <span><span v-html="raw6d4s"></span></span>
              <br />
              <span>
                workshops for
                <span v-html="rawsw5j"></span>
              </span>
              <br />
              <span>your team</span>
            </h1>
            <span class="ablout-text22">
              get early discounts and group discounts
            </span>
            <span class="ablout-text23">
              Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet
              sint. Velit officia consequat duis enim velit mollit. Exercitation
              veniam consequat sunt nostrud amet.
            </span>
            <button class="button button-md button-outline">learn more</button>
          </div>
        </div>
        <img
          alt="image"
          src="https://images.unsplash.com/photo-1556761175-5973dc0f32e7?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDIwfHxidXNpbmVzc3xlbnwwfHx8fDE2NDM3MzQ3MjI&amp;ixlib=rb-1.2.1&amp;w=1500"
          class="ablout-image1"
        />
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
      rawdeqq: ' ',
      raw6d4s: ' ',
      rawsw5j: ' ',
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
  padding-top: 128px;
}
.ablout-blue-background {
  top: 0px;
  right: 0px;
  width: 47%;
  height: 100px;
  position: absolute;
  min-height: 80%;
  background-size: cover;
  background-image: url("/playground_assets/blue-background-1500w.png");
  background-repeat: no-repeat;
}
.ablout-location {
  width: 100%;
  display: flex;
  align-items: stretch;
  flex-direction: row;
}
.ablout-image {
  width: 55%;
  max-height: 950px;
  object-fit: cover;
}
.ablout-content-container {
  flex: 1;
  display: flex;
  align-items: stretch;
  padding-top: 100px;
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: row;
  background-color: var(--dl-color-scheme-black);
}
.ablout-container1 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.ablout-text {
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
.ablout-text01 {
  color: var(--dl-color-scheme-white);
  font-size: 56px;
  font-style: normal;
  font-weight: 300;
  line-height: 1.1;
}
.ablout-container2 {
  display: flex;
  align-items: flex-end;
  margin-bottom: var(--dl-space-space-twounits);
  flex-direction: column;
}
.ablout-text02 {
  color: var(--dl-color-scheme-pink);
  font-size: 56px;
  font-style: normal;
  font-weight: 600;
  line-height: 1.1;
  margin-left: var(--dl-space-space-fiveunits);
}
.ablout-text04 {
  color: var(--dl-color-scheme-pink);
  font-size: 56px;
  font-style: normal;
  font-weight: 600;
  line-height: 1.1;
  margin-left: -36px;
}
.ablout-text06 {
  color: var(--dl-color-scheme-pink);
  font-size: 56px;
  font-style: normal;
  font-weight: 600;
  line-height: 1.1;
  margin-left: var(--dl-space-space-fiveunits);
}
.ablout-container3 {
  flex: 1;
  width: 100%;
  display: flex;
  max-width: 350px;
  align-items: flex-start;
  margin-left: 124px;
  flex-direction: column;
}
.ablout-text08 {
  color: var(--dl-color-scheme-white);
  font-size: 18px;
  font-style: normal;
  font-weight: 600;
  margin-bottom: var(--dl-space-space-halfunit);
}
.ablout-text09 {
  color: var(--dl-color-scheme-white);
  margin-bottom: var(--dl-space-space-twounits);
  text-transform: none;
}
.ablout-btns-container {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
}
.ablout-learn-more {
  color: var(--dl-color-scheme-white);
  transition: 0.3s;
  border-color: var(--dl-color-scheme-white);
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
.ablout-container4 {
  flex: 0 0 auto;
  display: flex;
  max-width: 366px;
  align-items: flex-start;
  margin-right: 107px;
  flex-direction: column;
}
.ablout-text13 {
  margin-bottom: 42px;
}
.ablout-text16 {
  color: var(--dl-color-scheme-pink);
}
.ablout-text22 {
  font-size: 18px;
  font-style: normal;
  font-weight: 600;
  margin-bottom: var(--dl-space-space-halfunit);
}
.ablout-text23 {
  margin-bottom: var(--dl-space-space-threeunits);
  text-transform: none;
}
.ablout-image1 {
  width: 55%;
  min-height: 880px;
  object-fit: cover;
  object-position: bottom;
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
  .ablout-blue-background {
    height: 50px;
  }
}
@media(max-width: 991px) {
  .ablout-blue-background {
    top: auto;
    width: 100%;
    bottom: 0px;
    min-height: 40%;
  }
  .ablout-location {
    flex-direction: column;
  }
  .ablout-image {
    width: 100%;
  }
  .ablout-content-container {
    padding-top: 0px;
    padding-left: var(--dl-space-space-threeunits);
  }
  .ablout-container1 {
    margin-top: -100px;
    align-items: center;
  }
  .ablout-container3 {
    max-width: 100%;
    margin-left: 0px;
  }
  .ablout-container4 {
    margin-right: var(--dl-space-space-unit);
  }
  .ablout-image1 {
    width: 50%;
    object-position: left;
  }
  .ablout-slider-controls {
    width: calc(75% + 48px);
  }
}
@media(max-width: 767px) {
  .ablout-image {
    max-height: 100%;
  }
  .ablout-content-container {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .ablout-text {
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
  .ablout-container4 {
    max-width: 100%;
    padding-top: var(--dl-space-space-twounits);
    margin-right: 0px;
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .ablout-image1 {
    width: 100%;
  }
  .ablout-previous-events {
    padding-bottom: var(--dl-space-space-sixunits);
  }
  .ablout-slider-controls {
    width: calc(80% + 48px);
  }
}
</style>
