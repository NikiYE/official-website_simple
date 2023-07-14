<template>
  <swiper
    :style="{
      '--swiper-navigation-color': '#fff',
      '--swiper-pagination-color': '#fff',
    }"
    :navigation="true"
    :pagination="{
      clickable: true,
    }"
    :modules="modules"
    class="mySwiper"
  >
    <swiper-slide :style="{ color: '#ccc','background': 'url(' + imgUrl2 + ')'  }">
        <div class="swiper-zoom-container">
          <h1 :style="{ 'font-size': '100px'}">文字文字文字</h1>
          <p :style="{fontSize: '18px',color: '#eee'}">文文字文字文字，文字文字文字，文字文字文字，文字文字文字，文字文字文字，文字文字文字，文字文字文字</p>
        </div> 
    </swiper-slide>
    <swiper-slide  :style="{ color: '#ccc','background': 'url(' + imgUrl1 + ')'  }">
      <div class="swiper-zoom-container">
        <h1>文字文字文字</h1>
        <p>文字文字文字，文字文字文字，文字文字文字，文字文字文字，文字文字文字，文字文字文字，文字文字文字，文字文字文字，文字文字文字，文字文字文字，文字文字文字</p>
      </div>   
    </swiper-slide>
  </swiper>
</template>
<script>
  import imgUrl1 from '../assets/img/bg1.png'
  import imgUrl2 from '../assets/img/bg2.png'

  // Import Swiper Vue.js components
  import { Swiper, SwiperSlide } from 'swiper/vue';

  // Import Swiper styles
  import 'swiper/css';
  import 'swiper/css/pagination';

  // import required modules
  import { Navigation,Pagination } from 'swiper/modules';

  export default {
  name: "HomePage",
    data() {
      return {
        imgUrl1,imgUrl2
      }
    },
    components: {
      Swiper,
      SwiperSlide,
    },
    mounted() {
      //我想要小于30岁的人的名字
      const aPersonData = [
      { id: 1, name: 'John', age: 25 },
      { id: 2, name: 'Jane', age: 28 },
      { id: 3, name: 'Tom', age: 35 }
      ];
      const aNewPersonData = aPersonData.filter( person =>  person.age <= 30).map( person => person.name)
      console.log(aNewPersonData)
    },

    setup() {
      return {
        modules: [Navigation,Pagination],
      };
    },
  };
</script>
<style scoped>
.swiper {
  width: 100%;
  height: 100%;
}

.swiper-slide {
  text-align: center;
  font-size: 18px;
  background: #eee;

  /* Center slide text vertically */
  display: flex;
  justify-content: center;
  align-items: center;
}

.swiper-slide img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
}
#swiper > h1{
  font-size: 50px;
  margin-top: 12%;
}
#swiper > p{
  font-size: 20px;
  margin-top: 1%;
  font-weight: 700;
}
</style>