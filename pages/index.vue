<template>
  <div class="container">
    <header>
      <div class="header" id="hero">
        <div class="logo"><h2>CODEXWORLD</h2></div>
        <div class="nav-links">
          <ul>
            <li><a href="#hero">1.Home</a></li>
            <li><a href="#project">2.Projects</a></li>
            <li><a href="#stack">3.Stacks</a></li>
            <li><a href="#contact">4.Contact</a></li>
          </ul>
        </div>
        <div :class="{ active: isClicked }" class="nav-side">
          <ul>
            <li>
              <a href="#hero"
                ><Icon name="material-symbols:home-outline"></Icon
              ></a>
            </li>
            <li>
              <a href="#project">
                <Icon name="material-symbols:workspace-premium-rounded"></Icon
              ></a>
            </li>
            <li>
              <a href="#stack">
                <Icon name="material-symbols:tools-wrench-outline-sharp"></Icon
              ></a>
            </li>
            <li>
              <a href="#contact">
                <Icon name="material-symbols:contacts-outline-sharp"></Icon
              ></a>
            </li>
          </ul>
        </div>
        <div @click="ToggleHandler" class="hamburger">
          <div v-if="(isClicked = isClicked)">
            <Icon name="material-symbols:density-medium-rounded"></Icon>
          </div>
          <div v-else>
            <Icon name="material-symbols:cancel-outline-rounded"></Icon>
          </div>
        </div>
      </div>
    </header>

    <div class="hero-section">
      <div class="hero-box-1">
        <h1>
          Hello, I’m Codex, a Software Engineer with 3 years of experience.
        </h1>
        <br />
        <h5>Frontend & Backend Engineer</h5>
        <p>
          I care a lot about using design and creating web & application
          Software for positive impact. and enjoy creating user-centric,
          delightful, and human experiences to solve Problems in the Society.
        </p>
        <div class="btn-social">
          <a href="mailto:michaelolaitan6@gmail.com">
            <button>Contact me</button></a
          >
          <div class="social-buttons">
            <div class="social">
              <a
                href="https://web.facebook.com/michaeloreoluwa5"
                target="_blank"
              >
                <Icon name="fa-brands:facebook"></Icon
              ></a>
            </div>
            <div class="social">
              <a href="https://www.instagram.com/lanre_olat/" target="_blank">
                <Icon name="fa-brands:instagram"></Icon
              ></a>
            </div>
            <div class="social">
              <a href="https://twitter.com/lanre_olat" target="_blank">
                <Icon name="fa-brands:twitter"></Icon
              ></a>
            </div>
            <div class="social">
              <a href="https://www.linkedin.com/in/lanreolat" target="_blank">
                <Icon name="fa-brands:linkedin"></Icon
              ></a>
            </div>
          </div>
        </div>

        <!-- <br>
<br>
        <div class="stack-buttons">
          
        </div> -->
      </div>

      <div class="hero-box-2">
        <nuxt-img src="/img/lanre_up.jpg" />
      </div>
    </div>

    <br />

    <div class="project-section" id="project">
      <div class="project-row">
        <div class="project-box">
          <a href="https://olatconcept.com.ng/sms/" target="_blank"
            ><nuxt-img src="/img/olatsms.png"
          /></a>
        </div>
        <div class="project-box">
          <a href="https://360litepay.netlify.app/" target="_blank"
            ><nuxt-img src="/img/360app.png"
          /></a>
        </div>
      </div>

      <div class="project-row">
        <div class="project-box">
          <a href="https://codexblog.com.ng/" target="_blank"
            ><nuxt-img src="/img/codexblo.png"
          /></a>
        </div>
        <div class="project-box">
          <a href="https://360lite.com.ng/" target="_blank"
            ><nuxt-img src="/img/360liteweb.png"
          /></a>
        </div>
      </div>
    </div>

    <br />
    <div class="stacks" id="stack">
      <div class="stack">
        <nuxt-img src="/img/icons/html.png" height="50px" />
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
      <div class="stack">
        <nuxt-img src="/img/icons/cap.svg" />
      </div>
      <div class="stack">
        <nuxt-img src="/img/icons/ionic.png" />
      </div>
    </div>

    <br />

    <div class="hero-section" id="contact">
      <div class="hero-box-3" style="width: 100%">
        <h1>Want to work together?</h1>
        <br />
        <h5>
          Feel free to reach out for collaborations or just a friendly hello
        </h5>
        <a href="mailto:michaelolaitan6@gmail.com">
          <p style="margin-top: 1em; color: white">
            michaelolaitan6@gmail.com
          </p></a
        >
        <div class="btn-social">
          <a
            href="https://drive.google.com/uc?export=download&id=170CE2QJrZI3fvcgd6FnKoZ7jn65f81wa"
            ><button>Download CV</button></a
          >
          <div class="social-buttons">
            <div class="social">
              <a
                href="https://web.facebook.com/michaeloreoluwa5"
                target="_blank"
              >
                <Icon name="fa-brands:facebook"></Icon
              ></a>
            </div>
            <div class="social">
              <a href="https://www.instagram.com/lanre_olat/" target="_blank">
                <Icon name="fa-brands:instagram"></Icon
              ></a>
            </div>
            <div class="social">
              <a href="https://twitter.com/lanre_olat" target="_blank">
                <Icon name="fa-brands:twitter"></Icon
              ></a>
            </div>
            <div class="social">
              <a href="https://www.linkedin.com/in/lanreolat" target="_blank">
                <Icon name="fa-brands:linkedin"></Icon
              ></a>
            </div>
          </div>
        </div>
        <br />
      </div>
    </div>

    <br />
  </div>
</template>

<script>
export default {
  data() {
    return {
      isClicked: true,
      title: 'Codexworld',
    };
  },
   head({ $seo }) {
      return $seo({
        title: 'Codexworld',
        description: 'Hello, I’m Codex World, a Software Engineer with 4 years of experience. I care a lot about using design and creating web & application Software for positive impact. and enjoy creating user-centric, delightful, and human experiences to solve Problems in the Society.',
        keywords: 'Codex, Codexworld, Software Engineer',
      })
    },
  methods: {
    ToggleHandler() {
      this.isClicked = !this.isClicked;
    },
  },
};
</script>

<style>
@import "~/assets/css/home.css";
</style>
