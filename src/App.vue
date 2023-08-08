<script setup lang="ts">
  import Black from './components/Black.vue'
  import White from './components/White.vue'
</script>

<template>
<body class="MainHomePageBackground__item">
<main>
 <header>
  <div class="MainHomePageBackground__habibi_logo">
    <img alt="Habibi LOGO" class="logo" src="@/assets/Habibi.png" width="125" height="125" /></div>
    <div class="MainHomePageBackground_Follow_Us">
    <slot>Follow Us !</slot></div>
    <div class="MainHomePageBackground_Follow_Us">
    <slot><a class="Follow_Us_icons" href="https://www.facebook.com/profile.php?id=100091803657905/"><img alt="Facebook" class="Follow_Us_icons" src="" width="60" height="60" /></a></slot>  &nbsp; | &nbsp;    <a class="" href="https://www.instagram.com/habibi_barber79/"><img alt="Instagram" class="logo" src="" width="60" height="60" /></a>
    </div>
  </header>
</main>

</body>
<div class="MainHomePageBackground_power_by">
<slot>This site is built by: <a class="" href="https://amatak.io/">Amatak</a></slot></div>
</template>



<style>
  @import "./assets/main.css";
</style>