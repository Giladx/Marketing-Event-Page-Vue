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
  color: #0b5400;
  cursor: pointer;
  transition: 0.3s;
}
.navigation-links-text {
  color: #0b5400;
  cursor: pointer;
  transition: 0.3s;
  margin-left: 41px;
}
.navigation-links-text1 {
  color: #0b5400;
  cursor: pointer;
  transition: 0.3s;
  margin-left: 41px;
}








@media(max-width: 767px) {
  .navigation-links-nav {
    align-items: flex-start;
    flex-direction: column;
  }
  .navigation-links-navlink {
    padding-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .navigation-links-text {
    margin-left: 0px;
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .navigation-links-text1 {
    margin-left: 0px;
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
}
</style>
