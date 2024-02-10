<script setup>
import Buttons from '../layouts/Buttons.vue';
import Container from '../layouts/Container.vue';
import Pictures from '../layouts/Pictures.vue';
import { Swiper, SwiperSlide } from 'swiper/vue';
import { Autoplay } from 'swiper/modules';
import 'swiper/css';

let modules = [Autoplay]


</script>
<template>
    
      <div class="bg-[#222222]">
        <Container class="flex h-[860px]">
            <!-- right -->
            <div class="w-1/2 h-full flex justify-center items-center">
                <div class="w-[500px] h-[500px] border-[20px] border-[#444444] rounded-full overflow-hidden">
                    <Pictures source="https://cdn.pixabay.com/photo/2023/11/09/11/50/cat-8377169_1280.jpg" class="w-full h-full" />
                </div>
            </div>

            <!-- left -->
            <div class="w-1/2 h-full flex justify-start items-center">
                <div class="w-full">
                    <swiper class="mySwiper" :modules="modules" :autoplay="{delay: 4500}" :centeredSlides="true">
                        <swiper-slide>
                            <h4 class="text-[#aaa] font-pop font-light text-base mb-3">Welcome ,</h4>
                        </swiper-slide>
                        <swiper-slide>
                            <h4 class="text-[#aaa] font-pop font-light text-base mb-3">Backend Developer</h4>
                        </swiper-slide>
                        <swiper-slide>
                            <h4 class="text-[#aaa] font-pop font-light text-base mb-3">Frontend Developer</h4>
                        </swiper-slide>
                        
                    </swiper>
                    
                    <h4 class="text-[#f5f5f5] font-pop font-semibold text-[48px] mb-5">Fahim Hossain Munna</h4>
                    <p class="w-[560px] text-sm font-pop text-[#d5d5d5]">Fusce tempor magna mi, non egestas velit ultricies nec. Aenean convallis, risus non condimentum gravida,
                        odio mauris ullamcorper felis
                        , ut venenatis purus ex eu mi. 
                        Quisque imperdiet lacinia urna, a placerat sapien pretium eu.
                    </p>
                    <div class="mt-7 flex justify-start items-center gap-3">
                        <Buttons title="Download CV" />
                        <Buttons title="Contact" />
                    </div>
                </div>
            </div>
        </Container>
      </div>
</template>
