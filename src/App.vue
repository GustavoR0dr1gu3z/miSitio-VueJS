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
body{
background: #00C9FF;  /* fallback for old browsers */
background: -webkit-linear-gradient(to right, #92FE9D, #00C9FF);  /* Chrome 10-25, Safari 5.1-6 */
background: linear-gradient(to right, #92FE9D, #00C9FF); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */

}

</style>
