<template>
  <div id="app">
    <div class="cont">
      <b-navbar>
        <template slot="brand">
          <b-navbar-item href="/">
            <img
              src="./assets/amusedcrabbie.svg"
              alt="amused crabbie rust-lang"
            />
          </b-navbar-item>
        </template>
        <template slot="start">
          <b-navbar-item href="#/" class="navbar-item">
            Home
          </b-navbar-item>
          <b-navbar-item href="#/experience" class="navbar-item">
            Experience
          </b-navbar-item>
          <!-- <b-navbar-item href="#/about" class="navbar-item">
            About
          </b-navbar-item> -->
          <b-navbar-item href="#/projects" class="navbar-item">
            Projects
          </b-navbar-item>
          <!-- <b-navbar-item href="#/blog" class="navbar-item">
            Blog
          </b-navbar-item> -->
          <a
            class="navbar-item"
            href="https://drive.google.com/file/d/1EtWdk4NjHvV8AyLt8QAu7sq-WcDruDxq/view?usp=sharing"
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
      <router-view />
    </div>
    <footer class="footer">
      <div class="content has-text-centered">
        <p>
          © Rajdeep Bharati 2020 <!--Social media icons by
          <a href="https://www.vecteezy.com">Vecteezy</a>. Images by
          <a href="https://www.rust-lang.org/">rust-lang.org</a>-->
          <br />
          Made with
          <i class="fa fa-heart" style="font-size: 16px; color: red"></i> in
          Vue.js and Bulma.
        </p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {}
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
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

html,
body {
  height: 100%;
}

#app {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

.cont {
  flex: 1;
}
</style>
