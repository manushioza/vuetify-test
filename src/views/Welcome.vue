<template>
  <div class="home">
   <Intro/>
  
  </div>
</template>

<style lang="scss">
  @import '../styles/Welcome.scss';

</style>

<script>
// @ is an alias to /src

import Intro from '@/components/Intro.vue'

export default {
  name: 'Welcome',
  components: {
   Intro
  }
}

</script>

