<template lang="html">
  <div>
    <table>
      <tr>
        <SubBoard style="margin-right:1em;"></SubBoard>
        <SubBoard></SubBoard>
      </tr>
      <hr>
      <tr>
        <SubBoard style="margin-right:1em;"></SubBoard>
        <SubBoard></SubBoard>
      </tr>
    </table>
  </div>
</template>

<script>
import SubBoard from './SubBoard.vue'

export default {
  components: {
    SubBoard
  }
}
</script>

<style lang="css" scoped>
  tr {
    margin: 0;
  }
  hr {
    border-width: .2em;
    margin-bottom: 1em;
  }
</style>
