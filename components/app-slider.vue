<template>
  <div class="app-slider">
    <img  style="width: 100%" src="/slider.png">
    <div class="app-slider--info">
      <span class="app-slider--info--text1">МЕСЯЦ</span>
      <span class="app-slider--info--text2">HAVAL M6 И DARGO</span>
      <span class="app-slider--info--text3">- Выгода 200 000 ₽</span>
      <span class="app-slider--info--text3">- Зимняя резина в подарок</span>
      <span class="app-slider--info--text3">- Кредит от 0.01%</span>
      <app-button class="app-slider--info-button">оставить заявку</app-button>
    </div>



    <div class="app-slider--timer">

      <div class="app-slider--timer--item">
        <div class="app-slider--timer--item--1">
          <span>Срок действия выгод:</span>
        </div>
      </div>

      <div class="app-slider--timer--item">
        <div class="app-slider--timer--item--2">
          <span class="app-slider--timer--item--number">14 :</span>
          <span class="app-slider--timer--item--date">дней</span>
        </div>
        <div class="app-slider--timer--item--2">
          <span class="app-slider--timer--item--number">06 :</span>
          <span class="app-slider--timer--item--date">часов</span>
        </div>
        <div class="app-slider--timer--item--2">
          <span class="app-slider--timer--item--number">14 :</span>
          <span class="app-slider--timer--item--date">минут</span>
        </div>
        <div class="app-slider--timer--item--2">
          <span class="app-slider--timer--item--number">33</span>
          <span class="app-slider--timer--item--date">секунд</span>
        </div>
      </div>

      <div class="app-slider--timer--item">
        <app-button>Узнать цены по предзаказу</app-button>
      </div>

    </div>

  </div>
</template>

<script lang="ts">
export default {
  name: "app-slider",
  setup(){

    return{

    }
  }
}
</script>

<style lang="scss">
.app-slider {
  position: relative;
}
.app-slider--info{
  top: 80px;
  left: 80px;
  position: absolute;
  color: var(--app-white);
  width: 350px;
  span{
    display: block;
  }
  .app-slider--info--text1{
    font-size: 25px;
  }
  .app-slider--info--text2{
    font-size: 35px;
    margin-top: 35px;
    margin-bottom: 35px;
  }
  .app-slider--info--text3{
    font-size: 22px;
  }
}
.app-slider--timer{
  position: absolute;
  display: flex;
  align-items: center;
  flex-direction: row;
  bottom: 0;
  width: 100%;
  background: var(--app-black);
  color: #ffffff;
}
.app-slider--timer--item {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 33.3333%;
}
.app-slider--timer--item--1 span{
  font-size: 30px;
  margin-left: 80px;
}
.app-slider--timer--item--2{
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.app-slider--timer--item--number{
  font-size: 35px;
  margin-left: 10px;
}
.app-slider--timer--item--date{
  font-size: 15px;
}
@media only screen and (max-width: 620px) {
  .app-slider--info{
    position: static;
    width: 100%;
    color: var(--app-black);
  }
  .app-slider--timer{
    position: static;
    width: 100%;
    height: 250px;
    flex-direction: column;
  }
  .app-slider--timer--item {
    width: 100%;
    justify-content: left;
    margin-top: 20px
  }
  .app-slider--timer--item--1 span {
    margin-left: 10px;
  }
  .app-slider--info-button{
    background: var(--app-black);
  }
}
</style>