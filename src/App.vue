<template>
  <v-app>
    <v-content>
      <Playground />
    </v-content>
  </v-app>
</template>

<script>
import Playground from '@/views/Playground'

export default {
  name: 'App',

  components: {
    Playground
  }
}
</script>
