<script setup>
import {useI18n} from "vue-i18n";

const { t } = useI18n()
</script>

<template>
  <div class="align-content-start justify-content-start m-4">
    <h1 class="text-3xl font-bold mb-4">{{ t('home.title') }}</h1>
    <p class="mb-2">{{ t('home.content') }}</p>
  </div>
</template>

<style scoped>

</style>