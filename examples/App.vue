<script setup>
import { provide } from 'vue';
provide('globalConfig', {
  lang: 'en',
});
</script>
<template>
  <router-view></router-view>
</template>
