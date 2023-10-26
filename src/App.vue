<script setup lang="ts">
import { createHead } from 'unhead'
import { RouterView } from 'vue-router'
import MainLayout from './components/layouts/MainLayout.vue';

createHead()
</script>

<template>
  <MainLayout>
    <RouterView />
  </MainLayout>
</template>