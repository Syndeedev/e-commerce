<template>
  <div class="pt-20 w-full">
    <div class="max-w-6xl m-auto px-4 sm:px-6">
      <div class="w-max bg-[#f5f5f5] p-2 rounded-md flex items-center">
        <button type="submit" aria-label="Search" class="mr-1">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="18"
            height="18"
            viewBox="0 0 24 24"
            aria-hidden="true"
            focusable="true"
          >
            <path
              stroke="#4f4f4f"
              d="m18.031 16.617 4.283 4.282-1.415 1.415-4.282-4.283A8.96 8.96 0 0 1 11 20c-4.968 0-9-4.032-9-9s4.032-9 9-9 9 4.032 9 9a8.96 8.96 0 0 1-1.969 5.617zm-2.006-.742A6.977 6.977 0 0 0 18 11c0-3.868-3.133-7-7-7-3.868 0-7 3.132-7 7 0 3.867 3.132 7 7 7a6.977 6.977 0 0 0 4.875-1.975l.15-.15z"
            ></path>
          </svg>
        </button>
        <input
          type="text"
          name="q"
          class="outline-none md:w-60 bg-[#f5f5f5]"
          placeholder="What are you shopping for?"
          autocomplete="off"
          aria-label="Search term"
        />
      </div>
      <div class="listing__result">
        <ul class="flex items-center flex-wrap justify-between">
          <single-product />
          <single-product />
          <single-product />
          <single-product />
          <single-product />
        </ul>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import SingleProduct from "./SingleProduct.vue";

export default defineComponent({
  components: { SingleProduct },
  setup() {
    return {};
  },
});
</script>

<style scoped>
/* .item__head img:hover {
  transition: transform 300ms ease;
  display: block;
  height: 100px;
  object-fit: cover;
  object-position: center;
} */
</style>
