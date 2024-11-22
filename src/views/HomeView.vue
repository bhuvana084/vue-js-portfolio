<script setup></script>

<template>
  <section id="profile">
    <div class="section__pic-container">
      <img src="../assets/profile-pic-linkedin.png" alt="Bhuvaneswari Lakshminarayanan" />
    </div>
    <div class="section__text">
      <p class="section__text__p1">Hello, I'm</p>
      <h1 class="title">Bhuvaneswari Lakshminarayanan</h1>
      <p class="section__text__p2">FullStack Software Developer</p>
      <div class="btn-container">
        <button
          class="btn btn-color-2"
          onclick="window.open('../assets/Bhuvaneswari_Lakshminarayanan_Resume.pdf')"
        >
          Download CV
        </button>
        <button class="btn btn-color-1" onclick="location.href='/contact'">Contact Info</button>
      </div>
      <div id="socials-container">
        <img
          src="../assets/linkedin.png"
          alt="My LinkedIn Profile"
          class="icon"
          onclick="window.open('https://www.linkedin.com/in/bhuvanalakshmi/')"
        />
        <img
          src="../assets/github.png"
          alt="My Github Profile"
          class="icon"
          onclick="window.open('https://github.com/bhuvana084')"
        />
      </div>
    </div>
  </section>
</template>
