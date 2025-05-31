<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router';
import { ElButton } from 'element-plus';
</script>

<template>
    <div class="bg-blue-200">
        <h1>Home</h1>
    </div>
    <el-button type="primary">
        <RouterLink to="/about">About</RouterLink>
    </el-button>
    <RouterView />
</template>

<style scoped></style>
