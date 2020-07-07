<template>
  <div class="home">
    
    <ListVideos msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>

import ListVideos from '@/components/ListVideos.vue'


export default {
  name: 'Home',
  components: {
    ListVideos

  }
}
</script>
