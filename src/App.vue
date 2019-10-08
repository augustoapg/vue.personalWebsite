<template>
  <div id="app">
    <NavigationBar />
    <AboutMe />
    <Resume />
    <Portfolio />
    <Contact />
    
    <footer>
      <a href="https://icons8.com/icon/13930/LinkedIn">Icons provided by Icons8</a>
    </footer>
  </div>
</template>

<script>
import AboutMe from './components/AboutMe.vue'
import Resume from './components/Resume.vue'
import Portfolio from './components/Portfolio.vue'
import Contact from './components/Contact.vue'
import NavigationBar from './components/NavigationBar.vue'

export default {
  name: 'app',
  components: {
    NavigationBar,
    AboutMe,
    Resume,
    Portfolio,
    Contact
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}

footer {
  margin-top: 3em;
}

h1 {
  margin-top: 2em;
  text-align: left;
}

/* Enter and leave animations can use different */
/* durations and timing functions.              */
.slide-fade-enter-active {
  transition: all 1.5s ease;
}
.slide-fade-leave-active {
  transition: all .8s cubic-bezier(1.0, 0.5, 0.8, 1.0);
}
.slide-fade-enter, .slide-fade-leave-to
/* .slide-fade-leave-active below version 2.1.8 */ {
  transform: translateX(10px);
  opacity: 0;
}
</style>
