<script setup>
import Menu from '../layouts/Menu.vue';

</script>


<template>
    <div class="bg-[#222222] w-full flex">
        <div class="w-1/2 h-full flex justify-start items-center gap-3 py-4">
            <div class="w-[60px] h-[60px] flex justify-center items-center border-0 rounded-full text-white bg-[#007CED] ml-10">
                <i class="fa-solid fa-f font-pop text-2xl"></i>
                <i class="fa-solid fa-h font-pop text-2xl"></i>
            </div>
            <h2 class="font-pop text-xl font-medium text-white">Fahim Hossain Munna</h2>
        </div>
        <div class="w-1/2 py-4 flex justify-end items-center mr-10" >
            <Menu/>
        </div>
    </div>
</template>

