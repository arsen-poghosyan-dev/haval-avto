<template>
  <div class=" app-advantages-item">

    <div class="app-advantages-item--number"> {{ number }}</div>

    <div>
      <h2>{{text}}</h2>
      <p>{{text1}}</p>
    </div>

  </div>
</template>

<script lang="ts">
export default {
  name: "app-advantages-item",
  props: ['text','text1','number'],
  setup(props: any){
    const text = props.text
    const text1 = props.text1
    const number = props.number
    return{
      text,
      text1,
      number,
    }
  }
}
</script>

<style lang="scss">

.app-advantages-item{
  width: 50%;
  height: 180px;
  border: 1px solid var(--app-white);
  color: var(--app-white);
  padding: 15px;
  transition: all 300ms;
  p{
    font-size: 18px;
    font-weight: 600;
  }
}
.app-advantages-item:hover{
  background: var(--app-aquamarine);
  color: var(--app-white);
  transition: all 300ms;
}
.app-advantages-item--number{
  display: flex;
  justify-content: flex-end;
  align-items: flex-end;
  font-size: 24px;
  font-weight: 600;
}
@media only screen and (max-width: 620px) {
  .app-advantages-item{
    width: 100%;
    color: var(--app-black);
    border: 1px solid var(--app-black);
    margin-top: 0;
  }
}
</style>