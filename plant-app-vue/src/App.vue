<template>
  <div id="app">
  <header>
  <h1>The Indoor Plant.</h1>
</header>
<main>
  Main
</main>

<footer>
  Footer
</footer>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',

  data() {
    return {
      data: [
        {
          name: 'Chinese Fan Palm',
        },
        {
          name: 'Parlor Palm'
        }
      ]
    }
  },
  components: {
    // HelloWorld
  }
}
</script>

<style>
#app {
 font-family: 'Roboto', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin: 0;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-template-rows: 20vw 30vw 10vw;

}

header,
footer {
  grid-column: 1 / span 5;

}

main {
  grid-column: 1 / span 5;

}

aside {
  grid-column: span 2;
}

@media (max-width: 700px) {
  
  main,
  aside {
    grid-column: 1 / span 5;
  }
  
}

/* Demo Specific Styles */

header {
  background-color: #56B895;
   display: flex;
  align-items: center;
  justify-content: center;
}

header h1 {
  color: white;
}
main,
aside,
footer {
  display: flex;
  align-items: center;
  justify-content: center;
}





</style>
