<template>
  <div class="home">
    <TopBar></TopBar>
    <NavBar></NavBar>
  </div>
</template>

<script>
import TopBar from '@/components/TopBar.vue';
import NavBar from '@/components/NavBar.vue';
// @ is an alias to /src

export default {
  name: 'HomeView',
  components: {
    TopBar,
    NavBar
}
}
</script>
