<template>
  <div id="app">
    <div class="wrapper">
      <section class="hero">
        <h1>The Indoor Plant.</h1>
      </section>
  <section>
         <h1 class="main-content-header"> <span>Find the perfect plant <br>to add to your living space.</span> </h1>
  </section>
      <section class="plants">
 
        <md-card md-with-hover>
      <div class="media">
        <img src="ivy.jpg" alt="">
      </div>

      <md-card-header>
        <div class="md-title">Living Room Space</div>
        <div class="md-subhead">These plants are suitable for larger living spaces.</div>
      </md-card-header>

      <md-card-content>
        Explore plants that are a perfect addition to you living room space.
    
      </md-card-content>

      <md-card-actions>
                    <md-button>Explore</md-button>
      </md-card-actions>
 

    </md-card>
      <md-card md-with-hover>
      <div class="media-two">
      </div>

      <md-card-header>
        <div class="md-title">Bed Room Space</div>
        <div class="md-subhead">These plants are suitable for larger living spaces.</div>
      </md-card-header>

      <md-card-content>
        Explore plants that are a perfect addition to you living room space.
    
      </md-card-content>

      <md-card-actions>
                    <md-button>Explore</md-button>
      </md-card-actions>
 

    </md-card>


    
      <md-card md-with-hover>
      <div class="media-three">
      </div>

      <md-card-header>
        <div class="md-title">Kitchen Space</div>
        <div class="md-subhead">Add elegance to your kitchen with this selection of plants.</div>
      </md-card-header>

      <md-card-content>
        Explore plants that are a perfect addition to you living room space.
    
      </md-card-content>

      <md-card-actions>
                    <md-button>Explore</md-button>
      </md-card-actions>
 

    </md-card>

      <md-card md-with-hover>
      <div class="media-four">
      </div>

      <md-card-header>
        <div class="md-title">Outdoor Space</div>
        <div class="md-subhead">Livin' up your outdoor space with these selection of plants.</div>
      </md-card-header>

      <md-card-content>
        Explore plants that are a perfect addition to you living room space.
    
      </md-card-content>

      <md-card-actions>
                    <md-button>Explore</md-button>
      </md-card-actions>
 

    </md-card>

      </section>
    </div>
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
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  grid-template-rows: 25vw 30vw 10vw;
}

.hero {
  background: url('header-background.png') center;
  background-size: cover;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  align-items: center;
  min-height: 30vh;
}

.hero h1 {
  font-size: 5em;
  text-align: center;
  color: white;
  font-weight: 400;
}

.main-content-header {
  margin-top: 5rem;
  font-size: 3em;
  font-weight: 400;
  text-transform: capitalize;
  text-align: center;
}

.plants {
  margin-top: 1rem;
  padding: 2rem;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}

.md-card {
    min-width: 300px;
    min-height: 200px;
    display: block;
    vertical-align: top;
    margin: 2em;
}

.media {
  height: 220px;
  width: 100%;
  background: url('mostera.jpg') center;
  background-size: cover;
}
.media-two {
  height: 220px;
  width: 100%;
  background: url('ivy.jpg') center;
  background-size: cover;
}

.media-three {
   height: 220px;
  width: 100%;
  background: url('parsley.jpg') center;
   background-size: cover;
}

.media-four {
     height: 220px;
  width: 100%;
  background: url('cherry-blossum.jpg');
     background-size: cover;
}




/* Demo Specific Styles */




</style>
