<template>
  <header class="navbar navbar-expand-lg navbar-dark py-3">
    <div class="container">         
      <a class="navbar-brand" href="#"> 
            <img src="../assets/img/light-logo.png" alt="dark"class="logo">
        </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item" v-for="item in menuItems" :key="item.name">
            <a class="nav-link" href="#">
              {{ item.name }} <i class="bi bi-chevron-down"></i>
            </a>
          </li>
        </ul>
        
        <div class="d-flex align-items-center">
          <a href="#" class="text-white me-3 position-relative">
            <i class="bi bi-cart3"></i>
            <span class="position-absolute top-0 start-100 translate-middle badge rounded-pill bg-success">
              0
            </span>
          </a>
          <a href="#" class="text-white me-3"><i class="bi bi-person-circle"></i></a>
          <form class="d-flex" role="search">
            <input class="form-control" type="search" placeholder="Search..." aria-label="Search">
            <button class="btn btn-search" type="submit"><i class="bi bi-search"></i></button>
          </form>
        </div>
      </div>
    </div>
    
  </header>
</template>

<script>
export default {
  name: 'Header',
  props: {
    menuItems: Array
  }
}
</script>



<style scoped>
.navbar {
  background-color: #2d1967 !important;
}
.navbar {
  background-color: #2d1967 !important;
}
.logo {
  max-width: 150px;
}


.navbar-brand {
  font-weight: bold;
  font-size: 1.5rem;
  color: white !important;
}

.nav-link {
  color: rgba(255, 255, 255, 0.8) !important;
  font-weight: 500;
  padding: 0.5rem 1rem !important;
}

.nav-link:hover {
  color: white !important;
}

.nav-link i {
  font-size: 0.75rem;
  margin-left: 2px;
}

.form-control {
  background-color: white;
  border: none;
  border-radius: 10px 0 0 10px;
  padding-left: 1rem;
  width: 50%;
}

.btn-search {
  background-color: white;
  border: none;
  border-radius: 0 10px 10px 0;
  color: #0ec81a;
  font-size:20px;
}

.btn-search:hover {
  background-color: #f0f0f0;
}

.bi-cart3, .bi-person-circle {
  font-size: 1.2rem;
}

.badge {
  font-size: 0.6rem;
  padding: 0.25em 0.4em;
}
</style>