<script setup></script>

<template>
  <section id="projects">
    <p class="section__text__p1">Browse My Recent</p>
    <h1 class="title">Projects</h1>
    <div class="experience-details-container">
      <div class="about-containers">
        <div class="details-container color-container">
          <div class="article-container">
            <img src="../assets/project-1.jpg" alt="Project 1" class="project-img" />
          </div>
          <h2 class="experience-sub-title project-title">Montessori Money Game</h2>
          <div class="btn-container">
            <button
              class="btn btn-color-2 project-btn"
              onclick="window.open('https://github.com/bhuvana084/bhuvana084.github.io')"
            >
              Github
            </button>
            <button
              class="btn btn-color-2 project-btn"
              onclick="window.open('http://montessorimoneygame.com/')"
            >
              Live Demo
            </button>
          </div>
        </div>
        <div class="details-container color-container">
          <div class="article-container">
            <img src="../assets/project-2.jpg" alt="Project 2" class="project-img" />
          </div>
          <h2 class="experience-sub-title project-title">Rock, Paper, Scissors</h2>
          <div class="btn-container">
            <button
              class="btn btn-color-2 project-btn"
              onclick="window.open('https://github.com/bhuvana084/vue-rock-paper-shears')"
            >
              Github
            </button>
            <button
              class="btn btn-color-2 project-btn"
              onclick="window.open('https://rock-paper-shears.com/')"
            >
              Live Demo
            </button>
          </div>
        </div>
        <div class="details-container color-container">
          <div class="article-container">
            <img src="../assets/project-3.jpg" alt="Project 3" class="project-img" />
          </div>
          <h2 class="experience-sub-title project-title">Words Building Game</h2>
          <div class="btn-container">
            <button
              class="btn btn-color-2 project-btn"
              onclick="window.open('https://github.com/bhuvana084/bhuvana084.github.io')"
            >
              Github
            </button>
            <!--TODO Fix the Project URL and Update-->
            <!-- <button class="btn btn-color-2 project-btn" onclick="window.open('http://montessorimoneygame.com/')">
                            Live Demo
                        </button>  -->
          </div>
        </div>
      </div>
    </div>
    <!-- <img
      src="../assets/arrow.png"
      alt="Arrow icon"
      class="icon arrow"
      onclick="location.href='./#contact'"
    /> -->
  </section>
</template>
