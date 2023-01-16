<template>
  <div class="fixed top-0 w-full z-50">
    <div class="bg-white">
      <nav
        class="m-auto max-w-6xl flex items-center justify-between py-5 px-4 sm:px-6"
      >
        <div class="flex items-center gap-2">
          <div class="bg-[#dadef5] p-2 rounded-full">
            <span class="font-semibold text-[#0f1c70] text-sm">KO</span>
          </div>
          <a
            href=""
            class="font-semibold text-xl text-[#333333] hover:text-[#EE6E24]"
          >
            Kokash
          </a>
        </div>
        <div class="flex items-center gap-6 md:gap-16">
          <a href="" class="uppercase text-xs font-bold hover:text-[#EE6E24]"
            >set up your store for free</a
          >

          <button class="flex items-center gap-2">
            <span class="header__nav__btn__icon relative">
              <svg
                fill="none"
                height="24"
                viewBox="0 0 24 24"
                width="24"
                class="hover:text-[#EE6E24]"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  stroke="#000000"
                  stroke-width="2"
                  d="M9 22C9.6 22 10 21.6 10 21 10 20.4 9.6 20 9 20 8.4 20 8 20.4 8 21 8 21.6 8.4 22 9 22Z"
                  class="a"
                ></path>
                <path
                  stroke="#000000"
                  stroke-width="2"
                  d="M20 22C20.6 22 21 21.6 21 21 21 20.4 20.6 20 20 20 19.4 20 19 20.4 19 21 19 21.6 19.4 22 20 22Z"
                  class="a"
                ></path>
                <path
                  stroke="#000000"
                  stroke-width="2"
                  d="M1 1H5L7.7 14.4C7.8 14.9 8 15.3 8.4 15.6 8.8 15.9 9.2 16 9.7 16H19.4C19.9 16 20.3 15.9 20.7 15.6 21.1 15.3 21.3 14.9 21.4 14.4L23 6H6"
                  class="a"
                ></path>
              </svg>
              <span data-v-5d92f3cc="" class="header__nav__btn__count"
                >1</span
              ></span
            >
            <span
              data-v-5d92f3cc=""
              class="text-[#333333] font-bold hover:text-[#EE6E24]"
              >Cart</span
            >
          </button>
        </div>
      </nav>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  setup() {
    return {};
  },
});
</script>

<style scoped>
.header__nav__btn__count {
  align-items: center;
  animation-duration: 1.5s;
  animation-iteration-count: 10;
  animation-name: removeproduct;
  background-color: #ff4067;
  border-radius: 50%;
  color: #ffffff;
  display: flex;
  font-size: 10px;
  height: 18px;
  justify-content: center;
  position: absolute;
  right: -10px;
  top: -10px;
  width: 18px;
  font-family: sans-serif;
  font-weight: 700;
}
</style>
