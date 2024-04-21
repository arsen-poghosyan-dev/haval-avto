<template>
  <div class="app-car">
    <div class="app-car-info">
      <div>
        <h1> {{name}} </h1>
      </div>

      <div class="app-car-body">

        <div class="app-car-body--1">
          <h4>{{advertisingText1}}</h4>
          <h4>{{advertisingText2}}</h4>
          <app-button color="black">узнать цену</app-button>
        </div>

        <div class="app-car-body--2">
          <h4>{{advertisingText3}}</h4>
          <h4>{{advertisingText4}}</h4>
          <app-button color="border">выбрать автомобиль</app-button>
        </div>

      </div>

      <div>
        <h4>тест-драйв ></h4>
      </div>

    </div>

    <div class="app-car-image">
      <img src="/Img.png" alt="">
<!--      <img src="/Img (1).png" alt="">-->
    </div>

  </div>
</template>

<script lang="ts">
export default {
  name: "app-car",
  props: ["name", "advertisingText1","advertisingText2","advertisingText3", "advertisingText4"],
  setup(props: any){
    const name = props.name
    const advertisingText1 = props.advertisingText1
    const advertisingText2 = props.advertisingText2
    const advertisingText3 = props.advertisingText3
    const advertisingText4 = props.advertisingText4

    return {
      name,
      advertisingText1,
      advertisingText2,
      advertisingText3,
      advertisingText4,
    }
  }
}
</script>

<style lang="scss">
.app-car{
  display: flex;
  justify-content: center;
  align-items: center;
  border: 1px solid;
  .app-car-info{
    width: 60%;
    padding: 30px;

  }
  .app-car-image{
    width: 40%;
  }
}
.app-car-body{
  display: flex;
  flex-direction: row;
  //justify-content: flex-start;
  .app-car-body--1 {
    width: 50%;
    //margin-left: 45px;
  }
  .app-car-body--2 {
    width: 50%;
    //margin-left: 45px;
  }
}

@media only screen and (max-width: 620px) {
  .app-car{
    display: flex;
    justify-content: start;
    align-items: start;
    flex-direction: column-reverse;
    .app-car-info{
      width: 100%;
      //background: orange;
      padding: 0;
    }
    .app-car-image{
      width: 100%;
      img{
        width: 100%;
      }
    }
  }

  .app-car-body{
    width: 100%;

    flex-direction: column;
    justify-content: center;

    .app-car-body--1 {
      width: 100%;

    }
    .app-car-body--2{
      width: 100%;
      margin-left: 0;

    }
  }
}
</style>