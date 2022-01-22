<script>
</script>

<main class="center">
  <div class="header">
    <div class="header__logo">
      <img
        src="assets/teslaLogoSmall.svg"
        alt="small tesla logo"
        width="120px"
      />
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
  </div>
</main>

<style>
  .center {
    display: flex;
    justify-content: center;
  }

  .header {
    align-self: center;
    display: flex;
    background-color: transparent;
    background: none;
    position: fixed;
    width: 95%;
    top: 0;
    margin: 15px;
    z-index: 100;
  }

  .header__logo {
    flex: 1; /* shorthand for: flex-grow: 1, flex-shrink: 1, flex-basis: 0 */
    display: flex;
    justify-content: flex-start;
    align-items: center;
    /* border: 1px dashed red; */
  }

  .header__center {
    flex: 10;
    display: flex;
    justify-content: center;
    align-items: center;
    /* border: 1px dashed red; */
  }

  .header__center > p {
    margin: 10px;
    text-transform: uppercase;
  }

  .header__right {
    flex: 1;
    display: flex;
    justify-content: flex-end;
    align-items: center;
    /* border: 1px dashed red; */
    white-space: nowrap;
  }

  .header__right > p {
    margin: 10px;
  }
</style>
