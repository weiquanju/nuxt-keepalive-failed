<script setup lang="ts">


const num = ref(0)

const change = () => {
    num.value++
}

definePageMeta({
    name: 'dashboard-business',
    keepalive: true
})
</script>
<template>
    <div>
        <h2>Business</h2>
        <button @click="change">change {{ num }}</button>
        <h3>
            <NuxtLink href="/dashboard">back</NuxtLink>
        </h3>
    </div>
</template>
<style scoped lang="css"></style>