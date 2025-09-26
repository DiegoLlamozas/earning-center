<script setup>
import {useI18n} from "vue-i18n";

const { t } = useI18n()
const router = useRouter();
const unavailableRoute = router.currentRoute.value.fullPath;

</script>

<template>
  <div class="align-content-start justify-content-start m-4">
    <h1 class="text-3xl font-bold mb-4">{{ t('pageNotFound.title') }}</h1>
    <p class="mb-2">{{ t('pageNotFound.content', {  'unavailable-router': unavailableRoute }) }}</p>
    <router-link to="/home">{{ t('page-not-found.go-home') }}</router-link>
  </div>
</template>

<style scoped>

</style>