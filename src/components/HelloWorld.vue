<template>
<div class="div1">
  <div class="container">
    <h1>We bring solution to <span>make life</span> <span>easier</span></h1>
    <i class="fas fa-arrow-down"></i>
  </div>
  </div>
  <div class="shape">
</div>  
<div class="div2">
  <div class="container">
    <div class="services">
      <div class="icon"><img :src="require('@/assets/icon1.png')"></div>
      <h3>Software Dev</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. </p>
      <span>See More<i class="fas fa-angle-right"></i></span>
    </div>
    <div class="services">
      <div class="icon"><img :src="require('@/assets/icon2.png')"></div>
      <h3>Web Dev</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. </p>
      <span>See More<i class="fas fa-angle-right"></i></span>
    </div>
    <div class="services">
      <div class="icon"><img :src="require('@/assets/icon3.png')"></div>
      <h3>UX/UI Desgin</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. </p>
      <span>See More<i class="fas fa-angle-right"></i></span>
    </div>
    <div class="services">
      <div class="icon"><img :src="require('@/assets/icon4.png')"></div>
      <h3>Mobile Dev</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. </p>
      <span>See More<i class="fas fa-angle-right"></i></span>
    </div>
  </div>
</div>
<div class="div3">
<div class="container">
  <div class="left">
    <img :src="require('@/assets/img.jpg')">
  </div>
  <div class="right">
    <div>
      <p>About</p>
      <h2>Who we <span>are</span></h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit. </p>
      <button>More Details</button>
    </div> 
  </div>
</div>
</div>
<div class="div4">
  <div class="container">
    <h2>Want To Start A New Project With Us? Let's Start!</h2>
    <button>Contact Now!</button>
  </div>
  </div>
  <div class="shape">
</div>
<div class="div5">
  <h2>Our <span>Pricing</span> Plan</h2>
  <div class="container">
    <div class="prices">
      <p>Starter Plan</p>
      <h3>$24.99</h3>
      <p>Per Month</p>
      <ul>
        <li>1 - 3 Website pages</li>
        <li>Responsive Design</li>
        <li>Social Media Integration</li>
        <li>Contact Form</li>
        <li>Google Maps</li>
        <li>Photo Sourcing</li>
        <li>2 Rounds of Revisions</li>
        <li>Website Design Mock Up</li>
      </ul>
      <p>https://my-template.online/numerio/home.hmtl</p>
    </div>
    <div class="prices">
      <p>Starter Plan</p>
      <h3>$27.99</h3>
      <p>Per Month</p>
      <ul>
        <li>1 - 3 Website pages</li>
        <li>Responsive Design</li>
        <li>Social Media Integration</li>
        <li>Contact Form</li>
        <li>Google Maps</li>
        <li>Photo Sourcing</li>
        <li>2 Rounds of Revisions</li>
        <li>Website Design Mock Up</li>
      </ul>
      <p>https://my-template.online/numerio/home.hmtl</p>
    </div>
    <div class="prices">
      <p>Starter Plan</p>
      <h3>$33.99</h3>
      <p>Per Month</p>
      <ul>
        <li>1 - 3 Website pages</li>
        <li>Responsive Design</li>
        <li>Social Media Integration</li>
        <li>Contact Form</li>
        <li>Google Maps</li>
        <li>Photo Sourcing</li>
        <li>2 Rounds of Revisions</li>
        <li>Website Design Mock Up</li>
      </ul>
      <p>https://my-template.online/numerio/home.hmtl</p>
    </div>
  </div>
<button>See All Prices</button>
</div>
<div class="footer">
  <div class="container">
    <div class="logo">
      <h2>SAMPLE</h2>
    </div>
    <div class="link">
      <p>Usefull Links</p>
      <ul>
        <li>Our Company</li>
        <li>About Us</li>
        <li>Services</li>
        <li>Contact Us</li>
        <li>FAQ</li>
      </ul>
    </div>
    <div class="legal">
      <p>Legal</p>
      <ul>
        <li>Privacy Policy</li>
        <li>Terms of Service</li>
        <li>Legal Notice</li>
      </ul>
    </div>
    <div class="info">
      <p>sample.sample@gmail.com</p>
      <p>Get Connected with us!<i class='fa fa-facebook'></i></p>
    </div>
  </div>
  <div class="container">
    <p>© 2021 Sample. All Right Reserved.</p>
  </div>
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

i.fas.fa-arrow-down {
    color: #fed917;
    font-size: 20px;
}

i.fas.fa-angle-right {
    font-size: 25px;
    margin-left: 10px;
}

.div1 {
  background: #F6F7F9;
  padding: 6em 4em 1em 4em;
}

.div1 h1{
  width: 30%;
  margin: auto;
  font-family: poppins;
  font-size: 50px;
  font-weight: 400;
  color:#000;
  margin-bottom: 1em;
}

.div1 h1 span:nth-child(1){
  font-weight: 700;
}

.div1 h1 span:nth-child(2){
  color:#FED917;
}
.shape {
  width: 100%;
  height: 250px;
  background: transparent;
  border-top-left-radius: 50% 50%;
  border-top-right-radius: 50% 50%;
  position: relative;
  transform: rotate(180deg);
  overflow: hidden;
}

.shape:after {
  content: "";
  width: 100%;
  height: 250px;
  position: absolute;
  top: 0;
  left: 0;
  background: #F6F7F9;
}

.div2 {
    margin-top: -10em;
    position: relative;
    z-index: 2;
}

.div2 .container {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-gap: 2em;
  max-width: 1140px;
  margin: auto;
}

.div2 .services {
    background: #fff;
    box-shadow: 0px 5px 6px #0000004a;
    padding: 2em;
    border-radius: 20px;
}

.div2 .services h3 {
  font-size: 20px;
  font-weight: 700;
}
.div2 .services span {
  display: flex;
  align-items: center;
  justify-content: center;
  color: #FED917;
}

.div2 .services .icon{
  text-align:left;
  margin-bottom: 35px;
}

.div2 .services .icon img {
    height: 55px;
}

.div3 {
  position: relative;
  padding: 10em 0px 5em;
}

.div3 .container {
  max-width: 1140px;
  margin: auto;
  display: grid;
  grid-template-columns: repeat(2, 1fr);  
}

.div3 .container .left {
  text-align: left;
}

.div3 .container .left img{
  width: 100%;
  height: auto;
}

.div3 .container .right {
  text-align: left;
  padding-left: 3em;
  display: flex;
  align-items: center;
}

.div3 .container .right p:nth-child(1) {
  margin: 0;
  font-weight: 500;
}

.div3 .container .right h2 {
  font-size: 35px;
  margin: 2px 0;
}
.div3 .container .right h2 span{
  color:#fed917;
}

.div3 .container .right button {
    padding: 1em 2.5em;
    border-radius: 5px;
    border: 0;
    font-weight: 600;
    background: #fed917;
    margin-top: 4em;
    font-family: poppins;
}


.div4 {
  position: relative;
  background: #F6F7F9;
  padding: 10em 0px 0em;
}

.div4 .container {
  max-width: 1140px;
  margin: auto;
}


.div4 h2 { 
  font-size: 50px;
  width: 70%;
  margin: auto;
}

.div4 button {
  padding: 0.5em 1em;
  border-radius: 5px;
  border: 0;
  font-weight: 600;
  background: #fed917;
  margin-top: 1em;
  font-family: poppins;
}

.div5 {
  position: relative;
  padding: 10em 0px 5em;
}

.div5 h2 {
    font-size: 35px;
}

.div5 h2 span{
    color:#fed917;
}

.div5 .container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 2em;
  max-width: 1140px;
  margin: auto;
  padding-bottom: 2em;
}

.div5 .container .prices{
    background: #fff;
    box-shadow: 0px 5px 6px #0000004a;
    padding: 4em 2em 1em;
    border-radius: 20px;
    color:#000;
}

.div5 .container .prices:nth-child(2){
    color:#fff;
    background: #fed917;
    box-shadow: 0px 5px 6px #0000004a;
    padding: 4em 2em 1em;
    border-radius: 20px;
}

.div5 .container .prices p:nth-child(1) {
    font-size: 22px;
    font-weight: 700;
    margin: 0;
}

.div5 .container .prices h3 {
    font-size: 50px;
    margin: 0;
}

.div5 .container .prices p:nth-child(3) {
    font-size: 22px;
    font-weight: 700;
    margin: 0;
}

.div5 .container .prices p:nth-child(5) {
    font-size: 11px;
    font-weight: 700;
}

.div5 .container .prices ul {
    padding: 1.5em 2em;
}

.div5 .container .prices ul li {
    text-align: left;
    font-weight: 700;
}

.div5 button {
  padding: 0.5em 1em;
  border-radius: 5px;
  border: 0;
  font-weight: 600;
  background: #fed917;
  margin-top: 1em;
  font-family: poppins;
}


.footer {
  position: relative;
  background: #F6F7F9;
  padding: 5em 0px 0em;  
}

.footer .container {
  display: grid;
  grid-template-columns: 30% 20% 20% 30%;
  max-width: 1140px;
  margin: auto;
  border-bottom: 2px solid #000;
  padding-bottom: 1em;
}

.footer .container .logo h2 {
    margin: 0;
    text-align: left;
    font-weight: 900;
    font-size: 40px;
}

.footer .container:nth-child(2) {
  display: block;
  max-width: 1140px;
  margin: auto;
  border-bottom: 0;
  text-align: center;
  padding: 1em;
}

.footer .container .link p {
    margin: 0;
    text-align: left;
    font-weight: 700;
}

.footer .container .link ul {
    list-style-type: none;
    text-align: left;
    padding-left: 0;
}

.footer .container .link ul li {
    padding-bottom: 5px;
}

.footer .container .legal p {
    margin: 0;
    text-align: left;
    font-weight: 700;
}

.footer .container .legal ul {
    list-style-type: none;
    text-align: left;
    padding-left: 0;
}

.footer .container .legal ul li {
    padding-bottom: 5px;
}

.footer .container .info {
    text-align: left;
}

.footer .container .info p:nth-child(1) {
    font-size: 22px;
    font-weight: 600;
}



</style>
