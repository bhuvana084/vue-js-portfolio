<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <nav id="desktop-nav">
    <div class="logo">
      <RouterLink to="/" style="text-decoration: none">Bhuvaneswari Lakshminarayanan</RouterLink>
    </div>
    <div>
      <ul class="nav-links">
        <li>
          <RouterLink to="/about">About</RouterLink>
        </li>
        <li><RouterLink to="/experience">Experience</RouterLink></li>
        <li><RouterLink to="/projects">Projects</RouterLink></li>
        <li><RouterLink to="/contact">Contact</RouterLink></li>
      </ul>
    </div>
  </nav>
</template>
