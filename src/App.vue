<template>
  <div id="app">
    <VmBlockquote texte="Mon text"></VmBlockquote>
    <VmHeading type="1" texte="Mon titre"></VmHeading>

    <VmBoutton texte='btn 1' ></VmBoutton>
    <VmBoutton texte='btn 2' outline></VmBoutton>
    <VmBoutton texte='btn 3' clear></VmBoutton>
  </div>
</template>

<script>
import VmBlockquote from "./components/VmBlockquote";
import VmHeading from "./components/VmHeading";
import VmBoutton from "./components/VmBoutton";

export default {
  name: "app",
  components: {
    VmBlockquote,
    VmHeading,
    VmBoutton
  }
};
</script>

<style></style>
