<template>
  <div id="app">
    <b-navbar>
      <template slot="brand">
        <b-navbar-item href="/">
          <img
            src="https://raw.githubusercontent.com/buefy/buefy/dev/static/img/buefy-logo.png"
            alt="Lightweight UI components for Vue.js based on Bulma"
          />
        </b-navbar-item>
      </template>
      <template slot="start">
        <b-navbar-item href="#/" class="navbar-item">
          Home
        </b-navbar-item>
        <b-navbar-item href="#/about" class="navbar-item">
          About
        </b-navbar-item>
        <b-navbar-item href="#/projects" class="navbar-item">
          Projects
        </b-navbar-item>
        <!-- <b-navbar-item href="#/blog" class="navbar-item">
          Blog
        </b-navbar-item> -->
        <a
          class="navbar-item"
          href="https://drive.google.com/file/d/110bvGGPXOsjxaqrYW3GgPQXdwQDVyou5/view?usp=sharing"
          target="_blank"
        >
          Résumé
        </a>
        <b-navbar-item class="navbar-item has-dropdown is-hoverable">
          <a class="navbar-link">
            More
          </a>

          <div class="navbar-dropdown">
            <a
              href="mailto:rajdeep@macports.org"
              target="_blank"
              class="navbar-item"
            >
              Contact
            </a>
            <hr class="navbar-divider" />
            <a
              href="https://github.com/rajdeepbharati/rajdeepbharati.github.io/issues"
              target="_blank"
              class="navbar-item"
            >
              Report an issue
            </a>
          </div>
        </b-navbar-item>
      </template>

      <template slot="end">
        <b-navbar-item tag="div">
          <div class="buttons">
            <a
              href="https://github.com/rajdeepbharati"
              target="_blank"
              class="navbar-item"
            >
              <img src="./assets/icons/Github.svg" width="28" height="28" />
            </a>
            <a
              href="https://twitter.com/ImRajdeepB"
              target="_blank"
              class="navbar-item"
            >
              <img src="./assets/icons/Twitter.svg" width="28" height="28" />
            </a>
            <a
              href="https://www.quora.com/profile/Rajdeep-Bharati"
              target="_blank"
              class="navbar-item"
            >
              <img src="./assets/icons/quora.svg" width="28" height="28" />
            </a>
            <a
              href="https://medium.com/@rajdeepbharati"
              target="_blank"
              class="navbar-item"
            >
              <img src="./assets/icons/medium.svg" width="28" height="28" />
            </a>
            <a
              href="https://www.linkedin.com/in/rajdeepbharati"
              target="_blank"
              class="navbar-item"
            >
              <img src="./assets/icons/Linkedin.svg" width="28" height="28" />
            </a>
          </div>
        </b-navbar-item>
      </template>
    </b-navbar>
    <!-- <div id="nav">
      <nav class="navbar" role="navigation" aria-label="main navigation">
        <div class="navbar-brand">
          <a class="navbar-item" href="https://bulma.io">
            <img
              src="https://bulma.io/images/bulma-logo.png"
              width="112"
              height="28"
            />
          </a>

          <a
            role="button"
            class="navbar-burger burger"
            aria-label="menu"
            aria-expanded="false"
            data-target="navbarBasicExample"
          >
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
          </a>
        </div>

        <div id="navbarBasicExample" class="navbar-menu">
          <div class="navbar-start">
            <router-link to="/" class="navbar-item">Home</router-link>

            <router-link to="/about" class="navbar-item">About</router-link>

            <router-link to="/projects" class="navbar-item">
              Projects
            </router-link>

            <a
              href="https://medium.com/@rajdeepbharati"
              target="_blank"
              class="navbar-item"
            >
              Blog
            </a>

            <div class="navbar-item has-dropdown is-hoverable">
              <a class="navbar-link">
                More
              </a>

              <div class="navbar-dropdown">
                <a
                  href="mailto:rajdeep@macports.org"
                  target="_blank"
                  class="navbar-item"
                >
                  Contact
                </a>
                <hr class="navbar-divider" />
                <a
                  href="https://github.com/rajdeepbharati/rajdeepbharati.github.io/issues"
                  target="_blank"
                  class="navbar-item"
                >
                  Report an issue
                </a>
              </div>
            </div>
            <a
              href="https://github.com/rajdeepbharati"
              target="_blank"
              class="navbar-item"
            >
              <img
                src="./assets/icons/SVG/SquareBlackWhite/Github.svg"
                width="28"
                height="28"
              />
            </a>
            <a
              href="https://twitter.com/ImRajdeepB"
              target="_blank"
              class="navbar-item"
            >
              <img
                src="./assets/icons/SVG/SquareColor/Twitter.svg"
                width="28"
                height="28"
              />
            </a>
            <a
              href="https://www.linkedin.com/in/rajdeepbharati"
              target="_blank"
              class="navbar-item"
            >
              <img
                src="./assets/icons/SVG/SquareColor/Linkedin.svg"
                width="28"
                height="28"
              />
            </a>
          </div>
        </div>
      </nav>
    </div> -->
    <router-view />
  </div>
</template>

<script>
export default {}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

.nav-item {
  color: red;
}
</style>
