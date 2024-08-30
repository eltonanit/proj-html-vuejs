<template>
  <div id="app">
    <Header :menuItems="headerMenuItems" />
    <Main />
    <Footer :menuItems="footerMenuItems" />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'
import 'bootstrap/dist/css/bootstrap.min.css'
import 'bootstrap-icons/font/bootstrap-icons.css'
import 'bootstrap/dist/js/bootstrap.bundle.min.js'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  },
  data() {
    return {
      headerMenuItems: [
        { name: 'Home', url: '#' },
        { name: 'Pages', url: '#' },
        { name: 'Courses', url: '#' },
        { name: 'Features', url: '#' },
        { name: 'Blog', url: '#' },
        { name: 'Shop', url: '#'}
      ],
      footerMenuItems: [
        { name: 'Explore', items: ['Start here', 'Blog', 'About us'] },
        { name: 'Information', items: ['Membership', 'Purchase guide', 'Privacy policy'] },
        { name: 'Community', items: ['Forums', 'Community', 'Events'] },
      ]
    }
  }
}
</script>

<style scoped>
#app {
  font-family: Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>