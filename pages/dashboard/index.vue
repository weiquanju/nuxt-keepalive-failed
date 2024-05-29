<script setup lang="ts">


const num = ref(0)

const change = () => {
    num.value++
}

definePageMeta({
    name: 'dashboard-index',
    keepalive: true
})
</script>
<template>
    <div>
        <h2>Dashboard</h2>
        <button @click="change">change {{ num }}</button>
        <h3>
            <NuxtLink href="/dashboard/business">business</NuxtLink>
        </h3>
        <h3>
            <NuxtLink href="/">back to home</NuxtLink>
        </h3>
    </div>
</template>
<style scoped lang="css"></style>