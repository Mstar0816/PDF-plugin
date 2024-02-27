<template>
  <PdfApp style="height: 90vh" pdf="/"></PdfApp>
</template>

<script>
import PdfApp from "vue3-pdf-app";
import "vue3-pdf-app/dist/icons/main.css";
export default {
  name: "App",
  components: {
    PdfApp,
  },
};
</script>


<!-- <style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style> -->
