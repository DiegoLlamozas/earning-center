<script setup>
import {useI18n} from "vue-i18n";

const { t } = useI18n()
</script>

<template>
  <div class="align-content-start justify-content-start m-4">
    <h1>{{ t('about.title') }}</h1>
    <image src="../src/assets/vue.svg" alt="ACME Logo" mode="aspectFill" width="200" height="200" />
  </div>
</template>

<style scoped>

</style>