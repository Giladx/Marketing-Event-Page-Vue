<template>
  <nav class="navigation-links-nav" v-bind:class="rootClassName">
    <router-link to="/ablout" class="navigation-links-navlink navigation-Link">
      {{ link1 }}
    </router-link>
    <span class="navigation-links-text navigation-Link">{{ link2 }}</span>
    <span class="navigation-links-text1 navigation-Link">{{ link3 }}</span>
  </nav>
</template>

<script>
export default {
  name: 'NavigationLinks',
  props: {
    rootClassName: String,
    link2: {
      type: String,
      default: 'Speakers',
    },
    link3: {
      type: String,
      default: 'Agenda',
    },
    link1: {
      type: String,
      default: 'About',
    },
  },
}
</script>

<style scoped>
.navigation-links-nav {
  flex: 0 0 auto;
  display: flex;
  align-items: center;
  flex-direction: row;
}
.navigation-links-navlink {
  color: var(--dl-color-scheme-white);
  cursor: pointer;
  transition: 0.3s;
  text-decoration: none;
}
.navigation-links-navlink:hover {
  color: var(--dl-color-scheme-pink);
}
.navigation-links-text {
  color: var(--dl-color-scheme-white);
  cursor: pointer;
  transition: 0.3s;
  margin-left: 41px;
}
.navigation-links-text:hover {
  color: var(--dl-color-scheme-pink);
}
.navigation-links-text1 {
  color: var(--dl-color-scheme-white);
  cursor: pointer;
  transition: 0.3s;
  margin-left: 41px;
}
.navigation-links-text1:hover {
  color: var(--dl-color-scheme-pink);
}








@media(max-width: 767px) {
  .navigation-links-nav {
    align-items: flex-start;
    flex-direction: column;
  }
  .navigation-links-navlink {
    margin-bottom: var(--dl-space-space-unit);
  }
  .navigation-links-text {
    margin-left: 0;
    margin-bottom: var(--dl-space-space-unit);
  }
  .navigation-links-text1 {
    margin-left: 0;
    margin-bottom: var(--dl-space-space-unit);
  }
}
</style>
