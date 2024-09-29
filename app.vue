<template>
    <div>
        <HorizontalNavigation></HorizontalNavigation>
    </div>
    <div class="flex justify-center mt-8">
        <Avatar src="/avatar.jpg" size="300px"></Avatar>
    </div>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </template>

<script setup lang="ts">
import HorizontalNavigation from '~/components/HorizontalNavigation.vue';
import Avatar from './components/Avatar.vue';
</script>

<style>

</style>