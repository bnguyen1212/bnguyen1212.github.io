<template>
    <div>
        <HorizontalNavigation></HorizontalNavigation>
    </div>
    <NuxtPage />
  </template>

<script setup lang="ts">
import HorizontalNavigation from '~/components/HorizontalNavigation.vue';
import Avatar from './components/Avatar.vue';
</script>

<style>
.page-enter-active,
.page-leave-active {
  transition: all 0.4s;
}
.page-enter-from,
.page-leave-to {
  opacity: 0;
  filter: blur(1rem);
}
</style>