<template>
  <Menubar :model="items" />
</template>

<script lang="ts" setup>
import { ref } from 'vue'

const items = ref([
  {
    label: 'Home',
    icon: 'pi pi-home',
  },
  {
    label: 'Portfolio',
    icon: 'pi pi-case',
  },
  {
    label: 'Contact',
    icon: 'pi pi-main',
  },
])
</script>
