<template>
  <div>
    <app-heder></app-heder>

   <div class="app-services">
     <div class="app-services-item">
       <app-service text1="оцени автомобиль" text2="и получи выгоду"></app-service>
     </div>
     <div class="app-services-item">
       <app-service text1="спецпредложения" text2="месяца"></app-service>
     </div>
     <div class="app-services-item">
       <app-service text1="рассчитать" text2="кредит"></app-service>
     </div>
     <div class="app-services-item">
       <app-service text1="записаться" text2="на сервис"></app-service>
     </div>
   </div>
    <app-title title="МОДЕЛИ HAVAL"></app-title>
    <div class="app-services-title">
      <app-car name="Haval jolion" advertising-text1="5 лет поддержки" advertising-text2="Гарантия лучшей оценки trade-in " advertising-text3="Зимняя резина в подарок " advertising-text4="Привилегии на сервисное обслуживание "></app-car>
      <app-car name="Haval m6" advertising-text1="5 лет поддержки" advertising-text2="Гарантия лучшей оценки trade-in "  advertising-text3="Зимняя резина в подарок " advertising-text4="Привилегии на сервисное обслуживание "></app-car>
      <app-car name="Haval F7" advertising-text1="5 лет поддержки" advertising-text2="Гарантия лучшей оценки trade-in "  advertising-text3="Зимняя резина в подарок " advertising-text4="Привилегии на сервисное обслуживание "></app-car>
      <app-car name="Haval F7X" advertising-text1="5 лет поддержки" advertising-text2="Гарантия лучшей оценки trade-in "  advertising-text3="Зимняя резина в подарок " advertising-text4="Привилегии на сервисное обслуживание "></app-car>
      <app-car name="Haval dargo" advertising-text1="5 лет поддержки" advertising-text2="Гарантия лучшей оценки trade-in "  advertising-text3="Зимняя резина в подарок " advertising-text4="Привилегии на сервисное обслуживание "></app-car>
      <app-car name="Haval POER KING KONG" advertising-text1="5 лет поддержки" advertising-text2="Гарантия лучшей оценки trade-in "  advertising-text3="Зимняя резина в подарок " advertising-text4="Привилегии на сервисное обслуживание "></app-car>
      <app-car name="Haval dargo X" advertising-text1="5 лет поддержки" advertising-text2="Гарантия лучшей оценки trade-in "  advertising-text3="Зимняя резина в подарок " advertising-text4="Привилегии на сервисное обслуживание "></app-car>
      <app-car name="Haval POER " advertising-text1="5 лет поддержки" advertising-text2="Гарантия лучшей оценки trade-in "  advertising-text3="Зимняя резина в подарок " advertising-text4="Привилегии на сервисное обслуживание "></app-car>
    </div>

      <app-title title="Автомобили в наличии"></app-title>

    <div class="app-cars-stock">

        <select class="app-cars">
          <option>
            <app-cars-stock cars="Выберите модель"></app-cars-stock>
          </option>
        </select>

      <select class="app-cars">
        <option>
          <app-cars-stock cars="Комплектация"></app-cars-stock>
        </option>
      </select>

      <select class="app-cars">
        <option>
          <app-cars-stock cars="Двигатель"></app-cars-stock>
        </option>
      </select>

      <div class="app-cars">
        <app-button class="app-cars-button" color="black">в кредит</app-button>
      </div>

    </div>

    <div class="app-cars-price-items">

      <div class="app-cars-price-item">
        <app-cars-price text="Haval F7X" equipment="Комплектация" engine="Двигатель" driveunit="Привод" elite="Elite" power="1.5 DCT (150 л.с.)" wd="2 WD"></app-cars-price>
      </div>

      <div class="app-cars-price-item">
        <app-cars-price text="Haval F7X" equipment="Комплектация" engine="Двигатель" driveunit="Привод" elite="Elite" power="1.5 DCT (150 л.с.)" wd="2 WD"></app-cars-price>
      </div>

      <div class="app-cars-price-item">
        <app-cars-price text="Haval F7X" equipment="Комплектация" engine="Двигатель" driveunit="Привод" elite="Elite" power="1.5 DCT (150 л.с.)" wd="2 WD"></app-cars-price>
      </div>

      <div class="app-cars-price-item">
        <app-cars-price text="Haval F7X" equipment="Комплектация" engine="Двигатель" driveunit="Привод" elite="Elite" power="1.5 DCT (150 л.с.)" wd="2 WD"></app-cars-price>
      </div>

      <div class="app-cars-price-item">
        <app-cars-price text="Haval F7X" equipment="Комплектация" engine="Двигатель" driveunit="Привод" elite="Elite" power="1.5 DCT (150 л.с.)" wd="2 WD"></app-cars-price>
      </div>

      <div class="app-cars-price-item">
        <app-cars-price text="Haval F7X" equipment="Комплектация" engine="Двигатель" driveunit="Привод" elite="Elite" power="1.5 DCT (150 л.с.)" wd="2 WD"></app-cars-price>
      </div>

      <div class="app-cars-price-item">
        <app-cars-price text="Haval F7X" equipment="Комплектация" engine="Двигатель" driveunit="Привод" elite="Elite" power="1.5 DCT (150 л.с.)" wd="2 WD"></app-cars-price>
      </div>

      <div class="app-cars-price-item">
        <app-cars-price text="Haval F7X" equipment="Комплектация" engine="Двигатель" driveunit="Привод" elite="Elite" power="1.5 DCT (150 л.с.)" wd="2 WD"></app-cars-price>
      </div>

      <app-title title="Смотреть еще >"></app-title>

    </div>


    <div>
      <app-advantages text="Преимущества"></app-advantages>
    </div>

    <div>
      <app-map></app-map>
    </div>

    <div class="app-store">
      <app-store></app-store>
    </div>

  </div>
</template>

<script  lang="ts">
export default {
  setup(){

   return{

   }
  }
}
</script>

<style lang="scss" scoped>
.app-services{
  display: flex;
  justify-content: center;
  align-items: center;
}
.app-services-item{
  width: 25%;
  padding: 5px;
}
.app-cars-stock{
  display: flex;
  justify-content: center;
  align-items: center;
}
.app-cars{
  width: 25%;
  height: 60px;
  background: unset;
  font-size: 18px;
  margin: 15px;
  .app-cars-button{
    width: 85%;
    height: 60px;
    &:before{
      width: 70px;
      height: 60px;
      right: -35px;
    }
  }
}
.app-cars-price-items{
  width: 100%;
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  align-items: center;
}
.app-cars-price-item{
  width: 25%;
}
@media only screen and (max-width: 620px) {
  .app-services{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }
  .app-services-item{
    width: 100%;
    padding: 0;
  }
  .app-cars-stock{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column-reverse;
  }
  .app-cars{
    width: 100%;
  }
  .app-cars-price-items{
    width: 100%;
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    align-items: center;
  }
  .app-cars-price-item{
    width: 100%;
  }
}


</style>