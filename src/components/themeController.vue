<script setup lang="ts">
import { onMounted } from "vue";
import { themeChange } from "theme-change";

// Use onMounted to initialize themeChange when the component is mounted
onMounted(() => {
  themeChange(false); // Initialize themeChange without immediate theme application
});
</script>

<template>
  <label class="grid cursor-pointer place-items-center mr-">
    <input
      type="checkbox"
      class="toggle theme-controller bg-base-content col-span-2 col-start-1 row-start-1"
      data-toggle-theme="cupcake,coffee"
      data-act-class="ACTIVECLASS"
    />
    <svg
      class="stroke-base-100 fill-base-100 col-start-1 row-start-1"
      xmlns="http://www.w3.org/2000/svg"
      width="14"
      height="14"
      viewBox="0 0 24 24"
      fill="none"
      stroke="currentColor"
      stroke-width="2"
      stroke-linecap="round"
      stroke-linejoin="round"
    >
      <circle cx="12" cy="12" r="5" />
      <path
        d="M12 1v2M12 21v2M4.2 4.2l1.4 1.4M18.4 18.4l1.4 1.4M1 12h2M21 12h2M4.2 19.8l1.4-1.4M18.4 5.6l1.4-1.4"
      />
    </svg>
    <svg
      class="stroke-base-100 fill-base-100 col-start-2 row-start-1"
      xmlns="http://www.w3.org/2000/svg"
      width="14"
      height="14"
      viewBox="0 0 24 24"
      fill="none"
      stroke="currentColor"
      stroke-width="2"
      stroke-linecap="round"
      stroke-linejoin="round"
    >
      <path d="M21 12.79A9 9 0 1 1 11.21 3 7 7 0 0 0 21 12.79z"></path>
    </svg>
  </label>
</template>
