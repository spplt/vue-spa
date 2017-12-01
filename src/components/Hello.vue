<template lang="html">
  <div class="greeting">
    <h2>
      {{ greeting }} Welcome to the Vue.js blog
    </h2>
    <img src="../assets/logo.png" alt="vuejs logo">
    <table class="table table-hover">
      <thead>
        <tr>
          <td>Rank</td>
          <td>Name</td>
          <td>Symbol</td>
          <td>Price (USD)</td>
          <td>1H</td>
          <td>1D</td>
          <td>1W</td>
          <td>Market Cap (USD)</td>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
          <td>
            <span>+</span>
          </td>
          <td>
            <span>+</span>
          </td>
          <td>
            <span>+</span>
          </td>
          <td></td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script>
module.exports = {
  data: function () {
    return {
      greeting: 'Hello'
    }
  }
}
</script>

<style lang="scss">
  .greeting {
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    flex-direction: column;
  }
</style>
