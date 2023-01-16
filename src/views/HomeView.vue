<template>
  <div class="home">
    <product-page />
  </div>
</template>

<script lang="ts">
import ProductPage from "@/components/ProductPage.vue";
import { defineComponent } from "vue";

export default defineComponent({
  components: { ProductPage },
  name: "HomeView",
});
</script>
