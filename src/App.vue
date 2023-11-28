<template>
  <div id="app" class="bg-green-800 h-screen">
    <router-view />
    <AppNavbar/>
    
  </div>
</template>

<script>
  import AppNavbar from '@/components/AppNavbar.vue'
export default {
  name: 'HomeView',
  components: {
    AppNavbar
  }
}
</script>
