<script setup>
import { ref } from 'vue'
const count = ref(0)
</script>

<template>
  <div class="upper-footer">

    <div class="container">
      <div class="links">
        <ul class="list-1">
          <li>
            <h4>DC COMICS</h4>
          </li>

          <li>
            <a href="">Characters</a>
          </li>

          <li>
            <a href="">Comics</a>
          </li>

          <li>
            <a href="">Movies</a>
          </li>

          <li>
            <a href="">Tv</a>
          </li>

          <li>
            <a href="">Games</a>
          </li>

          <li>
            <a href="">Videos</a>
          </li>

          <li>
            <a href="">News</a>
          </li>

          <li>
            <ul class="list-2">
              <li>
                <h4>SHOP</h4>
              </li>
              <li>
                <a href="">Shop DC</a>
              </li>
              <li>
                <a href="">Shop DC Collectibles</a>
              </li>
            </ul>
          </li>
        </ul>
        <ul class="list-3">
          <li>
            <h4>DC</h4>
          </li>
          <li>
            <a href="">Terms of Use</a>
          </li>
          <li>
            <a href="">Privacy Policy</a>
          </li>
          <li>
            <a href="">Ad Choices</a>
          </li>
          <li>
            <a href="">Advertising</a>
          </li>
          <li>
            <a href="">Jobs</a>
          </li>
          <li>
            <a href="">Subscriptions</a>
          </li>
          <li>
            <a href="">Talent Workshops</a>
          </li>
          <li>
            <a href="">CPSC Certificates</a>
          </li>
          <li>
            <a href="">Ratings</a>
          </li>
          <li>
            <a href="">Shop help</a>
          </li>
          <li>
            <a href="">Contact Us</a>
          </li>
        </ul>
        <ul class="list-4">
          <li>
            <h4>SITES</h4>
          </li>
          <li>
            <a href="">DC</a>
          </li>
          <li>
            <a href="">Mad Magazine</a>
          </li>
          <li>
            <a href="">DC Kids</a>
          </li>
          <li>
            <a href="">DC Universe</a>
          </li>
          <li>
            <a href="">DC Power Visa</a>
          </li>
        </ul>
      </div>
      <img src="/src/assets/img/dc-logo-bg.png" alt="">
    </div>
  </div>




  <div class="lower-footer">
    <div class="container">
      <div class="sign-up-button">
        <button>SIGN UP NOW!</button>
      </div>
      <div class="follow-us">
        <p>FOLLOW US</p>
        <img src="/src/assets/img/footer-facebook.png" alt="">
        <img src="/src/assets/img/footer-twitter.png" alt="">
        <img src="/src/assets/img/footer-youtube.png" alt="">
        <img src="/src/assets/img/footer-pinterest.png" alt="">
        <img src="/src/assets/img/footer-periscope.png" alt="">

      </div>

    </div>
  </div>
</template>

<style lang="scss" scoped>
.upper-footer {
  background-image: url("src/assets/img/footer-bg.jpg");
  height: 400px;
  width: 100%;
  z-index: 0;
  position: relative;

  .container {
    width: 75%;
    height: 100%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;

    .links {
      display: flex;

      h4 {
        color: white;
      }
    }

    img {
      width: 50%;
    }
  }
}

.lower-footer {
  height: 100px;
  width: 100%;
  background-color: rgb(68, 67, 67);
  z-index: 1;
  position: relative;

  .container {
    width: 75%;
    height: 100%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;

    button {
      border: 2px solid rgb(0, 123, 255);
      background-color: transparent;
      padding: 10px;
      color: white;
    }

    .follow-us {
      display: flex;
      align-items: center;
      gap: 10px;

      p {
        color: rgb(0, 132, 255);
        font-weight: bold;
      }
    }
  }


}
</style>
