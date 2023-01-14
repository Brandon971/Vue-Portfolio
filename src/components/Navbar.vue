<template>
    <nav class="navbar navbar-dark sticky-top">
            <div class="container-fluid text-center">
              <router-link class="navbar-brand" to="/">Brandon Swinton</router-link>
              <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasDarkNavbar" aria-controls="offcanvasDarkNavbar">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="offcanvas offcanvas-end text-bg-dark" tabindex="-1" id="offcanvasDarkNavbar" aria-labelledby="offcanvasDarkNavbarLabel">
                <div class="offcanvas-header">
                  <h5 class="offcanvas-title" id="offcanvasDarkNavbarLabel">Brandon Swinton</h5>
                  <button type="button" class="btn-close btn-close-white" data-bs-dismiss="offcanvas" aria-label="Close"></button>
                </div>
                <div class="offcanvas-body">
                  <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
                    <li class="nav-item">
                        <router-link class="router" to="/"> HOME </router-link>
                    </li>
                    <li class="nav-item">
                        <router-link class="router" to="/about"> ABOUT </router-link>
                    </li>
                    <li class="nav-item">
                        <router-link class="router" to="/resume"> RESUME </router-link>
                    </li>
                    <li class="nav-item">
                        <router-link class="router" to="/skills"> SKILLS </router-link>
                    </li>
                    <li class="nav-item">
                      <router-link class="router" to="/projects"> PROJECTS </router-link>
                    </li>
                    <li class="nav-item">
                        <router-link class="router" to="/testimonials"> TESTIMONIALS </router-link>
                    </li>
                    <li class="nav-item">
                        <router-link class="router" to="/contact"> CONTACT ME </router-link>
                    </li>
                      </ul>
                </div>
              </div>
            </div>
          </nav> 
</template>
<script>
export default {
    
}
</script>
<style>
.router{
  text-decoration: none;
  color: antiquewhite;
  font-family: sans-serif;
}
.router:hover{
    color: lightslategray;
    transition: 0.3s;
    text-decoration: none;
}
li{
    padding-top: 40px;
}



    
</style>