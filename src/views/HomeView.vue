<script setup lang="ts">
import NavbarHeader from "../components/NavbarHeader.vue"
</script>

<template>
  <header>
    <NavbarHeader />
  </header>
  <main>
    <div id = "test">
      hi
    </div>
  </main>
</template>



<style scoped>
header {
  position:absolute;
  top: 0%;
  left: 0%;
}

#test {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

</style>
