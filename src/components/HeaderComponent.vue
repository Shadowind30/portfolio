<template>
  <Menubar :model="items">
    <template #start>
      <h1>Portfolio</h1>
    </template>
    <template #end>
      <Button icon="pi pi-palette"></Button>
    </template>
  </Menubar>
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
    icon: 'pi pi-mail',
  },
])
</script>
