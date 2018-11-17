<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>

    <br><br><br><br><br><br><br><br><br><br><br><br>

    <Apollo-example />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

import ApolloExample from '@/components/ApolloExample.vue'

export default {
  name: 'home',
  components: {
    HelloWorld,
    ApolloExample
  }
}
</script>
