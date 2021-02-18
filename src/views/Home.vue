<template>
  <div class="home">
    <HelloWorld msg="谢谢你，给了我这次机会，我一定会抓住它！"/>
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
