<template>
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Kulineran</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <router-link class="nav-link" to="/">Home</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" to="/FoodsView">Foods</router-link>
          </li>
        </ul>

        <ul class="navbar-nav me-auto ml-2 ml-lg-0">
          <li class="nav-item">
            <router-link class="nav-link" to="/keranjang">Keranjang<b-icon-bag></b-icon-bag>
            </router-link>
            
          </li>
          
        </ul>
        
      </div>
    </div>
  </nav>
</template>
  
  <script>
export default {
  name: "NavbarMenu"
};
</script>
  
  <style>
</style>