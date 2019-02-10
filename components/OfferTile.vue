<template>
  <div class="card offer-tile">
    <div class="card-header-title">
      <h2 class="title is-3 has-text-dark">Lorem Ipsum</h2>
    </div>
    <div class="card-image">
      <figure class="image is-4by3">
        <img
          :src="imgSrc"
          alt="offer image">
      </figure>
    </div>
    <div class="card-content">
      <div class="content has-text-dark">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    imgSrc: {
      type: String,
      default: 'https://via.placeholder.com/400x300?text=Moja Oferta'
    }
  }
}
</script>

<style lang="scss" scoped>
.offer-tile {
  max-width: 400px;
}
</style>
