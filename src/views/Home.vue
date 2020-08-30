<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld :msg="msg"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  data:function(){
    return {
      msg:"布卡"
    }
  },
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
