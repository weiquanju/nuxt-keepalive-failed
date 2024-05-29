<script setup lang="ts">
definePageMeta({
    name: 'user',
    redirect: 'user-index',
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