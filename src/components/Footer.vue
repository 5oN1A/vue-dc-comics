<template>
  <footer>
    <div class="section_1">
      <div class="container">
        <ul class="d-flex">
          <!-- <li v-for="(item, i) in buyComicsItems" :key="i">
          <a :href="item.href"> 
              <img :src="item.src" :alt="i"/>
              <p>{{item.title}}</p>
          </a>
        </li> -->
          <li>
            <a class="d-flex" href="#">
              <div class="card">
                <img
                  src="../assets/buy-comics-digital-comics.png"
                  alt="digital comics"
                />
              </div>
              <h3>DIGITAL COMICS</h3>
            </a>
          </li>
          <li>
            <a class="d-flex" href="#">
              <div class="card">
                <img
                  src="../assets/buy-comics-merchandise.png"
                  alt="digital comics"
                />
              </div>
              <h3>DC MERCHANDISE</h3>
            </a>
          </li>
          <li>
            <a class="d-flex" href="#">
              <div class="card">
                <img
                  src="../assets/buy-comics-subscriptions.png"
                  alt="digital comics"
                />
              </div>
              <h3>SUBSCRIPTION</h3>
            </a>
          </li>
          <li>
            <a class="d-flex" href="#">
              <div class="card">
                <img
                  src="../assets/buy-comics-shop-locator.png"
                  alt="digital comics"
                />
              </div>
              <h3>COMIC SHOP LOCATOR</h3>
            </a>
          </li>
          <li>
            <a class="d-flex" href="#">
              <div class="card">
                <img
                  src="../assets/buy-dc-power-visa.svg"
                  alt="digital comics"
                />
              </div>
              <h3>DC POWER VISA</h3>
            </a>
          </li>
        </ul>
      </div>
    </div>
    <div class="section_2">
      <div class="container">
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

    <div class="container"></div>
  </footer>
</template>










<script>
export default {
  name: "Footer",
  data() {
    return {
      /*  buyComicsItems: [
        {
          title: "DIGITAL COMICS",
          href: "#",
          src: "../assets/buy-comics-digital-comics.png",
          
        },
        {
          title: "DC MERCHANDISE",
          href: "#",
          src: "../assets/buy-comics-merchandise.png",
        },
        {
          title: "SUBSCRIPTION",
          href: "#",
          src: "../assets/buy-comics-subscriptions.png",
        },
        {
          title: "COMIC SHOP LOCATOR",
          href: "#",
          src: "../assets/buy-comics-shop-locator.png",
        },
        {
          title: "DC POWER VISA",
          href: "#",
          src: "../assets/buy-dc-power-visa.png",
        },
      ], */
    };
  },
};
</script>



