<script setup>
import { RouterLink, RouterView } from 'vue-router'
import navbarvuea from './components/Navbar.vue'
import Kateg from './components/Kategoriler.vue'
import slide from './components/Slider.vue' 
import card from './components/Kcard.vue'
import pslider from './components/Pslider.vue'

</script>

<template>
 <navbarvuea></navbarvuea>
<Kateg></Kateg>
<slide></slide>
<card></card>
<pslider></pslider>

</template>

<style>

</style>
