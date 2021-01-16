<script>
</script>

<main class="header">
  <div class="header__logo">
    <img src="assets/teslaLogoSmall.svg" alt="small tesla logo" />
  </div>

  <div class="header__center">
    <p>Model S</p>
    <p>Model 3</p>
    <p>Model X</p>
    <p>Model Y</p>
    <p>Solar Roof</p>
    <p>Solar Panel</p>
  </div>

  <div class="header__right">
    <p>Shop</p>
    <p>Tesla Account</p>
  </div>
</main>

<style>
  .header {
    display: flex;
    background-color: transparent;
    background: none;
    position: fixed;
    width: 100vw;
    top: 0;
    margin: 15px;
    z-index: 100;
  }

  .header__logo {
    height: 24px;
    width: 100px;
    margin-top: 7px;
  }

  .header__center {
    flex: 1;
    display: flex;
    justify-content: center;
  }

  .header__center > p {
    margin: 10px;
    text-transform: uppercase;
  }

  .header__right {
    display: flex;
    justify-content: flex-end;
    text-transform: uppercase;
  }

  .header__right > p {
    margin: 10px;
  }
</style>
