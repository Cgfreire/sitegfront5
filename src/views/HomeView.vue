<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/eu.png">
    <HelloWorld msg="Olá! Tudo bem Pessoal? Como vão vocês?"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
