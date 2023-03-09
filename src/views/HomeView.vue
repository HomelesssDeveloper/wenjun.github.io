<template>
  <div class="home">
    <Snow :zIndex="'2'" color="#ffffff" :swing='2' :speed='"m"' />
  </div>
</template>

<script>
  // @ is an alias to /src
  import HelloWorld from '@/components/HelloWorld.vue'
  import Snow from 'vue-niege';
  export default {
    name: 'HomeView',
    components: {
      HelloWorld,
      Snow,
    },
    methods: {
      
    },
    mounted() {
      
    }
  }
</script>
<style lang="scss" scoped>
  .home {
    height: 100vh;
    background: #000;
  }
</style>