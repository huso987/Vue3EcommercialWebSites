<script setup>
import { RouterLink, RouterView } from 'vue-router'
import navbarvuea from './components/Navbar.vue'
import Kateg from './components/Kategoriler.vue'
import slide from './components/Slider.vue' 
import card from './components/Kcard.vue'
import pslider from './components/Pslider.vue'
import yanrek from './components/YanReklam.vue'
import pslider2 from './components/Pslider2.vue'
import simge from './components/Simge.vue'
import ykolek from './components/YeniKoleksiyon.vue'
import bilgi1 from './components/Bilgiaqua.vue'
</script>

<template>

<navbarvuea></navbarvuea>
<Kateg></Kateg>
<slide></slide>
<card></card>
<pslider></pslider>
<simge></simge>
<yanrek></yanrek>
<pslider2></pslider2>
<ykolek></ykolek>
<bilgi1></bilgi1>
</template>

<style scoped>

</style>


<!-- <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
    <a class="navbar-brand" href="http://localhost:5173/about">Navbar</a>
    
    <div class="collapse navbar-collapse" id="navbarNavDropdown">
      <ul class="navbar-nav">
        <li class="nav-item">
          <RouterLink to="/" class="nav-link" >Home</RouterLink>
        </li>
        <li class="nav-item">
          <RouterLink to="/about" class="nav-link">About</RouterLink>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Pricing</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Dropdown link
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>
      </ul>
    </div>
  </div>
</nav>




  <RouterView /> -->