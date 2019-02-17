<template>
  <div class="card offer-tile">
    <div class="card-header-title">
      <h2 class="title is-3 has-text-dark">{{ title }}</h2>
    </div>
    <div
      v-if="imgSrc"
      class="card-image">
      <figure class="image is-4by3">
        <img
          :src="imgSrc"
          alt="offer image">
      </figure>
    </div>
    <div class="card-content">
      <div class="content has-text-dark">
        <ul>
          <li
            v-for="(item, index) in items"
            :key="index">{{ item }}</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    imgSrc: {
      type: String,
      default: ''
    },
    title: {
      type: String,
      required: true
    },
    items: {
      type: Array,
      default: () => []
    }
  }
}
</script>

<style lang="scss" scoped>
.offer-tile {
  max-width: 400px;
}
</style>
