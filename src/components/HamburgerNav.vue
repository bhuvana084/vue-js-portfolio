<script setup>
const toggleMenu = () => {
  const menu = document.querySelector('.menu-links')
  const icon = document.querySelector('.hamburger-icon')
  menu.classList.toggle('open')
  icon.classList.toggle('open')
}
</script>

<template>
  <nav id="hamburger-nav">
    <div class="logo">
      <RouterLink to="/" style="text-decoration: none">Bhuvaneswari Lakshminarayanan</RouterLink>
    </div>
    <div class="hamburger-menu">
      <div class="hamburger-icon" @click="toggleMenu">
        <span></span>
        <span></span>
        <span></span>
      </div>
      <div class="menu-links">
        <li><RouterLink to="/about" @click="toggleMenu">About</RouterLink></li>
        <li><RouterLink to="/experience" @click="toggleMenu">Experience</RouterLink></li>
        <li><RouterLink to="/projects" @click="toggleMenu">Projects</RouterLink></li>
        <li><RouterLink to="/contact" @click="toggleMenu">Contact</RouterLink></li>
      </div>
    </div>
  </nav>
</template>
