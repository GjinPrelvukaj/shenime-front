<script setup lang="ts">
import themeChange from "@/components/themeController.vue";
import { RouterLink } from "vue-router";
</script>
<template>
  <div class="navbar sticky">
    <div class="navbar-start">
      <div class="dropdown">
        <div tabindex="0" role="button" class="btn btn-ghost lg:hidden">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-5 w-5"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M4 6h16M4 12h8m-8 6h16"
            />
          </svg>
        </div>
        <ul
          tabindex="0"
          class="menu menu-sm dropdown-content bg-base-100 rounded-box z-[1] mt-3 w-52 p-2 shadow"
        >
          <li>
            <RouterLink to="/">Home</RouterLink>
          </li>
          <li>
            <a
              href="https://github.com/GjinPrelvukaj"
              target="_blank"
              rel="noopener noreferrer"
              >About</a
            >
          </li>
          <li>
            <a
              href="https://github.com/GjinPrelvukaj/shenimet-dev"
              target="_blank"
              rel="noopener noreferrer"
              >Download</a
            >
          </li>
        </ul>
      </div>

      <a class="btn btn-ghost text-xl"
        ><img src="/icon.png" width="45" />Shenimet</a
      >
    </div>
    <div class="navbar-center hidden lg:flex">
      <ul class="menu menu-horizontal px-1">
        <li><RouterLink to="/">Home</RouterLink></li>
        <li>
          <a
            href="https://github.com/GjinPrelvukaj"
            target="_blank"
            rel="noopener noreferrer"
            >About</a
          >
        </li>
        <li>
          <a
            href="https://github.com/GjinPrelvukaj/shenimet-dev"
            target="_blank"
            rel="noopener noreferrer"
            >Download</a
          >
        </li>
      </ul>
    </div>
    <div class="navbar-end">
      <themeChange />
    </div>
  </div>
</template>
