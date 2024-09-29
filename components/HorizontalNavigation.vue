<script setup lang="ts">
const links = [{
  label: '',  
  icon: 'i-hugeicons:home-03',
  to: '/'
}, {
  label: '',
  icon: 'i-hugeicons:computer-programming-01',
  to: '/projects'
}, {
  label: '',
  icon: 'i-hugeicons:mail-01',
}]
</script>

<template>
  <UHorizontalNavigation :links="links" class="flex justify-center w-screen mt-4 border-b border-gray-200 dark:border-gray-800" />
</template>
