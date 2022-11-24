<template>
  <div class="main-relative">
    <div class="bg-black">
      <div class="black-main-container">
        <h1>conten goes her</h1>
      </div>
    </div>
    <div class="bg-blue">
      <div class="blue-main-container">
        <ul class="dc-menu">
          <li class="icon-title">
            <div>
              <img src="@/img/buy-comics-digital-comics.png" alt="digital comics" class="img-size">
            </div>
            DIGITAL COMICS
          </li>
          <li class="icon-title">
            <div>
              <img src="@/img/buy-comics-merchandise.png" alt="merchandise" class="img-size">
            </div>
            DC MERCHANDISE
          </li>
          <li class="icon-title">
            <div>
              <img src="@/img/buy-comics-subscriptions.png" alt="iscriviti" class="img-size">
            </div>
            SUBSCRIPTION
          </li>
          <li class="icon-title">
            <div>
              <img src="@/img/buy-comics-shop-locator.png"
              alt="localizzatore shop" class="img-size">
            </div>
            COMIC SHOP LOCATOR
          </li>
          <li class="icon-title">
            <div>
              <img src="@/img/buy-dc-power-visa.svg" alt="carta visa" class="img-size">
            </div>
            DC POWER VISA
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
  .main-relative {
    position: relative;
  }
  .bg-black {
    background-color: #1C1C1C;
  }
  .black-main-container {
    max-width: 1200px;
    margin: 0 auto;
    color: white;
  }

  .bg-blue {
    background-color: #0282F9;
    position: absolute;
    width: 100%;
    z-index: 5;
  }

  .blue-main-container {
    max-width: 1200px;
    margin: 0 auto;
    color: white;
    display: flex;
    padding: 3rem 0;
  }

  .dc-menu {
    display: flex;
  }

  .icon-title {
    display: flex;
    align-items: center;
    gap: 1rem;

    .img-size {
      width: 50px;
      height: 70px;
      margin-left: 1rem;
    }
  }
</style>
