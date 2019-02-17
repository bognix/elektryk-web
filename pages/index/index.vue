<template>
  <div class="section">
    <div class="container offer-tiles">
      <offer-tile
        :items="['Montaż​ ​urządzeń​ ​AGD​ ​i​ ​RTV', 'Instalacja​ ​oświetlenia​ ​wewnętrznego​ ​oraz​ ​zewnętrznego', 'Przyłącza​ ​do​ ​sieci​ ​energetycznej']"
        class="offer-tile"
        title="Instalacje elektryczne"
      />
      <offer-tile
        class="offer-tile"
        title="Prace ogólnobudowlane"
      />
      <offer-tile
        class="offer-tile"
        title="Serwis kotłów grzewczych"
      />
      <offer-tile
        class="offer-tile"
        title="Automatyka domowa"
      />
      <offer-tile
        class="offer-tile"
        title="Monitoring i instalacje alarmowe"
      />
      <offer-tile
        class="offer-tile"
        title="Możliwość stałej współpracy"
      />
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
