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
          <a class="navbar-item">
            Oferta
          </a>
          <a class="navbar-item">
            Wykonane Realizacje
          </a>
          <a class="navbar-item">
            O Firmie
          </a>
          <a class="navbar-item">
            Kontakt
          </a>
        </div>
      </div>
    </nav>
    <nuxt/>
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
