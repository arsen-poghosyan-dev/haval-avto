<template>
  <div class="app-map-item">

    <div>
      <h1>{{ text}}</h1>
      <span>{{text1}}</span>
    </div>

    <div class="app-map-item1">

      <div>
        <h2>{{ text2 }}</h2>
        <h2>{{text3}}</h2>
      </div>

      <div>
        <div>
          <span>{{text4}}</span>
          <h2>{{text5}}</h2>
        </div>
        <span>{{text6}}</span>
        <h2>{{text7}}</h2>
      </div>

    </div>
  </div>
</template>

<script lang="ts">
export default {
  name: "app-map",
  props: ['text', 'text1', 'text2', 'text3', 'text4','text5','text6','text7'],
  setup(props: any){
    const text = props.text
    const text1 = props.text1
    const text2 = props.text2
    const text3 = props.text3
    const text4 = props.text4
    const text5 = props.text5
    const text6 = props.text6
    const text7 = props.text7

    return{
      text,
      text1,
      text2,
      text3,
      text4,
      text5,
      text6,
      text7,
    }
  }
}
</script>

<style lang="scss">
.app-map-item{
  width: 50%;
  margin: 80px;
  padding: 25px;
  background: var(--app-black);
  color: var(--app-white);
}
.app-map-item1{
  display: flex;
  justify-content: space-between;
  align-items: center;
}
@media only screen and (max-width: 620px) {
  .app-map-item{
    width: 100%;
    margin: 10px;
  }
}
</style>