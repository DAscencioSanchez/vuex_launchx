<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Contador/>
    <contadorCuadrado/>
    <botones/>
  </div>
</template>

<script>

import Contador from "../components/Contador.vue"
import contadorCuadrado from "../components/contadorCuadrado.vue"
import Botones from "../components/Botones.vue"


export default {
  name: 'HomeView',
  components: {
    Contador,
    contadorCuadrado,
    Botones,
  }
}

</script>

<style>
  div{
    margin-bottom:10px;
  }
  .contador{
    font-size:80px;
  }
  .botones button {
    font-size: 40px;
    width:100px;
    margin:20px;
  }
  .cuadrado{
    font-size:25px;
  }

</style>