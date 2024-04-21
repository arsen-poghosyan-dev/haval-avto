<template>
  <button class="app-button" :class="color">
    <slot></slot>
  </button>
</template>

<script lang="ts">
export default {
  name: "app-button",
  props: ["color"],
  setup(props: any){
    const color = props.color

    return{
      color,
    }
  }
}
</script>

<style lang="scss">

.app-button{
  width: 300px;
  height: 45px;
  font-size: 19px;
  position: relative;
  outline: none;
  border: none;
  border-top: 1px solid var(--app-black)!important;
  border-bottom: 1px solid var(--app-black)!important;
  border-left: 1px solid var(--app-black)!important;
  background: var(--app-white);
  border: unset;
  &.black {
    background: var(--app-black);
    color: var(--app-white);
  }
  &.white {
    background: var(--app-white);
    color: var(--app-black);
  }
  &.border{
    background: unset;
    color: var(--app-black);
  }

  &:before{
    content: "";
    position: absolute;
    top: -1px;
    border-right: 1px solid black;
    border-top: 1px solid black;
    right: -27px;
    width: 53px;
    height: 44px;
    background: inherit;
    transform: skew(-50deg);
  }
}

</style>