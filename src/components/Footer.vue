<template>
  <footer>
    <div class="section_1">
      <div class="container">
        <ul class="d-flex">
          <li v-for="(item, i) in buyComicsItems" :key="i">
            <a class="d-flex" :href="item.href">
              <div class="card">
                <img :src="item.src" :alt="i" />
              </div>
              <h3>{{ item.title }}</h3>
            </a>
          </li>
        </ul>
      </div>
    </div>

    <div class="section_2">
      <div class="container d-flex">
        <div class="col_1 p-right">
          <h3>DC COMICS</h3>
          <ul>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
          <h3>SHOP</h3>
          <ul>
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectibles</a></li>
          </ul>
        </div>
        <div class="col_2 p-right">
          <h3>DC</h3>
          <ul>
            <li><a href="#">Terms Of Use</a></li>
            <li><a href="#">Privacy Policy (New)</a></li>
            <li><a href="#">Ad Choices</a></li>
            <li><a href="#">Advertising</a></li>
            <li><a href="#">Jobs</a></li>
            <li><a href="#">Subscriptions</a></li>
            <li><a href="#">Talent Workshops</a></li>
            <li><a href="#">CPSC Certificates</a></li>
            <li><a href="#">Ratings</a></li>
            <li><a href="#">Shop Help</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </div>
        <div class="col_3">
          <h3>SITES</h3>
          <ul>
            <li><a href="#">DC</a></li>
            <li><a href="#">MAD Magazine</a></li>
            <li><a href="#">Dc Kids</a></li>
            <li><a href="#">DC Universe</a></li>
            <li><a href="#">DC Power Visa</a></li>
          </ul>
        </div>
        
      </div>
     
    </div>
    <div class="section_3">
      <div class="container d-flex">
        <a class="sign_up_button" href="#">SIGN-UP NOW</a>
        <div class="social_section d-flex">
          <h3>FOLLOW US</h3>
          <img src="@/assets/footer-facebook.png" alt="facebook icon" />
          <img src="@/assets/footer-twitter.png" alt="twitter icon" />
          <img src="@/assets/footer-youtube.png" alt="youtube icon" />
          <img src="@/assets/footer-pinterest.png" alt="pinterest icon" />
          <img src="@/assets/footer-periscope.png" alt="periscope icon" />
        </div>
      </div>
    </div>
  </footer>
</template>










<script>
export default {
  name: "Footer",
  data() {
    return {
      buyComicsItems: [
        {
          title: "DIGITAL COMICS",
          href: "#",
          src: require("@/assets/buy-comics-digital-comics.png"),
        },
        {
          title: "DC MERCHANDISE",
          href: "#",
          src: require("@/assets/buy-comics-merchandise.png"),
        },
        {
          title: "SUBSCRIPTION",
          href: "#",
          src: require("@/assets/buy-comics-subscriptions.png"),
        },
        {
          title: "COMIC SHOP LOCATOR",
          href: "#",
          src: require("@/assets/buy-comics-shop-locator.png"),
        },
        {
          title: "DC POWER VISA",
          href: "#",
          src: require("@/assets/buy-dc-power-visa.svg"),
        },
      ],
    };
  },
};
</script>



