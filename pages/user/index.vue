<script setup lang="ts">
definePageMeta({
    name: 'user-index',
    keepalive: true
})

const age = ref(20)
const change = () => {
    age.value++
}
</script>
<template>
    <div>
        <h1>User</h1>
        <button @click="change">change user age: {{ age }}</button>
    </div>
    <h3>
        <NuxtLink href="/">back to home</NuxtLink>
    </h3>
</template>
<style scoped lang="css"></style>