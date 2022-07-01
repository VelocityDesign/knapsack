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
    height: 7.5vh;
    width: 100vw;
    background: rgb(226, 27, 27);
    align-items: center;
    box-shadow: 0px 0px 16px -3px rgba(0, 0, 0, 0.43);
  }
  #wordmark {
    font-family: "Plus Jakarta Sans", sans-serif;
    color: white;
    font-weight: 800;
    font-size: 2em; 
  }
  @media screen and (min-width: 700px) {
    #navbar-container {
        /* justify-content: center; */
    }
    #wordmark {
      
    }
  }
  @media screen and (max-width: 700px) {
    #navbar-container {
        justify-content: center;
    }
  }
</style>
