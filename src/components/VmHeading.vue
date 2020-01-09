<template>
  <div>
    <!-- <h1 v-if="type === '1'">{{ texte }}</h1> -->
        
<!-- 
    <h2 v-if="type === '2'">{{ texte }}</h2>
    <h3 v-if="type === '3'">{{ texte }}</h3>
    <h4 v-if="type === '4'">{{ texte }}</h4>
    <h5 v-if="type === '5'">{{ texte }}</h5>
    <h6 v-if="type === '6'">{{ texte }}</h6> -->
    <component v-if="type <= '6'" :is="elementAAficher">{{ texte }}</component>
     <button v-else>Autre</button>
  
  </div>
</template>

<script>
export default {
  name: "VmHeading",
  props: ["texte", "type"],
  computed: {
    elementAAficher() {
    //   return `h${this.type}`;
      return "h" + this.type;
    }
  }
};
</script>

<style></style>
