<script>
  import Button from "./button.svelte";
  import ExpandDown from "svelte-material-icons/ChevronDown.svelte";

  export let title,
    desc,
    backgroundImg,
    leftBtnTxt,
    leftBtnLink,
    rightBtnTxt,
    rightBtnLink,
    first,
    twoButtons;
</script>

<main class="item" style="background-image: url('{backgroundImg}')">
  <div class="item__container">
    <div class="item__text">
      <p>{title}</p>
      <div class="item__textDesc">
        <p>{desc}</p>
      </div>
    </div>
    <div class="item_lowerThird">
      <div class="item__buttons" />
      <Button imp="primary" text="{leftBtnTxt}," link={leftBtnLink} />
      {#if twoButtons}
        <Button imp="secondary" text="{rightBtnTxt}," link={rightBtnLink} />
      {/if}
    </div>
    {#if first}
      <div class="item__expand">
        <ExpandDown size="1.5em" />
      </div>
    {/if}
  </div>
</main>

<style>
  .item {
    height: 100vh;
    width: 100vw;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    display: flex;
    justify-content: center;
  }

  .item__container {
    width: 40vw;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .item__text {
    margin-top: 20%;
    display: flex;
    flex-direction: column;
    font-size: 34px;
    color: #393c41;
    align-items: center;
    flex: 1;
  }
  .item__textDesc {
    font-weight: 200;
    font-size: 14px;
  }

  .item_lowerThird {
    margin-bottom: 5%;
    display: flex;
    flex-direction: column;
  }

  .item__buttons {
    display: flex;
  }

  .item__expand {
    color: white;
    /* width: 100%; */
    margin-top: 3%;
    justify-content: center;
  }
</style>
