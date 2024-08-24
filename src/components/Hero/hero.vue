<script setup lang="ts">
import { MoveRight } from "lucide-vue-next";
import { CodeXml } from "lucide-vue-next";
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
        Open-Source
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
        <a class="btn btn-primary">
          Get started
          <MoveRight />
        </a>

        <a
          href="https://github.com/GjinPrelvukaj/shenimet-dev"
          target="_blank"
          rel="noopener noreferrer"
        >
          <code class="btn btn-ghost border border-neutral">
            $ git clone me :)
            <i class="fa-solid fa-copy text-lg text-secondary"></i>
          </code>
        </a>
      </div>

      <a class="link link-secondary">
        Installation guide
        <i class="fa-solid fa-arrow-right text-sm"></i>
      </a>
    </div>
  </div>
</template>
