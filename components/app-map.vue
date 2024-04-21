<template>
  <div class="app-map">
    <iframe src="https://yandex.ru/map-widget/v1/?um=constructor%3A80a86e6fe40a7510543e39bb7e41ef1d1396b01a542f7c1de47ea29cca0d2b50&amp;source=constructor" width="100%" height="800" frameborder="0"></iframe>
    <div class="app-map-flex">
      <app-map-item text="haval Авторусь подольск" text1="Подольск, проспект Юных Ленинцев, д. 1И, МЦД Селикатная" text2="+7 (495) 492-09-45" text3="info@haval-avtoruss.ru" text4="Отдел продаж" text5="ежедневно 9-21" text6="Сервис" text7="ежедневно 8—21"></app-map-item>
      <app-map-item text="haval Авторусь лосиный остров" text1="Москва, Ярославское ш., владение 2В, строение 3 (95 км МКАД)" text2="+7 (495) 432-59-97" text3="info-los@haval-avtoruss.ru" text4="Отдел продаж" text5="ежедневно 9—21" text6="Сервис" text7="ежедневно 8—21"></app-map-item>
    </div>
  </div>
</template>

<script lang="ts">
export default {
  name: "app-map",
  props: [],
  setup(props: any){
    return{

    }
  }
}
</script>

<style lang="scss">
.app-map{
  position: relative;
  width: 100%;
  background: var(--app-white);
}
.app-map-flex{
  position: absolute;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  top: 450px;
}
@media only screen and (max-width: 620px) {
  .app-map-flex{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    position: static;
  }
  .app-map{
    top: 100px;
  }
}
</style>