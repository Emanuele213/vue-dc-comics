<template>
  <div class="header-container">
    <div>
      <img src="@/img/dc-logo.png" alt="logo dc" class="img-mod">
    </div>
    <nav>
      <ul class="flex-nav-bar">
        <li class="nav-li-blue">CHARACTERS</li>
        <li class="nav-li-blue">COMICS</li>
        <li class="nav-li-blue">MOVIES</li>
        <li class="nav-li-blue">TV</li>
        <li class="nav-li-blue">GAMES</li>
        <li class="nav-li-blue">COLLECTIBLES</li>
        <li class="nav-li-blue">VIDEOS</li>
        <li class="nav-li-blue">FANS</li>
        <li class="nav-li-blue">NEWS</li>
        <li class="nav-li-blue">SHOPS</li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
  .header-container {
    background-color: white;
    height: 100%;
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .img-mod {
     margin: 1rem 0;
  }

  .flex-nav-bar {
    height: 100%;
    display: flex;
    gap: 1rem;
  }

  .nav-li-blue {
    padding: 50px 0;
    border-bottom: 5px solid white;
  }
  .nav-li-blue:hover {
    color: blue;
    border-bottom: 5px solid blue;
  }
</style>
