<script setup lang="ts">
import BaseCard from "./components/BaseCard.vue";
</script>

<template>
  <div
    class="relative flex h-screen w-screen items-center justify-center bg-[#18181b] p-16"
  >
    <div class="max-w-5xl w-full">
      <BaseCard class="w-full">
        <div class="relative h-full flex flex-col md:justify-center">
          <h2 class="text-2xl font-medium text-white">Deploy Everywhere</h2>

          <div class="mt-4 text-gray-400 md:w-1/2 md:text-lg">
            Studio works on any hosting platform. <br />
            Deploy on GitHub pages in one click.
          </div>
        </div>

        <div
          class="absolute bottom-0 right-0 flex items-center lg:inset-y-0 lg:h-full"
        >
          <img
            src="https://nuxt.studio/assets/home/projects-deploy.svg"
            class="hidden h-full cursor-pointer object-cover lg:block"
          />

          <img
            src="https://nuxt.studio/assets/home/projects-deploy-small.svg"
            class="cursor-pointer lg:hidden"
          />
        </div>
      </BaseCard>
    </div>
  </div>
</template>
