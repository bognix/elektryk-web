<template>
  <div class="section">
    <div class="container offer-tiles">
      <offer-tile class="offer-tile"/>
      <offer-tile class="offer-tile"/>
      <offer-tile class="offer-tile"/>
      <offer-tile class="offer-tile"/>
      <offer-tile class="offer-tile"/>
      <offer-tile class="offer-tile"/>
    </div>
  </div>
</template>

<script>
import OfferTile from '~/components/OfferTile'
export default {
  components: { OfferTile }
}
</script>

<style lang="scss" scoped>
@import '~/assets/theme.scss';

.offer-tiles {
  display: flex;
  flex-wrap: wrap;

  .offer-tile {
    flex: 1 0 30%;
    margin: $margin-base;
  }
}
</style>
