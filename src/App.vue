<template>
  <navbar-section />
  <router-view />
  <footer-section />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import FooterSection from "@/components/FooterSection.vue";
import NavbarSection from "./components/NavbarSection.vue";

export default defineComponent({
  components: {
    FooterSection,
    NavbarSection,
  },
});
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
