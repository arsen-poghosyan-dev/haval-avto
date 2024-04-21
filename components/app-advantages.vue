<template>
  <div class="app-advantages">
    <img src="/img2.png" style="width: 100%;">

    <div class="app-advantages-text">
      <h1>{{text}}</h1>
    </div>

    <div class="app-advantages-items">

      <app-advantages-item text="приятно" text1="Удобное местоположение с бесплатной парковкой" number="01 /"></app-advantages-item>
      <app-advantages-item text="професионально" text1="Удобное местоположение с бесплатной парковкой" number="02 /"></app-advantages-item>
      <app-advantages-item text="Быстро" text1="Удобное местоположение с бесплатной парковкой" number="03 /"></app-advantages-item>
      <app-advantages-item text="удобно" text1="Удобное местоположение с бесплатной парковкой" number="04 /"></app-advantages-item>
      <app-advantages-item text="впечатляюще" text1="Удобное местоположение с бесплатной парковкой" number="05 /"></app-advantages-item>
      <app-advantages-item text="надежно" text1="Удобное местоположение с бесплатной парковкой" number="06 /"></app-advantages-item>
      <app-advantages-item text="безопасно" text1="Удобное местоположение с бесплатной парковкой" number="07 /"></app-advantages-item>
      <app-advantages-item text="выгодно" text1="Удобное местоположение с бесплатной парковкой" number="08 /"></app-advantages-item>

    </div>


  </div>
</template>

<script lang="ts">
export default {
  name: "app-advantages",
  props: ['text','text1'],
  setup(props: any){
    const text = props.text
    const text1 = props.text1
    return{
      text,
      text1,
    }
  }
}
</script>

<style lang="scss">
.app-advantages{
  position: relative;
  top: 50px;
}
.app-advantages-text{
  position: absolute;
  top: 5px;
  color: var(--app-white);
  margin: 30px;
}
.app-advantages-items{
  position: absolute;
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  width: 40%;
  top: 100px;
  margin: 30px;
}
@media only screen and (max-width: 620px) {
  .app-advantages{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    width: 100%;
  }
  .app-advantages-items{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    width: 100%;
    position: static;
    margin: 0;
  }
  .app-advantages-text{
    position: static;
    color: var(--app-black);
    margin: 0;
    display: flex;
    justify-content: flex-start;
    align-items: flex-start;
    flex-direction: column;

  }
}
</style>