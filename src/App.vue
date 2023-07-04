<script setup>
  import { ref } from 'vue';

  const masterklass = ref("masterKlass");

</script>


<template>
  <div>
    > Hello {{ masterklass }} !
  </div>
</template>

<style>
html {
  background: rgb(16, 16, 17);
  color: rgb(111, 224, 135);
  font-family: 'Courier New', Courier, monospace;
}
</style>