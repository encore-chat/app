<svelte:head>
  <title>Encore - Touch grass.</title>
</svelte:head>

<div class="main">
  <img src="/encore.svg" alt="Encore logo" />
  <h1>Encore</h1>
  <h2>Touch grass.</h2>
</div>

<style lang="scss">
  .main {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100vh;

    img {
      height: 20%;
    }

    h1 {
      font-size: 4em;
    }

    h2 {
      font-size: 2em;
      color: #f6f6f6aa;
    }

    h1,
    h2 {
      padding: 0;
      margin: 0;
    }
  }
</style>
