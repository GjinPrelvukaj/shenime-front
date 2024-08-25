<script setup lang="ts">
import { MoveRight } from "lucide-vue-next";
import { CodeXml } from "lucide-vue-next";
import window from "@/components/Hero/window.vue";
import { ref } from "vue";
</script>
<template>
  <div class="flex justify-center">
    <div class="flex flex-col items-center text-center gap-6 max-w-lg">
      <a
        class="btn"
        href="https://github.com/GjinPrelvukaj/shenimet-dev"
        target="_blank"
        rel="noopener noreferrer"
      >
        This website is open-source
        <CodeXml />
      </a>

      <h1 class="font-bold text-5xl mt-60">
        Welcome to
        <span class="text-primary">Shenimet</span>
      </h1>

      <span>
        Shenimet is an open-source, lightweight app that makes note-taking
        effortless and intuitive.
      </span>

      <div class="flex gap-4">
        <a
          href="https://github.com/GjinPrelvukaj/shenimet-dev"
          target="_blank"
          rel="noopener noreferrer"
        >
          <code class="btn btn-ghost border border-neutral">
            $ click me to clone :)
            <i class="fa-solid fa-copy text-lg text-secondary"></i>
          </code>
        </a>
      </div>
    </div>
  </div>
  <section>
    <div class="mt-[10%] hidden lg:block md:block">
      <window />
    </div>
  </section>
</template>
