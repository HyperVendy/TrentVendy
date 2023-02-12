<script setup lang="ts">
useHead({
  title: 'Trent Vendy',
  meta: [
    { name: 'description', content: 'Landing Page for Trent Vendy' },
    {
      name: 'theme-color',
      content: computed(() => isDark.value ? '#00aba9' : '#ffffff'),
    },
  ],
  link: [
    {
      rel: 'icon',
      href: computed(() => preferredDark.value ? '/favicon.ico' : '/favicon.ico'),
    },
  ],
})
</script>

<template>
  <RouterView />
</template>
