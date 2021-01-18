<template>
  <div class="home">
    <HelloWorld msg="Hello I'm Jay Oliver"/>
    <h3>Github: https://github.com/Qwerter49</h3>
    <h3>LinkedIn: </h3>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
