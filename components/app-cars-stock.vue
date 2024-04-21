<template>
  <div class="cars-text">
    <span> {{ cars }}</span>
  </div>
</template>
<script  lang="ts">
export default {
  name: "app-cars-stock",
  props: ['cars'],
  setup(props: any) {
    const cars = props.cars
    return{
      cars,
    }
  }
}
</script>


<style lang="scss" scoped>
.cars-text{
  padding: 18px;
}
</style>