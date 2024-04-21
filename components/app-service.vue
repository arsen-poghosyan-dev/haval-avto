<template>
  <div class="app-service">
    <div class="app-service--item--icon"></div>
    <span>{{ text1 }}</span>
    <span>{{ text2 }}</span>
  </div>
</template>

<script lang="ts">
export default {
  name: "app-service",
  props: ['text1', "text2"],
  setup(props: any){
    const text1 = props.text1
    const text2 = props.text2

    // {text1:12345}
    return{
      text1,
      text2,
    }
  }
}
</script>

<style scoped>
.app-service{
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  width: 100%;
  margin-top: 30px;
  padding: 15px;
  background: var(--app-grey);
  span {
    width: 100%;
    display: block;
  }
}
.app-service--item--icon{
  width: 30px;
  height: 30px;
  border-radius: 50%;
  background: var(--app-green);
}
</style>