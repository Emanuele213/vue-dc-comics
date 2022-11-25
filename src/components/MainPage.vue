<template>
  <main class="main-relative">
    <div class="bg-black">
      <img src="@/img/jumbotron.jpg" alt="teen titans">
      <div class="h1-main-container">
        <h1>CURRENT SERIES</h1>
      </div>
    </div>
    <div class="bg-black-comics">
      <div class="comics-container">
        <CardComics
        v-for="objComics in ArrComics"
        :key="objComics.series"
        :comic="objComics"
        />
      </div>
    </div>
    <div class="bg-blue">
      <div class="blue-main-container">
        <ul class="dc-menu">
          <li class="icon-title">
            <div>
              <img
                src="@/img/buy-comics-digital-comics.png"
                alt="digital comics"
                class="img-size"
              />
            </div>
            DIGITAL COMICS
          </li>
          <li class="icon-title">
            <div>
              <img
                src="@/img/buy-comics-merchandise.png"
                alt="merchandise"
                class="img-size"
              />
            </div>
            DC MERCHANDISE
          </li>
          <li class="icon-title">
            <div>
              <img
                src="@/img/buy-comics-subscriptions.png"
                alt="iscriviti"
                class="img-size"
              />
            </div>
            SUBSCRIPTION
          </li>
          <li class="icon-title">
            <div>
              <img
                src="@/img/buy-comics-shop-locator.png"
                alt="localizzatore shop"
                class="img-size"
              />
            </div>
            COMIC SHOP LOCATOR
          </li>
          <li class="icon-title">
            <div>
              <img
                src="@/img/buy-dc-power-visa.svg"
                alt="carta visa"
                class="img-size"
              />
            </div>
            DC POWER VISA
          </li>
        </ul>
      </div>
    </div>
  </main>
</template>

<script>
import CardComics from '@/components/CardComics.vue';
import ArrComics from '@/components/ArrComics.json';

export default {
  name: 'MainPage',
  components: {
    CardComics,
  },
  data() {
    return {
      ArrComics,
    };
  },
};
</script>

<style lang="scss" scoped>
.main-relative {
  position: relative;
}
.bg-black {
  img {
    object-position: top;
    object-fit: cover;
    height: 320px;
    width: 100%;
  }
}
.h1-main-container {
  max-width: 1200px;
  margin: 0 auto;
  color: white;
  position: relative;

  h1 {
    background-color: #0282F9;
    width: fit-content;
    padding: 1rem;
    position: absolute;
    z-index: 10;
    bottom: -36px;
  }
}

.bg-black-comics {
  background-color: #1C1C1C;
  position: relative;
  top: -4px;
  padding-bottom: 3rem;

  .comics-container {
    max-width: 1300px;
    margin: 0 auto;
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
    /* margin-top: 0rem; */
    justify-content: center;
  }
}

.bg-blue {
  background-color: #0282f9;
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
