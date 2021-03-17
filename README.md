<!DOCTYPE html>
<html lang="en">
<title>Gabbys Webpage</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Poppins">
<style>
body,h1,h2,h3,h4,h5 {font-family: "Poppins", sans-serif}
body {font-size:16px;}
.w3-half img{margin-bottom:-6px;margin-top:16px;opacity:0.8;cursor:pointer}
.w3-half img:hover{opacity:1}
</style>
<body>

<!-- Sidebar/menu -->
<nav class="w3-sidebar w3-grey w3-collapse w3-top w3-large w3-padding" style="z-index:3;width:300px;font-weight:bold;" id="mySidebar"><br>
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-button w3-hide-large w3-display-topleft" style="width:100%;font-size:22px">Close Menu</a>
  <div class="w3-container">
    <h3 class="w3-padding-64"><b>Company<br>Name</b></h3>
  </div>
  <div class="w3-bar-block">
    <a href="#" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Home</a> 
    <a href="#showcase" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Welcome</a> 
    <a href="#services" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">About Us</a> 
    <a href="#designers" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Reviews</a> 
    <a href="#packages" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Packages</a> 
    <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Contact</a>
  </div>
</nav>

<!-- Top menu on small screens -->
<header class="w3-container w3-top w3-hide-large w3-black w3-xlarge w3-padding">
  <a href="javascript:void(0)" class="w3-button w3-red w3-margin-right" onclick="w3_open()">☰</a>
  <span>GG Galore</span>
</header>

<!-- Overlay effect when opening sidebar on small screens -->
<div class="w3-overlay w3-hide-large" onclick="w3_close()" style="cursor:pointer" title="close side menu" id="myOverlay"></div>

<!-- !PAGE CONTENT! -->
<div class="w3-main" style="margin-left:340px;margin-right:40px">

  <!-- Header -->
  <div class="w3-container" style="margin-top:80px" id="showcase">
    <h1 class="w3-jumbo"><b>GG Galore</b></h1>
    <h1 class="w3-xxxlarge w3-text-red"><b>Welcome.</b></h1>
    <hr style="width:50px;border:5px solid red" class="w3-round">
  </div>
  
  <!-- Photo grid (modal) -->
  <div class="w3-row-padding">
    <div class="w3-half">
      <img src="https://static.india.com/wp-content/uploads/2017/03/best-makeup-2017.jpg" style="width:100%" onclick="onClick(this)" alt="eye makeup">
      <img src="https://www.channelnewsasia.com/image/13102150/1x1/600/600/893a0b0c29adca04321cb5218ef451ed/pp/how-to-repurpose-your-makeup-hero.jpg" style="width:100%" onclick="onClick(this)" alt="Face makeup">
      <img src="https://threadcurve.com/wp-content/uploads/2020/06/types-of-lipsticks-June282020-1-min.jpg" style="width:100%" onclick="onClick(this)" alt="Eyeshadow">
    </div>

    <div class="w3-half">
      <img src="https://c1.peakpx.com/wallpaper/27/470/544/makeup-colors-brushes-wallpaper-preview.jpg" style="width:100%" onclick="onClick(this)" alt="Windows for the atrium">
      <img src="https://cdn.shopify.com/s/files/1/0268/4741/2398/files/IK-banner-home-sq1024-feat-best-makeup_600x.png?v=1603842174" style="width:100%" onclick="onClick(this)" alt="Bedroom and office in one space">
      <img src="https://media-api.xogrp.com/images/7d2403e5-b8f5-49dc-b74d-b79b597cf517~rs_1536.h" style="width:100%" onclick="onClick(this)" alt="Scandinavian design">
    </div>
  </div>

  <!-- Modal for full size images on click-->
  <div id="modal01" class="w3-modal w3-black" style="padding-top:0" onclick="this.style.display='none'">
    <span class="w3-button w3-black w3-xxlarge w3-display-topright">×</span>
    <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
      <img id="img01" class="w3-image">
      <p id="caption"></p>
    </div>
  </div>

  <!-- Services -->
  <div class="w3-container" id="services" style="margin-top:75px">
    <h1 class="w3-xxxlarge w3-text-red"><b>About Us.</b></h1>
    <hr style="width:50px;border:5px solid red" class="w3-round">
    <p>We are a cosmetic service that focus on what's best for what's best for you!</p>
    <p>Our mission it to make every makeup and beauty product user feel beautiful in their own skin. Our job is to provide you with the latest innnovative soultions for your everyday needs and more. GG GALORE® provides that sense of completion and beauty we all desire.We've all had moments where we've felt down and wanted a little pick me up. Whether its just a bad day and you want to make yourself feel better by putting on makeup and getting ready or you're having a bad hair day here at GG GALORE® we offer all the solutions. Whether you're new to the world of makeup or you're a frequent visiter GG GALORE® is a place you can call home, we are a community of beautiful people who just want everytone to feel beautiful in whatever way they choose. Here we know what's its like to be afraid of looking a certain way but we are beautiful in our own unique way and the only people we shoud want to change for is ourselves. It's hard looking in the mirror sometimes no matter who we are, what we see on the outside affects how we feel on the inside, here you're safe to discover all of it. Welcome to our community here at GG GALORE®.
    </p>
  </div>
  
  <!-- Reviews -->
  <div class="w3-container" id="designers" style="margin-top:75px">
    <h1 class="w3-xxxlarge w3-text-red"><b>Reviews.</b></h1>
    <hr style="width:50px;border:5px solid red" class="w3-round">
    <p><b>Heres what our customers have to say:</b></p>
    <p>⭐️⭐️⭐️⭐️ <b>@Juliusceaser45</b>: Effortlessly beautiful, calming to know the products work and last a long time always available for the needed occasion</p>
    <p>⭐️⭐️⭐️⭐️⭐️ <b>@Deigo76expert</b>: My number one choice for makeup when it comes to making sure my skin stays healthy and safe when im busy making it beautiful </p>
    <p> ⭐️⭐️⭐️⭐️⭐️ <b>@Rozywizzes</b>: Doesn't disappoint, quality is promising and packages arrive on time and undamaged </p>
    <p> ⭐️⭐️⭐️⭐️ <b>@Goratory1638</b>: Customer service is outstanding, there every step of the way, always willing to help
    <p><b>Shopping Made For You!</b></p>
  </div>

  <!-- Packages / Pricing Tables -->
  <div class="w3-container" id="packages" style="margin-top:75px">
    <h1 class="w3-xxxlarge w3-text-red"><b>Packages:</b></h1>
    <hr style="width:50px;border:5px solid red" class="w3-round">
    <p>Our Makeup packages and sets range from low to high in order to fit your needs and what you desire. Below are some basic packages often bought and are frequently purchased by our customers. You can also contact us for specific items you are looking for, gift packages, customized sets and more.</p>
  </div>

  <div class="w3-row-padding">
    <div class="w3-half w3-margin-bottom">
      <ul class="w3-ul w3-light-grey w3-center">
        <li class="w3-dark-grey w3-xlarge w3-padding-32">Basic</li>
        <li class="w3-padding-16">Eyeshadow Pallets</li>
        <li class="w3-padding-16">Brushes</li>
        <li class="w3-padding-16">Foundation, setting powders, contour</li>
        <li class="w3-padding-16">Mascara, liner, lashes</li>
        <li class="w3-padding-16">Primer, facial mist, moisturizer</li>
        <li class="w3-padding-16">
          <h2>$ 198</h2>
          <span class="w3-opacity">Basic Starting Price</span>
        </li>
        <li class="w3-light-grey w3-padding-24">
          <button class="w3-button w3-white w3-padding-large w3-hover-black">Order Now</button>
        </li>
      </ul>
    </div>
        
    <div class="w3-half">
      <ul class="w3-ul w3-light-grey w3-center">
        <li class="w3-red w3-xlarge w3-padding-32">Pro</li>
        <li class="w3-padding-16">Eyeshadow, Mascara, eyeliner</li>
        <li class="w3-padding-16">Highlighter, countor, setting powder, primers</li>
        <li class="w3-padding-16">Lipstick, lipgloss, lipliner</li>
        <li class="w3-padding-16">Makeup brushes and bags</li>
        <li class="w3-padding-16">Eyelashes, contacts, lace</li>
        <li class="w3-padding-16">
          <h2>$ 248</h2>
          <span class="w3-opacity">Starting Price But Customizable</span>
        </li>
        <li class="w3-light-grey w3-padding-24">
          <button class="w3-button w3-red w3-padding-large w3-hover-black">Order Now</button>
        </li>
      </ul>
    </div>
  </div>
  
  <!-- Contact -->
  <div class="w3-container" id="contact" style="margin-top:75px">
    <h1 class="w3-xxxlarge w3-text-red"><b>Contact.</b></h1>
    <hr style="width:50px;border:5px solid red" class="w3-round">
    <p>Fill out the form and fill me in with the details :) We love helping our customers get what they desire! Contact Us for more information, discounts, deals and to learn more</p>
    <form action="/action_page.php" target="_blank">
      <div class="w3-section">
        <label>Name</label>
        <input class="w3-input w3-border" type="text" name="Name" required>
      </div>
      <div class="w3-section">
        <label>Email</label>
        <input class="w3-input w3-border" type="text" name="Email" required>
      </div>
      <div class="w3-section">
        <label>Message</label>
        <input class="w3-input w3-border" type="text" name="Message" required>
      </div>
      <button type="submit" class="w3-button w3-block w3-padding-large w3-red w3-margin-bottom">Send Message</button>
    </form>  
  </div>

<!-- End page content -->
</div>

<!-- W3.CSS Container -->
<div class="w3-light-grey w3-container w3-padding-32" style="margin-top:75px;padding-right:58px"><p class="w3-right">Created by <a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-opacity">GG GALORE</a></p></div>

<script>
// Script to open and close sidebar
function w3_open() {
  document.getElementById("mySidebar").style.display = "block";
  document.getElementById("myOverlay").style.display = "block";
}
 
function w3_close() {
  document.getElementById("mySidebar").style.display = "none";
  document.getElementById("myOverlay").style.display = "none";
}

// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
}
</script>

</body>
</html>
