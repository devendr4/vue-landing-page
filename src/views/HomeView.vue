<script setup lang="ts">
import SectionList from '@/components/SectionList.vue';
import ContentGrid from '@/components/ContentGrid.vue';
import PlaceholderCards from '@/components/icons/PlaceholderCards.vue';
import MainContent from '@/components/MainContent.vue';
import BackgroundPolygons from '@/components/icons/BackgroundPolygons.vue';
</script>

<template>
  <main class="relative md:mt-80 md:ml-20% md:mr-20% ml-[5%] mr-5%">
    <div class="flex flex-wrap-reverse w-full">
      <div class="lg:w-1/2 w-full">
        <MainContent />
      </div>
      <div class="lg:w-1/2 w-full">
        <div class="relative">
          <div class="max-w-full p-4">
            <PlaceholderCards />
          </div>
          <div class="absolute -top-[20rem] -right-[37rem] opacity-30 -z-20">
            <BackgroundPolygons />
          </div>
        </div>
      </div>
    </div>
    <SectionList />

    <ContentGrid />
    <img class="relative md:-left-[17rem] -left-[3rem] w-20%" src="../assets/orangetriangle.png" />
  </main>
</template>

<style></style>
