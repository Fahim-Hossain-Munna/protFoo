<script setup>
defineProps([
    'title'
])
</script>

<template>
    <button class="font-pop text-base px-8 py-3 border-2 transition-all duration-500 border-[#007CED] text-white rounded-full hover:bg-[#007CED]">{{ title }}</button>
</template>
