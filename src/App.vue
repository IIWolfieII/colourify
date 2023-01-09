<script setup>
import SideBar from "@/components/SideBar.vue";
</script>

<template>
  <div class="flex flex-no-wrap h-screen" style="background-color: #001514;">
    <SideBar></SideBar>
    <div class="container mx-auto py-10 h-64 md:w-4/5 w-11/12 px-6">
      <!-- Remove class [ border-dashed border-2 border-gray-300 ] to remove dotted border -->
      <div class="w-full h-full rounded border-dashed border-2 border-gray-300">
        <!-- Place your content here -->
        <router-view></router-view>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>

</style>
