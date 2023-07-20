<script setup>

</script>

<template>
  <div class="product">
    <ul class="pro_wrap w1280">
      <li class="pro_list">
        <div class="pro_img">
          <div class="book_card card_hover">
              <div class="book_card_inner"></div>
              <div color="linear-gradient(180deg, #408DD5 0%, #630B8C 100%)" class="book_card_shadow"></div>
          </div>
        </div>
        <div class="pro_intro">
          <h3>我们的产品是巴啦啦小魔仙</h3>
          <p>古娜拉黑暗之神,古娜拉黑暗之神,波希和皮普之红球,波希是个乖宝宝</p>
          <p>古娜拉黑暗之神,古娜拉黑暗之神,波希和皮普之红球,波希是个乖宝宝</p>
        </div>
      </li>
      <li class="pro_list">
        <div class="pro_img">
          <div class="book_card card_hover">
              <div class="book_card_inner"></div>
              <div color="linear-gradient(180deg, #408DD5 0%, #630B8C 100%)" class="book_card_shadow"></div>
          </div>
        </div>
        <div class="pro_intro">
          <h3>我们的产品是巴啦啦小魔仙</h3>
          <p>古娜拉黑暗之神,古娜拉黑暗之神,波希和皮普之红球,波希是个乖宝宝</p>
          <p>古娜拉黑暗之神,古娜拉黑暗之神,波希和皮普之红球,波希是个乖宝宝</p>
        </div>
      </li>
    </ul>
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#F2F6FF" fill-opacity="1" d="M0,160L60,170.7C120,181,240,203,360,186.7C480,171,600,117,720,117.3C840,117,960,171,1080,202.7C1200,235,1320,245,1380,250.7L1440,256L1440,0L1380,0C1320,0,1200,0,1080,0C960,0,840,0,720,0C600,0,480,0,360,0C240,0,120,0,60,0L0,0Z"></path></svg>
  </div>
    
</template>
<style>
.product{
  height: 100%;
  margin-top: -150px;
}
.pro_wrap{
}
.pro_list{
  display: grid;
  grid-template-columns: 33% auto ;
  margin-bottom: 120px;
}
.pro_list h3 {
  font-size: 30px;
  text-emphasis-style: '`';
  text-emphasis-position: under;
}
.pro_intro {
  filter: drop-shadow(0 0 2em #5bc0ef63);
  cursor: pointer;
  background: rgba(255, 255,255, .6);
  list-style: none;
  height: 300px;
  margin: 0 0 40px 0;
  border-radius: 30px;
  padding: 36px;
}
.pro_wrap{
  width: 100%;
}
.book_card{
  position: relative;
}
.book_card .book_card_inner:hover {
    box-shadow: rgba(24, 32, 79, 0.25) 0px 100px 100px, rgba(255, 255, 255, 0.5) 0px 0px 0px 0.5px inset;
    transform: translateY(-3px);
}
.card_hover > div {
    transition: all 0.8s cubic-bezier(0.075, 0.82, 0.165, 1) 0s;
}
.book_card_inner {
    position: relative;
    width: 240px;
    height: 280px;
    backdrop-filter: blur(40px);
    border-radius: 0px 30px 40px 40px;
    padding: 20px;
    background: rgba(255, 255, 255, 0.3);
    /* box-shadow: rgba(24, 32, 79, 0.25) 0px 40px 80px, rgba(255, 255, 255, 0.5) 0px 0px 0px 0.5px inset; */
    z-index: 1;
}
.card_hover > div {
    transition: all 0.8s cubic-bezier(0.075, 0.82, 0.165, 1) 0s;
}

.book_card_shadow {
    position: absolute;
    width: 220px;
    height: 280px;
    background: linear-gradient(rgb(64, 141, 213) 0%, rgb(99, 11, 140) 100%);
    border-radius: 0px 40px 40px;
    transform: skewY(8deg);
    transform-origin: left top;
    top: 0px;
}
.book_card:hover .book_card_shadow {
    transform: skewY(15deg);
    width: 200px;
}
</style>