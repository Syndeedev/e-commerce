<template>
  <li class="item flex items-center border-b py-7">
    <div class="item__head relative overflow-hidden">
      <img
        alt="Google Pixel"
        src="https://cdn.filestackcontent.com/resize=width:399,height:399,fit:crop,align:center/8bVU42ZpSKeWk3sUeYzm"
        class="item__image w-36 h-36"
      />
    </div>
    <div class="item__body">
      <div class="item__info text-left">
        <a
          href="/store/kokash/kwpqklt7s15dtx"
          class="item__name font-medium text-lg"
          >Google Pixel</a
        >

        <p class="item__description item__description--web mb-3 mt-1 text-sm">
          Google Pixel Device
        </p>
        <div class="item__price-group">
          <p class="item__price font-bold text-lg">NGN 50.00</p>
        </div>
      </div>
      <div class="item__cta">
        <div class="action flex items-center gap-3 pt-2">
          <button type="button" class="action__minus">
            <svg
              fill="none"
              height="24"
              viewBox="0 0 24 24"
              width="24"
              xmlns="http://www.w3.org/2000/svg"
            >
              <circle
                cx="12"
                cy="12"
                fill="#F2F2F2"
                r="11.5"
                stroke="#E0E0E0"
              ></circle>
              <path
                d="M14.158 12.332H10.7V11.275H14.158V12.332Z"
                fill="#333333"
              ></path>
            </svg>
          </button>
          <span class="action__value">0</span>
          <button type="button" class="action__plus">
            <svg
              fill="none"
              height="24"
              viewBox="0 0 24 24"
              width="24"
              xmlns="http://www.w3.org/2000/svg"
            >
              <circle
                cx="12"
                cy="12"
                fill="#F2F2F2"
                r="11.5"
                stroke="#E0E0E0"
              ></circle>
              <path
                d="M15.406 11.772H12.557V14.782H11.535V11.772H8.7V10.827H11.535V7.838H12.557V10.827H15.406V11.772Z"
                fill="#333333"
              ></path>
            </svg>
          </button>
        </div>
      </div>
    </div>
  </li>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  setup() {
    return {};
  },
});
</script>

<style scoped></style>
