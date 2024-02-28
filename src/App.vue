<template>
  <div class="app">
   <img class="logo" alt="Vue logo" src="./assets/logo.png">

    <h1 class="h1">Remember me</h1>
   <p>Запомни и открой все зеленые клетки</p>

    <Board/>
  </div>
</template>

<script>
import Board from "@/components/Board";
export default {
  name: 'App',
  components: {
  Board
  }
}
</script>

<style scoped>
.app{
  font-family: "Times New Roman", Georgia, Serif;
  text-align: center;
  margin-top: 40px;
}
.logo{
width: 200px;
}

</style>
