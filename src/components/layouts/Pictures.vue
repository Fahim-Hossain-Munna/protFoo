<script setup>
defineProps([
    'source',
    'class'
])
</script>
<template>
    <picture>
        <img :src=source :class=class>
    </picture>
</template>

