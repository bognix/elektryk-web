<template>
  <div>
    <nav class="navbar">
      <div class="navbar-brand">
        <nuxt-link
          class="navbar-item"
          to="/">LOGO</nuxt-link>

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
    <footer class="footer">
      <div class="columns">
        <div class="column">
          <p>Dane firmy</p>
          <p>Adres...</p>
          <p>Telefon...</p>
          <p>Nip...</p>
          <p>Nazwa...</p>
        </div>
        <div class="column is-three-quarters">
          Znajdź nas na Facebooku
          <span class="icon">
            <i class="fab fa-facebook"/>
          </span>
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
