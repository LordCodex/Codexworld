<template>
  <div class="container">
    <header>
      <div class="header">
        <div class="logo"><h2>CODEXWORLD</h2></div>
        <div class="nav-links">
          <ul>
            <li>1.Home</li>
            <li>2.About</li>
            <li>3.Projects</li>
            <li>4.Contact</li>
          </ul>
        </div>
        <div @click="ToggleHandler" class="hamburger">
            #
        </div>
      </div>
    </header>
    <div class="hero-section">
      <div class="hero-box-1">
        <h1>
          Hello, I’m Codex, a Software Engineer with 
          3 years of experience.
        </h1>
        <br>
        <h5>Frontend & Backend Engineer</h5>
        <p>
          I care a lot about using design for positive impact. and enjoy
          creating user-centric, delightful, and human experiences.
        </p>
        <div class="btn-social">
          <button>Hire me</button>
          <div class="social-buttons">
            <div class="social">
              <Icon name="fa-brands:facebook"></Icon>
            </div>
            <div class="social">
              <Icon name="fa-brands:instagram"></Icon>
            </div>
            <div class="social">
              <Icon name="fa-brands:twitter"></Icon>
            </div>
            <div class="social">
              <Icon name="fa-brands:linkedin"></Icon>
            </div>
          </div>
        </div>
<!-- <br>
<br>
        <div class="stack-buttons">
          <div class="stack">
            <nuxt-img src="/img/icons/html.png"  height="50px"/>
          </div>
          <div class="stack">
            <nuxt-img src="/img/icons/css.png" />
          </div>
          <div class="stack">
            <nuxt-img src="/img/icons/js.png" />
          </div>
          <div class="stack">
            <nuxt-img src="/img/icons/jquery.webp" />
          </div>
          <div class="stack">
            <nuxt-img src="/img/icons/vue.png" />
          </div>
          <div class="stack">
            <nuxt-img src="/img/icons/nuxt.webp" />
          </div>
          <div class="stack">
            <nuxt-img src="/img/icons/php.png" />
          </div>
          <div class="stack">
            <nuxt-img src="/img/icons/laravel.png" />
          </div>
          <div class="stack">
            <nuxt-img src="/img/icons/golang.png" />
          </div>
        </div> -->
      </div>

      <div class="hero-box-2">
        <nuxt-img src="/img/lanre_up.jpg" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
    data() {
    return {
      isClicked: true,
    };
  },
  methods: {
    ToggleHandler() {
      this.isClicked = !this.isClicked;
      console.log(this.isClicked);
    },
  },
};
</script>

<style>
@import "~/assets/css/home.css";
</style>
