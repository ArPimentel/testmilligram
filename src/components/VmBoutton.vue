<template>

  <button v-bind:class="{'button-outline' : outline, 'button-clear' : clear}" >{{texte}}</button>
  

</template>

<script>
export default {
  
  name: "VmBoutton",
  props: {
      texte:String,
      
      outline:Boolean, 

      clear:Boolean, 
     
  },
  
  computed: {

  }
};
</script>

<style></style>
