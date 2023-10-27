<template>
  <div>
    <p class="square1"></p>
    <p class="square2"></p>
    <p class="square3"></p>
    <p class="square4"></p>
    <p class="square5"></p>
    <p class="square6"></p>
    <Lol/>
  </div>
</template>
<script>
import Lol from './components/lol.vue';
export default {
    components: { Lol }
}
</script>
<style>
  .square1{
    width: 40px;
    height: 40px;
    background-color: red;

  }
  .square2{
    width: 50px;
    height: 50px;
    background-color: green;
  }
  .square3{
    width: 60px;
    height: 60px;
    background-color: blue;
  }
  .square4{
    width: 70px;
    height: 70px;
    background-color: orange;

  }
  .square5{
    width: 80px;
    height: 80px;
    background-color: purple;

  }
  .square6{
    width: 90px;
    height: 90px;
    background-color: black;

  }
</style>