<!-- c'est le composant Root. Il contient toute notre application -->
<template>
  <div>
    <meteo></meteo>
  </div>
</template>



<script>

import meteo from './components/Meteo.vue'

export default {

  components: {
    'meteo' : meteo
  }
}

</script>



<style>
body {
  background: #8360c3;  /* fallback for old browsers */
  background: -webkit-linear-gradient(to right, #2ebf91, #8360c3);  /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(to right, #2ebf91, #8360c3); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}
</style>

