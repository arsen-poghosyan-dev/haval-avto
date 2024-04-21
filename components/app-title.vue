<template>
  <div class="app-title">
    <h1>{{title}}</h1>
  </div>
</template>

<script lang="ts">
export default {
  name: "app-title",
  props: ["title"],
  setup(props: any){
    const title = props.title
    return{
      title,
    }
  }
}
</script>

<style lang="scss">
.app-title{
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
</style>