<script setup>
import '@unocss/reset/tailwind.css'

useHead({
    htmlAttrs: {
        style: 'font-size: 12px',
    },
})
</script>

<template>
    <main>
        <slot />
    </main>
</template>

<style>
body {
    font-family: var(--font-family);
    background-color: var(--surface-ground);
}
</style>
