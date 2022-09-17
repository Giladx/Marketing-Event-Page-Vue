<template>
  <div data-type="slide" class="slide-slide slide" v-bind:class="rootClassName">
    <div class="slide-max-wdith max-content-container">
      <h1 class="slide-text heading2">{{ heading }}</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Slide',
  props: {
    heading: {
      type: String,
      default: 'Slide #1',
    },
    rootClassName: String,
  },
}
</script>

<style scoped>
.slide-slide {
  align-items: center;
  justify-content: center;
}
.slide-max-wdith {
  flex: 0 0 auto;
  display: flex;
  flex-direction: column;
}
.slide-text {
  color: var(--dl-color-scheme-white);
}
.slide-root-class-name {
  background-color: var(--dl-color-scheme-pink);
}
.slide-root-class-name1 {
  background-color: var(--dl-color-scheme-darkgray);
}
.slide-root-class-name2 {
  background-color: var(--dl-color-scheme-pink);
}
.slide-root-class-name3 {
  background-color: var(--dl-color-scheme-darkgray);
}
.slide-root-class-name4 {
  background-color: var(--dl-color-scheme-darkblue);
}
.slide-root-class-name5 {
  background-color: var(--dl-color-scheme-darkblue);
}
.slide-root-class-name6 {
  background-color: var(--dl-color-scheme-darkgray);
}
.slide-root-class-name7 {
  background-color: var(--dl-color-scheme-lightblue);
}
.slide-root-class-name8 {
  background-color: var(--dl-color-scheme-darkgray);
}
.slide-root-class-name9 {
  background-color: var(--dl-color-scheme-pink);
}
@media(max-width: 1200px) {
  .slide-root-class-name7 {
    background-color: var(--dl-color-scheme-lightblue);
  }
  .slide-root-class-name8 {
    background-color: var(--dl-color-scheme-darkgray);
  }
}
</style>
