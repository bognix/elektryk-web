<template>
  <div>
    <nav class="navbar">
      <div class="navbar-brand">
        <nuxt-link
          class="navbar-item"
          to="/">Instalacje Elektryczne - Bartosz Flieger</nuxt-link>
        <a
          role="button"
          class="navbar-burger burger"
          aria-label="menu"
          aria-expanded="false"
          data-target="navbarMain"
        >
          <span aria-hidden="true"/>
          <span aria-hidden="true"/>
          <span aria-hidden="true"/>
        </a>
      </div>
      <div
        id="navbarMain"
        class="navbar-menu"
      >
        <div class="navbar-end">
          <nuxt-link
            class="navbar-item"
            to="/offer">
            Oferta
          </nuxt-link>
          <nuxt-link
            class="navbar-item"
            to="/projects">
            Wykonane Realizacje
          </nuxt-link>
          <nuxt-link
            class="navbar-item"
            to="/about-us">
            O Firmie
          </nuxt-link>
          <nuxt-link
            class="navbar-item"
            to="/contact">
            Kontakt
          </nuxt-link>
        </div>
      </div>
    </nav>
    <nuxt/>
    <footer class="footer has-text-light">
      <div class="columns">
        <div class="column">
          <p class="subtitle is-5 has-text-light">Dane firmy</p>
          <p>
            <span class="is-block">ul. Zofii Nałkowskiej 55/28</span>
            <span class="is-block">60-573 Poznań</span>
          </p>
          <p>+48 665 414 109</p>
          <p>Nip: 7881947653</p>
          <p>Zakład ogólno-budowlany elektryczno-pomiarowy Bartosz Flieger</p>
        </div>
        <div class="column is-three-quarters has-text-right-desktop has-text-right-tablet">
          <a
            href="https://www.facebook.com/instalacjeelektrycznebartoszflieger/"
            target="_blank">
            <span class="icon">
              <i class="fab fa-facebook"/>
            </span>
            Znajdź nas na Facebooku
          </a>
        </div>
      </div>
    </footer>
  </div>
</template>

<style lang="scss">
@import '~/assets/theme.scss';

html {
  font-family: $family-primary;
  font-size: $font-size;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}
</style>
