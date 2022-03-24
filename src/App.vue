<template>
  <div id="nav">
    <Navbar/>
    <router-view/>
  </div>
</template>


<script>

// 1er Paso: Importar el componente Navbar
import Navbar from './components/Navbar.vue'

  // 2do Paso: Crear el componente Navbar
export default {
    components: {
      Navbar,
    },
  }

</script>



<style>

</style>
