<script setup> 
import { Swiper, SwiperSlide } from 'swiper/vue'; 
import { Navigation, Pagination, A11y } from 'swiper/modules'; 
import 'swiper/css'; 
import 'swiper/css/navigation'; 
import 'swiper/css/pagination'; 
import 'swiper/css/scrollbar'; 
</script> 
 
<template> 
  <Swiper 
    :modules="[Navigation, Pagination]" 
    :slides-per-view="1" 
    :space-between="50" 
    :pagination="{ clickable: true }" 
  > 
    <SwiperSlide> 
        <img src="../src/assets/Group 112.png" alt=""> 
    </SwiperSlide> 
    <SwiperSlide> 
        <img src="../src/assets/Group 112.png" alt=""> 
    </SwiperSlide> 
    <SwiperSlide> 
        <img src="../src/assets/Group 112.png" alt=""> 
    </SwiperSlide> 
  </Swiper> 
</template>