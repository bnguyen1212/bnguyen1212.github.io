<script setup lang="ts">
const links = [{
  label: '',  
  icon: 'i-hugeicons:home-03',
}, {
  label: '',
  icon: 'i-hugeicons:computer-programming-01',
}, {
  label: '',
  icon: 'i-hugeicons:user-circle-02',
}, {
  label: '',
  icon: 'i-hugeicons:mail-01',
}]
</script>

<template>
  <UHorizontalNavigation :links="links" class="border-b border-gray-200 dark:border-gray-800" />
</template>

