<script setup>
import { Swiper, SwiperSlide } from 'swiper/vue';
import { Navigation, Pagination } from 'swiper/modules';

import 'swiper/css';
import 'swiper/css/navigation';
import 'swiper/css/pagination';
</script>

<template>
  <swiper
    :slides-per-view="1"
    :space-between="50"
    :modules="[Navigation, Pagination]"
  >
    <swiper-slide>
      <img src="../assets/slide-img.png" alt="" />
    </swiper-slide>
    <swiper-slide>
      <img src="../assets/slide-img.png" alt="" />
    </swiper-slide>
    <swiper-slide>
      <img src="../assets/slide-img.png" alt="" />
    </swiper-slide>
  </swiper> 
  <div> 
    <div > 
      <img src="../assets/icon-like.svg" alt="like"> 
      <img src="../assets/card-icon.png" alt=""> 
       
       <div>   
         <span>Мужские Кроссовки Nike Blazer Mid Suede</span> 
         <span>Цена:</span> 
         <span>12 999 руб.</span>
        </div> 
       <img src="../assets/plus.svg" alt="">
    </div>
  </div>
</template>
