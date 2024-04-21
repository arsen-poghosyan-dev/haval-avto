<template>
  <div class="app-cars-price">
    <img src="https://s3-alpha-sig.figma.com/img/3e1d/2e31/44bee2eb43d21ae145805335e39c9f15?Expires=1714348800&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=Bsh7mqVuAO-ORujUcQiDKY2uku2oVuv6kkvXmeQ8F7K76v8ZMk3a5iAMJceH7W7il4bws5ppvTPo5y44PhRs3PYiUrDtUKVzJn3MNGL-JFRGFOLy1NM-XbzX0Li4TBO9MD4JQ3R5nuk91scwxcdlGTbHJd~l2vKUdapVlStJSA22hvdUyRFNs5XbSm~uRiuWr3ho8v4b6MRWzkgad8zWC78w1~LWwDxaZ6bcqEtxKrwmo7TVIkHjHgkA2BVdjNQ4usyWbxReX-4Ew0jBkuJb9L8bVq5cCrxZFq8cnrgQQB8NxZ5VRhDPracTy8hEoxrz7q94eUN4HrAT7cMB3nA7sA__" alt="">
    <h2>{{text}}</h2>

    <div class="app-car-price">

      <div class="app-car-price1">
        <span>{{ equipment }}</span>
        <span>{{ engine }}</span>
        <span>{{ driveunit }}</span>
      </div>

      <div class="app-car-price2">
        <span>{{ elite }}</span>
        <span>{{ power }}</span>
        <span>{{ wd }}</span>
      </div>
    </div>

    <div class="app-cars-app-buttone">
      <app-button class="app-cars-app-button" color="black">Получить лучшую цену</app-button>
    </div>
  </div>
</template>
<script  lang="ts">
export default {
  name: "app-cars-price",
  props: ['text','equipment','engine','driveunit','elite','power','wd'],
  setup(props: any) {
    const text = props.text
    const equipment = props.equipment
    const engine = props.engine
    const driveunit = props.driveunit
    const elite = props.elite
    const power = props.power
    const wd = props.wd

    return{
      text,
      equipment,
      engine,
      driveunit,
      elite,
      power,
      wd,

    }
  }
}
</script>


<style lang="scss" scoped>
.app-cars-price{
  border: 1px solid;
  margin: 15px;
  img{
    width: 100%;
  }
  h2{
    margin: 15px;
  }
}
.app-car-price{
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin: 15px;
}
.app-car-price1{
  display: flex;
  justify-content: start;
  align-items: start;
  flex-direction: column;
  span{
    padding-top: 10px;
  }
}
.app-car-price2{
  display: flex;
  justify-content: start;
  align-items: start;
  flex-direction: column;
  span{
    padding-top: 10px;
    font-weight: 600;
  }
}
.app-cars-app-button{
  width: 85%;
  margin: 10px;
}

</style>