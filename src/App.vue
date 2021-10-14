<template>
  <Header></Header>
</template>

<script>
import Header from './components/Header'

export default {
  name: 'App',
  components: {
    Header,
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');
body{
  margin: 0;
}

#app {
  font-family: 'Montserrat', sans-serif;
}
</style>
