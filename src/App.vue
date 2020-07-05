<template>
  <div id="app">
    <div class="app-page">
      <div class="resume" v-if="isResumePageActive">
        <resume-layout></resume-layout>
      </div>
      <div class="home-layout" v-else>
        <navigation></navigation>
        <hr />
        <router-view/>
      </div>
    </div>
  </div>
</template>

<script>
import Navigation from '@/components/navigation.vue'
import ResumeLayout from '@/components/resume-layout.vue'
export default {
  name: 'App',
  data() {
    return {
      isResumePageActive: true,
    }
  },
  components: {
    Navigation,
    ResumeLayout
  }
}
</script>

<style>
#app {
  /* font-family: 'Avenir', Helvetica, Arial, sans-serif; */
  font-family: "Saira Extra Condensed", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
.cta-300 {
  min-width: 300px;
}
ul {
  list-style: none;
  padding: 0;
}
</style>