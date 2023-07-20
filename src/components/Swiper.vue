<template>
  <!-- <swiper
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
  
    <swiper-slide class="swiper-zero">
      <div class="swiper-zoom-container">
        <h1 :style="{ 'font-size': '100px'}">ONE</h1>
      </div> 
    </swiper-slide>
    <swiper-slide class="swiper-one">
      <div class="swiper-zoom-container">
        <h1 :style="{ 'font-size': '100px'}">文字/logo</h1>
        <p :style="{fontSize: '18px',color: '#eee'}">文文字文字文字，文字文字文字，文字文字文字，文字文字文字，文字文字文字，文字文字文字，文字文字文字</p>
      </div> 
    </swiper-slide>
    <swiper-slide  :style="{ color: '#ccc','background': 'url(' + imgUrl2 + ')'  }">
      <div class="swiper-zoom-container">
        <h1>文字文字文字</h1>
        <p>文字文字文字，文字文字文字，文字文字文字，文字文字文字，文字文字文字，文字文字文字，文字文字文字，文字文字文字，文字文字文字，文字文字文字，文字文字文字</p>
      </div>   
    </swiper-slide>
  </swiper> -->
  <div class="wave_bg">
    <div class="blur_wrap">
      <div class="wave_one"></div>
      <div class="wave-blur"></div>
    </div>
    <div class="wave_two">
    </div>
    <div class="wave_wrap">
      <svg style="position: absolute;"><clipPath id="clip"><path d="M1175.65 35.7644C962.846 -46.1285 865.751 35.6288 643.768 54.6084C421.786 73.588 391.68 33.0436 226.292 14.4975C60.9034 -4.0486 11.1228 90.8729 -67.9998 110.654C-67.9998 198.586 -67.9998 516 -67.9998 516L1508.19 516L1508.19 8.45359C1508.19 8.45359 1388.84 117.807 1175.65 35.7644Z"></path></clipPath></svg>
    </div>
    <div class="w1280">
      <div class="wave_content">
        <div class="wave_logo"></div>
        <p>修志，修最好的</p>
        <p>修志，修村志，修修修，村志志书</p>
        <div class="wave_img">
          <div class="btn draw meet">咔咔修</div>
        </div>
      </div>
    </div>
  </div>
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
  // import { Navigation,Pagination } from 'swiper/modules';

  // export default {
  // name: "HomePage",
  //   data() {
  //     return {
  //       imgUrl1,imgUrl2
  //     }
  //   },
  //   components: {
  //     Swiper,
  //     SwiperSlide,
  //   },
  //   mounted() {
  //     //我想要小于30岁的人的名字
  //     const aPersonData = [
  //     { id: 1, name: 'John', age: 25 },
  //     { id: 2, name: 'Jane', age: 28 },
  //     { id: 3, name: 'Tom', age: 35 }
  //     ];
  //     const aNewPersonData = aPersonData.filter( person =>  person.age <= 30).map( person => person.name)
  //     console.log(aNewPersonData)
  //   },

  //   setup() {
  //     return {
  //       modules: [Navigation,Pagination],
  //     };
  //   },
  // };
</script>
<style scoped>
.wave_bg{
  width: 100%;
  height: 100%;
  overflow: hidden;
  position: relative;
  background-color: #88FFCD;
  background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100%25' height='100%25' viewBox='0 0 1200 800'%3E%3Cdefs%3E%3CradialGradient id='a' cx='0' cy='800' r='800' gradientUnits='userSpaceOnUse'%3E%3Cstop offset='0' stop-color='%232af7ff'/%3E%3Cstop offset='1' stop-color='%232af7ff' stop-opacity='0'/%3E%3C/radialGradient%3E%3CradialGradient id='b' cx='1200' cy='800' r='800' gradientUnits='userSpaceOnUse'%3E%3Cstop offset='0' stop-color='%2312e0fc'/%3E%3Cstop offset='1' stop-color='%2312e0fc' stop-opacity='0'/%3E%3C/radialGradient%3E%3CradialGradient id='c' cx='600' cy='0' r='600' gradientUnits='userSpaceOnUse'%3E%3Cstop offset='0' stop-color='%23024bae'/%3E%3Cstop offset='1' stop-color='%23024bae' stop-opacity='0'/%3E%3C/radialGradient%3E%3CradialGradient id='d' cx='600' cy='800' r='600' gradientUnits='userSpaceOnUse'%3E%3Cstop offset='0' stop-color='%2388FFCD'/%3E%3Cstop offset='1' stop-color='%2388FFCD' stop-opacity='0'/%3E%3C/radialGradient%3E%3CradialGradient id='e' cx='0' cy='0' r='800' gradientUnits='userSpaceOnUse'%3E%3Cstop offset='0' stop-color='%230066CC'/%3E%3Cstop offset='1' stop-color='%230066CC' stop-opacity='0'/%3E%3C/radialGradient%3E%3CradialGradient id='f' cx='1200' cy='0' r='800' gradientUnits='userSpaceOnUse'%3E%3Cstop offset='0' stop-color='%23043490'/%3E%3Cstop offset='1' stop-color='%23043490' stop-opacity='0'/%3E%3C/radialGradient%3E%3C/defs%3E%3Crect fill='url(%23a)' width='1200' height='800'/%3E%3Crect fill='url(%23b)' width='1200' height='800'/%3E%3Crect fill='url(%23c)' width='1200' height='800'/%3E%3Crect fill='url(%23d)' width='1200' height='800'/%3E%3Crect fill='url(%23e)' width='1200' height='800'/%3E%3Crect fill='url(%23f)' width='1200' height='800'/%3E%3C/svg%3E");
  background-attachment: fixed;
  background-size: cover;
}
.wave_one{
  position: absolute;
  width: 100%;
  background-position: center top;
  background-repeat: no-repeat;
  background-size: 100%;
  top: 50px;
  height: 900px;
  background-image: url(./../assets/img/wave1.svg);
}

.wave_content{
  color: #fff;
  font-size: 30px;
  font-weight: bold;
  text-align: right;
  padding: 150px 80px 0;
}
.wave_logo{
  height: 280px;
  background-image: url(./../assets/img/logo.svg);
  background-repeat: no-repeat;
  background-position: right;
}

.blur_wrap{
  
}
.wave-blur{
  position: absolute;
  width: 100%;
  height: 800px;
  backdrop-filter: blur(60px);
}

@media (min-width: 1440px){
  .wave_wrap {
      transform: scale(1.5);
  }
}
.wave_two {
    position: absolute;
    width: 100%;
    background-position: center top;
    background-repeat: no-repeat;
    background-size: 100%;
    top: 380px;
    left: 0px;
    height: 600px;
    background-image: url(./../assets/img/wave2.svg);
}
.wave_wrap {
    position: absolute;
    width: 100%;
    top: 520px;
    height: 500px;
    clip-path: url(#clip);
    transform-origin: left top;
    background: linear-gradient(rgba(190, 255, 255, 0.25) -18.72%, rgb(242, 246, 255) 37.6%);
}




.swiper {
  width: 100%;
  height: 100%;
}
.swiper-one{
  background-color: #9C92AC;
  background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100%25' height='100%25' viewBox='0 0 800 400'%3E%3Cdefs%3E%3CradialGradient id='a' cx='396' cy='281' r='514' gradientUnits='userSpaceOnUse'%3E%3Cstop offset='0' stop-color='%237F58AC'/%3E%3Cstop offset='1' stop-color='%239C92AC'/%3E%3C/radialGradient%3E%3ClinearGradient id='b' gradientUnits='userSpaceOnUse' x1='400' y1='148' x2='400' y2='333'%3E%3Cstop offset='0' stop-color='%23DFDBE5' stop-opacity='0'/%3E%3Cstop offset='1' stop-color='%23DFDBE5' stop-opacity='0.5'/%3E%3C/linearGradient%3E%3C/defs%3E%3Crect fill='url(%23a)' width='800' height='400'/%3E%3Cg fill-opacity='0.4'%3E%3Ccircle fill='url(%23b)' cx='267.5' cy='61' r='300'/%3E%3Ccircle fill='url(%23b)' cx='532.5' cy='61' r='300'/%3E%3Ccircle fill='url(%23b)' cx='400' cy='30' r='300'/%3E%3C/g%3E%3C/svg%3E");
  background-size: cover;
  background-position: center center;
}
.swiper-slide {
  text-align: center;
  font-size: 18px;
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