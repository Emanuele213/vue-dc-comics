<template>
  <footer>
    <div class="bg-image">
      <div class="footer-container">
        <div class="other-things">
          <ul>
            <h2>DC COMICS</h2>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
            <h2 class="space-top">SHOP</h2>
            <li>Shop DC</li>
            <li>Shop DC Collectibles</li>
          </ul>
          <ul>
            <h2>DC</h2>
            <li>Terms Of Use</li>
            <li>Privacy policy (NEw)</li>
            <li>Ad Chois</li>
            <li>Advertising</li>
            <li>Jobs</li>
            <li>Subscriptions</li>
            <li>Talent Workshops</li>
            <li>CPSC Certificates</li>
            <li>Ratings</li>
            <li>Shop Help</li>
            <li>Contact Us</li>
          </ul>
          <ul>
            <h2>SITES</h2>
            <li>DC</li>
            <li>MAD Magazine</li>
            <li>DC Kids</li>
            <li>DC Universe</li>
            <li>DC Power Visa</li>
          </ul>
        </div>
      </div>
      <div>
        <img src="@/img/dc-logo-bg.png" alt="logo storto">
      </div>
    </div>
    <div class="bg-black-down">
      <div class="footer-down-container">
        <div>
          <button class="mod-btn">SIGN-UP NOW!</button>
        </div>
        <div class="social-media">
          <h2>FOLLOW US</h2>
          <div class="">
            <img src="@/img/footer-facebook.png" alt="facebook">
          </div>
          <div class="">
            <img src="@/img/footer-twitter.png" alt="twitter">
          </div>
          <div class="">
            <img src="@/img/footer-youtube.png" alt="youtube">
          </div>
          <div class="">
            <img src="@/img/footer-pinterest.png" alt="pinterest">
          </div>
          <div class="">
            <img src="@/img/footer-periscope.png" alt="periscope">
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'FooterPage',
};
</script>

<style lang="scss" scoped>
  .bg-image {
    background-image: url('@/img/footer-bg.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
    top: 79px;
    display: flex;
  }

  .footer-container {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .other-things {
    color: white;
    display: flex;
    gap: 3rem;
  }

  .space-top {
    margin-top: 2rem;
  }

  .bg-black-down {
    background-color: #303030;
    position: relative;
    height: 100px;
  }

  .footer-down-container {
    max-width: 1200px;
    margin: 0 auto;
    height: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .mod-btn {
    background-color: #303030;
    color: white;
    border: 2px solid #0282F9;
    padding: 1rem;
  }

  .social-media {
    color: #0282F9;
    display: flex;
    align-items: center;
    gap: 1rem;
  }
</style>
