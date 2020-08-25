<template>
  <div class="chip" v-if="value != 0">{{ value }}</div>
</template>

<script>
  export default {
    name: "Chip",
    props: {
      value: Number
    }
  }
</script>

<style>
  .chip {
    /*transform: rotate(360deg);*/
    text-align: center;
    vertical-align: middle;
    width: 23px;
    height: 23px;
    position: absolute;
    top: calc(50% - 10px);
    left: calc(50% - 10px);
    display: inline;
    background: url("../assets/chip.png") no-repeat;
    background-size: 100% 100%;
    color: white;
    border-radius: 50%;
  }
</style>
