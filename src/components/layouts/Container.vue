<script setup>
defineProps([
    'class'
])
</script>
<template>
    <div class="max-w-[1320px] mx-auto p-0" :class=class>
        <slot>
            
        </slot>
    </div>
</template>

