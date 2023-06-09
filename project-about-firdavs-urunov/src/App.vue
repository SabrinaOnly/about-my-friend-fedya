<script >
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import FirstPage from "./firstPage.vue"

export default {
  data() {
    return {

    }
  },
  components: {
    'first-page': FirstPage
  }
}
</script>

<template>
  <RouterView />
</template>




<style scoped>

</style>
