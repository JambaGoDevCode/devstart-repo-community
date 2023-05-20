<template>
  <div class="bg">
    <Calculator/>
  </div>
</template>

<script>
import Calculator from './components/Calculator';
export default {
  components: {
    Calculator
  }
}
</script>

<style >
  .bg {
    background-color: #272727;
    width: 100vw;
    height: 100vh;
    padding: 2rem;
  }
  html, body {
      font-family: 'Sora', sans-serif;
  }
</style>