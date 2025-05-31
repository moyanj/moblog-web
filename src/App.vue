<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router';
import { ElButton } from 'element-plus';
</script>

<template>
    <ElButton type="primary">
        <RouterLink to="/">Home</RouterLink>
    </ElButton>
    <RouterView />
</template>

<style scoped></style>
