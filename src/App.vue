<template>
  <div id="app">
     <h1>PaginaChris</h1>
     <PaginaChris />
  </div>
</template>

<script>
import PaginaChris from "./main/paginaChris"
export default {
    components: { PaginaChris }
}
</script>

<style>
body{
    margin: 0;
}
#app{
    display: flex;
    flex-direction: column;
    height: 100vh;
    justify-content: center;
    align-items: center;
    text-align: center;

    color: #fff;
    background: linear-gradient(to right, rgb(10,37,156), rgb(253,50,88));
}
</style>