<template>
  <div>
    <h1>Olá coleguinhas da Webschool!</h1>
    <Intro/>
  </div>
</template>

<script>
import Intro from './Intro.vue'

export default {
  components: {
    Intro
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1{
    font-size: 50px;
    font-weight: bold;
    color: #FF0000;
  }
</style>
