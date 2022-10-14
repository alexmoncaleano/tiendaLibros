<script setup>
  import tituloComponent from "./components/tituloComponent.vue";
  import menuComponent from "./components/menuComponent.vue";
  import pieComponent from "./components/pieComponent.vue";
</script>
<script>
	  import { defineComponent } from "vue";
	  export default defineComponent({
	    name: "app",
	    components: {},
	  });
	</script>
<template>
    <div class="container-xl" id="marco">
	    <div class="row" id="titulo"><tituloComponent /></div>
	    <div class="row" id="central">
	      <!--<div id="menuNav"><menuComponent /></div>-->
	      <div id="contenido"><router-view /></div>
	    </div>
	    <div class="row" id="pie"><pieComponent /></div>
	  </div> 

</template>




