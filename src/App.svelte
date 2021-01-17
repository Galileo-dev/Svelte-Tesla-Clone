<script>
  import Header from "./components/Header.svelte";
  import Item from "./components/item.svelte";
  let Accesories = "assets/Desktop-Accessories.jpg";
  let ModelS = "assets/Desktop-ModelS.jpeg";
  let Model3 = "assets/Desktop-Model3.jpeg";
  let ModelX = "assets/Desktop-ModelX.jpeg";
  let ModelY = "assets/Desktop-ModelY.jpeg";
  let SolarPanels = "assets/Desktop-SolarPanels.jpeg";
  let SolarRoof = "assets/Desktop-SolarRoof.jpeg";
</script>

<main>
  <!-- {HEADER} -->
  <Header />
  <div class="app__itemsContainer">
    <Item
      title="Lowest Cost Solar Panels in America"
      desc="Money-back guarantee"
      backgroundImg={SolarPanels}
      leftBtnTxt="ORDER NOW"
      leftBtnLink=""
      rightBtnTxt="LEARN MORE"
      rightBtnLink=""
      twoButtons="true"
      first
    />
    <Item
      title="Model S"
      desc="Starting at $69,420"
      backgroundImg={ModelS}
      leftBtnTxt="CUSTOM ORDER"
      leftBtnLink=""
      rightBtnTxt="EXISTING INVENTORY"
      rightBtnLink=""
      twoButtons="true"
    />
    <Item
      title="Model 3"
      desc="Order Online for Touchless Delivery"
      backgroundImg={Model3}
      leftBtnTxt="CUSTOM ORDER"
      leftBtnLink=""
      rightBtnTxt="EXISTING INVENTORY"
      rightBtnLink=""
      twoButtons="true"
    />
    <Item
      title="Model X"
      desc="Order Online for Touchless Delivery"
      backgroundImg={ModelX}
      leftBtnTxt="CUSTOM ORDER"
      leftBtnLink=""
      rightBtnTxt="EXISTING INVENTORY"
      rightBtnLink=""
      twoButtons="true"
    />
    <Item
      title="Model Y"
      desc="Order Online for Touchless Delivery"
      backgroundImg={ModelY}
      leftBtnTxt="CUSTOM ORDER"
      leftBtnLink=""
      rightBtnTxt="LEARN MORE"
      rightBtnLink=""
      twoButtons="true"
    />
    <Item
      title="Solar for New Roofs"
      desc="Solar Roof Costs Less Than a New Roof Plus Solar Panels"
      backgroundImg={SolarRoof}
      leftBtnTxt="ORDER NOW"
      leftBtnLink=""
      rightBtnTxt="LEARN MORE"
      rightBtnLink=""
      twoButtons="true"
    />
    <Item
      title="Accessories"
      desc=""
      backgroundImg={Accesories}
      leftBtnTxt="SHOP"
      leftBtnLink=""
      rightBtnTxt="LEARN MORE"
      rightBtnLink=""
      twoButtons="false"
    />
  </div>
</main>

<style>
</style>
