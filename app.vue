<template>
  <div>
    <ClientOnly>
      <NuxtLayout>
        <NuxtPage :keepalive="true" />
      </NuxtLayout>
    </ClientOnly>
  </div>
</template>
