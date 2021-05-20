<template>
    <footer>
        <div class="blue-line">
            <ul>
                <!-- <li v-for="(link, index) in links" :key="index">
                    <img :src="link.img" alt="">
                    <a :href="link.url">{{link.text}}</a>
                </li> -->
                <li>
                    <img src="@/assets/img/buy-comics-digital-comics.png" alt="">
                    <a href="#">DIGITAL COMICS</a>
                </li>
                <li>
                    <img src="@/assets/img/buy-comics-merchandise.png" alt="">
                    <a href="#">DC MERCHANDISE</a>
                </li>
                <li>
                    <img src="@/assets/img/buy-comics-shop-locator.png" alt="">
                    <a href="#">SUBSCRIPTION</a>
                </li>
                <li>
                    <img src="@/assets/img/buy-comics-subscriptions.png" alt="">
                    <a href="#">COMIC SHOP LOCATOR</a>
                </li>
                <li>
                    <img src="@/assets/img/buy-dc-power-visa.svg" alt="">
                    <a href="#">DC POWER VISA</a>
                </li>

            </ul>
        </div>
        <div class="terms">

            <div class="container">
                <div class="listaDC">
                  <section>
                      <h5>dc comics</h5>
                      <ul>
                          <li><a href="#">Characters</a></li>
                          <li><a href="#">Comics</a></li>
                          <li><a href="#">Movies</a></li>
                          <li><a href="#">TV</a></li>
                          <li><a href="#">Games</a></li>
                          <li><a href="#">Videos</a></li>
                          <li><a href="#">News</a></li>
                      </ul>
                      <h5>shop</h5>
                      <ul>
                          <li><a href="#">Shop DC</a></li>
                          <li><a href="#">Shop DC Collectibles</a></li>
                          
                         
                      </ul>
                  </section>
                  <section>
                      <h5>DC</h5>
                      <ul>
                          <li><a href="">Terms Of Use</a></li>
                          <li><a href="">Privacy policy (New)</a></li>
                          <li><a href="">Ad Choices</a></li>
                          <li><a href="">Advertising</a></li>
                          <li><a href="">Jobs</a></li>
                          <li><a href="">Subscriptions</a></li>
                          <li><a href="">Talent Workshops</a></li>
                          <li><a href="">CPSC Certificates</a></li>
                          <li><a href="">Ratings</a></li>
                          <li><a href="">Shop Help</a></li>
                          <li><a href="">Contact Us</a></li>
                      </ul>
                  </section>
                  <section>
                      <h5>SITES</h5>
                      <ul>
                          <li><a href="">DC</a></li>
                          <li><a href="">MAD Magazine</a></li>
                          <li><a href="">DC Kids</a></li>
                          <li><a href="">DC Universe</a></li>
                          <li><a href="">DC Power Visa</a></li>
                      </ul>
                  </section>
                </div>

                <div class="logoDC">

                 </div>
            </div>
            
        </div>
        <div class="sign">
            <div class="container">
            <div class="footer-left">
                <a href="">SIGN UP NOW!</a>
            </div>
            <div class="footer-right">
                <ul>
                    <li><a href="#">FOLLOW US</a></li>
                    <li><a href="#"></a><img src="@/assets/img/footer-facebook.png" alt=""></li>
                    <li><a href="#"></a><img src="@/assets/img/footer-periscope.png" alt=""></li>
                    <li><a href="#"></a><img src="@/assets/img/footer-pinterest.png" alt=""></li>
                    <li><a href="#"></a><img src="@/assets/img/footer-twitter.png" alt=""></li>
                    <li><a href="#"></a><img src="@/assets/img/footer-youtube.png" alt=""></li>
                
                </ul>
            </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'FooterDC',
    data(){
        return{
            links:[
                {
                    text: 'DIGITAL COMICS',
                    img: 'comics-digital-comics.png',
                    url: '#'
                },
                {
                    text: 'DC MERCHANDISE',
                    img: 'comics-merchandise.png',
                    url: '#'
                },
                {
                    text: 'SUBSCRIPTION',
                    img: 'comics-shop-locator.png',
                    url: '#'
                },
                {
                    text: 'COMIC SHOP LOCATOR',
                    img: 'comics-subscriptions.png',
                    url: '#'
                },
                {
                    text: 'DC POWER VISA',
                    img: 'dc-power-visa.svg',
                    url: '#'
                }
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
 @import '../assets/style/vars.scss';
    footer{
        height: 50vh;
        /* blue-line */
        @import '../assets/style/footer-blue.scss';
        /* background con sfondo DC */
        @import '../assets/style/footer-terms.scss';
        /* Sign Up */
        @import '../assets/style/footer-sign.scss';
    }
</style>