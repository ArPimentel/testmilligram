<template>
  <div id="app">
    <VmBlockquote texte="Mon text"></VmBlockquote>
    <VmHeading type="8" texte="Mon titre"></VmHeading>
  </div>
</template>

<script>
import VmBlockquote from "./components/VmBlockquote"
import VmHeading from "./components/VmHeading"
export default {
  name: 'app',
  components:{
    VmBlockquote,
    VmHeading
  }
}
</script>

<style>

</style>
