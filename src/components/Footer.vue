<script setup>
import { ref } from "vue";
const year = ref("2025");
const href = ref("https://scrimba.com");

year.value = "2014";
</script>

<template>
  <footer>
    Created by
    <a target="_blanks" :href>
      <span>Professor Pickle</span> &copy; {{ year }}
    </a>
  </footer>
</template>

<style scoped>
/* FOOTER CSS */
footer {
  position: fixed;
  margin: 0 auto;
  bottom: 0;
  text-align: center;
  color: #ccd6d9;
  padding-bottom: 20px;
}

span {
  font-family: cursive;
}

a {
  color: white;
}
</style>
