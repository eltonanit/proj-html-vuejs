<template>
  <footer>
    <div v-for="section in menuItems" :key="section.name" class="footer-section">
      <h3>{{ section.name }}</h3>
      <ul>
        <li v-for="item in section.items" :key="item">{{ item }}</li>
      </ul>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  props: {
    menuItems: Array
  }
}
</script>

<style scoped>
footer {
  display: flex;
  justify-content: space-around;
  padding: 2rem;
  background-color: #f5f5f5;
}

.footer-section h3 {
  margin-bottom: 1rem;
}

.footer-section ul {
  list-style-type: none;
  padding: 0;
}

.footer-section ul li {
  margin-bottom: 0.5rem;
}
</style>