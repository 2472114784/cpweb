<template>
  <div id="app">
    <v-content></v-content>
    <v-footer></v-footer>
  </div>
</template>
<script>
import content from '../components/Home_Content'
import footer from '../components/Home_Footer'

export default {
  data() {
    return {
      message: "hello vue!"
    };
  },

  methods: {
    
  },
  components:{
    'v-content':content,
    'v-footer':footer
  }
};
</script>
<style scoped>
