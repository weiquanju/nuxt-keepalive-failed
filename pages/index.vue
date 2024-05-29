<script setup lang="ts">
definePageMeta({
    keepalive: true
})
</script>
<template>
    <div>
        <NuxtLayout>
            <h1>Home</h1>
            <h3>
                <NuxtLink href="/user">user</NuxtLink>
            </h3>
            <h3>
                <NuxtLink href="/dashboard">dashboard</NuxtLink>
            </h3>
        </NuxtLayout>
    </div>
</template>