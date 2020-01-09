<template>

  <button v-bind:class="{'button-outline' : outline, 'button-clear' : clear}" @click="boutonClique" >{{texte}}</button>
  

</template>

<script>
export default {
  
  name: "VmBoutton",
  props: {
      texte:String,
      
      outline:Boolean, 

      clear:Boolean, 
     
  },

  
  methods: {
      boutonClique(evenement){
          this.$emit('click',evenement)
      }
  }
};
</script>

<style></style>
