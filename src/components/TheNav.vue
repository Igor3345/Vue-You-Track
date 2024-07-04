<script setup>
import { ClockIcon, ListBulletIcon, ChartBarIcon } from '@heroicons/vue/24/outline'
import NavItem from './NavItem.vue'

const navItems = { timeline: ClockIcon, activities: ListBulletIcon, progress: ChartBarIcon }
</script>

<template>
  <nav class="sticky bottom-0 z-20 bg-white border-t">
    <ul class="flex items-center justify-around">
      <NavItem v-for="(icon, page) in navItems" :key="page" :href="`#${page}`">
        <component :is="icon" class="h-6 w-6" /> {{ page }}
      </NavItem>
    </ul>
  </nav>
</template>
