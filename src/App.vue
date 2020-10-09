<template>
  <Header msg="Header"/>
  <Main msg="Main"/>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main
  }
}
</script>

<style>
html {
  font-size: 16px;
}

body {
  font-family: "Helvetica Neue","Helvetica,Roboto","Arial",sans-serif;
  font-weight: 400;
  line-height: 1.5;
  color: #222;
}

p {
  margin-top: 0.5rem;
  margin-bottom: 0.5rem;
}

.row {
  max-width: 1425px;
  margin: auto;
}

i {
  font-family: "fontawesome";
}
</style>
