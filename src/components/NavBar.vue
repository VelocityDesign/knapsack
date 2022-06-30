<script>
import "@fontsource/plus-jakarta-sans"
export default {
  name: "NavBar",
};
</script>

<template>
  <div id="navbar-container">
    <span id="wordmark">knapsack</span>
  </div>
</template>

<style scoped>
  #navbar-container {
    display: flex;
    height: 5vh;
    width: 100vw;
    background: rgb(226, 27, 27);
    justify-content: center;
    align-content: center;
  }
  #wordmark {
    font-family: "Plus Jakarta Sans", sans-serif;
    color: white;
    font-weight: 800;
    height: 80%; 
  }
</style>
