<template lang="html">
  <div class="sub-board">
    <table>
      <tr>
        <Square></Square>
        <Square></Square>
        <Square></Square>
        <Square></Square>
      </tr>
      <tr>
        <Square></Square>
        <Square></Square>
        <Square></Square>
        <Square></Square>
      </tr>
      <tr>
        <Square></Square>
        <Square></Square>
        <Square></Square>
        <Square></Square>
      </tr>
      <tr>
        <Square></Square>
        <Square></Square>
        <Square></Square>
        <Square></Square>
      </tr>
    </table>
  </div>
</template>

<script>
import Square from './Square.vue'

export default {
  components: {
    Square
  }
}
</script>

<style lang="css" scoped>
  .sub-board {
    display: inline-block;
  }
</style>
