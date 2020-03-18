<template>
  <div class="experience">
    <div class="e1">
      <h2>
        Google Summer of Code (2019) @
        <a href="https://www.macports.org" target="_blank">MacPorts</a>
      </h2>
      <h4>May - Aug 2019</h4>
      <div class="uldiv">
        <li>
          Ported MacPorts
          <a href="https::/buildbot.net">Buildbot</a> (Continuous Integration)
          Infrastructure from version 0.8 to 2.x.
        </li>
        <li>
          Optimized the database layer of Buildbot.
        </li>
        <li>
          Developed a
          <a
            href="https://github.com/macports/buildbot-macports-custom-views"
            target="_blank"
          >
            custom views plugin
          </a>
          for Buildbot that enables writing UI components in modern frameworks
          such as Vue.js instead of Angular.js.
        </li>
        <li>Wrote custom views for MacPorts Buildbot.</li>
        <li>
          Developed
          <a
            href="https://github.com/buildbot/buildbot/commits?author=rajdeepbharati"
            target="_blank"
          >
            new features in Buildbot
          </a>
          and made it scalable for large setups (support > 20k builds at once).
        </li>
        <li>
          Packaging and maintaining
          <a
            href="https://ports.macports.org/maintainer/github/rajdeepbharati/"
            target="_blank"
          >
            ports related to Buildbot </a
          >.
        </li>
      </div>
      <br />
      <h2>
        Software Engineer, Intern @
        <a href="https://www.fetchmewishes.com" target="_blank">FetchMe</a>
      </h2>
      <h4>Sept - Nov 2018</h4>
      <div class="uldiv">
        <li>
          Built web platform from scratch and scaled it to 2k active users.
        </li>
        <li>
          Developed an efficient dispatch system.
        </li>
        <li>
          Wrote a chatbot for Facebook Messenger that increased user engagement
          by more than 60%.
        </li>
        <li>
          Integrated payment gateway.
        </li>
        <li>
          Implemented Maps APIs: created a model of the geographical area where
          the service is available; added features like distance, time, and fare
          estimation.
        </li>
      </div>
    </div>
  </div>
</template>
<style scoped>
.e1 {
  margin: 0 8px;
}
.uldiv {
  margin-left: 4px;
}
.experience {
  /* margin-left: 16px; */
  margin: 8px 8px 0px 8px;
}
h1 {
  font-size: 32px;
}
h2 {
  font-size: 24px;
}
h3 {
  font-size: 18.72px;
}
h4 {
  font-size: 16px;
}
</style>
