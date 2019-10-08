<template>
    <nav class="navbar navbar-expand-md navbar-dark bg-dark fixed-top">
      <a class="navbar-brand" @click="navigateTo('aboutMe')">Augusto Peres</a>

      <!-- Toggle button for small screens -->
      <button class="navbar-toggler" type="button" data-toggle="collapse" 
              data-target="#navbarsExampleDefault" 
              aria-controls="navbarsExampleDefault" aria-expanded="false" 
              aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarsExampleDefault">
          <ul class="navbar-nav mr-auto">
              <li class="nav-item">
                  <a class="nav-link" @click="navigateTo('resume')">
                      Resume</a>
              </li>
              <li class="nav-item">
                  <a class="nav-link" @click="navigateTo('portfolio')">
                      Portfolio</a>
              </li>
              <li class="nav-item">
                  <a class="nav-link" @click="navigateTo('contact')">
                      Contact</a>
              </li>
          </ul>
          <ul class="nav navbar-nav navbar-right">
              <li><a href="https://github.com/augustoapg" target="_blank">
                      <img src="../assets/icons8-GitHub-48.png" 
                            alt="github_icon"></a></li>
              <li><a href="https://www.linkedin.com/in/augustoapg/"
                      target="_blank">
                      <img src="../assets/icons8-LinkedIn-48.png" 
                            alt="linkedin_icon"></a>
              </li>
          </ul>
      </div>
    </nav>
</template>

<script>
export default {
  name: 'NavigationBar',
  props: {
    msg: String
  },
  data () {
    return {

    }
  },
  methods: {
    navigateTo: function(page) {
      // pagesStatus = {
      //   "resume": false,
      //   "portfolio": false
      // }

      // pagesStatus[page] = true
      this.$emit('navigateTo', page)
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.navbar-brand {
  color: white !important;
}
</style>
