<template>
  <router-view v-slot="{ Component, route }">
    <component :is="Component" :key="route.key" />
  </router-view>
</template>

<script setup lang="ts"></script>

<style scoped></style>
