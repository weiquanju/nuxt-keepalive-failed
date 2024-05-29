<script setup lang="ts">
definePageMeta({
    name: 'dashboard',
    redirect: 'dashboard-index',
    keepalive: true
})
</script>
<template>
    <div>
        <NuxtLayout>
            <RouterView />
        </NuxtLayout>
    </div>
</template>