<script setup lang="ts">
import type { NavigationMenuItem } from '@nuxt/ui'

const items = ref<NavigationMenuItem[]>([
  {
    label: 'Web Design',
    icon: 'i-lucide-database',
    to: '/',
    children: [
      // {
      //   label: 'Basic',
      //   icon: 'i-lucide-file-text',
      //   description: 'Basic JavaScript Instructions',
      //   to: '/basic'
      // },
      // {
      //   label: 'Functions',
      //   icon: 'i-lucide-file-text',
      //   description: 'Functions, Methods, & Objects',
      //   to: '/function'
      // },
      // {
      //   label: 'Decision',
      //   icon: 'i-lucide-file-text',
      //   description: 'Decisions & Loops',
      //   to: '/decision'
      // },
      // {
      //   label: 'DOM',
      //   icon: 'i-lucide-file-text',
      //   description: 'Document Object Model',
      //   to: '/dom'
      // },
      // {
      //   label: 'Events',
      //   icon: 'i-lucide-file-text',
      //   description: 'Events',
      //   to: '/events'
      // },
    ]
  },
])
</script>

<template>
  <UNavigationMenu :items="items" class="w-full justify-center" />
</template>
