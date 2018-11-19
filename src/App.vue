<template>
  <v-app >
    <div class="red darken-4">
      <v-content>
        <HelloWorld/>  
      </v-content>
    </div>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data () {
    return {
      //
    }
  }
}
</script>
