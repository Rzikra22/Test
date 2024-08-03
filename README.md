<!DOCTYPE html>
<html>
<head>
<title>Beauty Finder</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Poppins|Dancing+Script|Pacifico">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
  body, h1, h2, h3, h4, h5 {
    font-family: "Poppins", sans-serif;
    color: #4d004d;
  }
  h1 {
    font-family: 'Pacifico', cursive;
  }
  h3, h4, h5 {
    font-family: 'Dancing Script', cursive;
  }
  body {
    font-size: 16px;
    background: linear-gradient(to right, #ffe6f0, #f9ccff);
  }
  img {
    margin-bottom: -8px;
    border-radius: 15px;
  }
  .mySlides {
    display: none;
  }
  .w3-pink {
    background-color: #ff99cc !important;
  }
  .w3-purple {
    background-color: #cc99ff !important;
  }
  .w3-light-pink {
    background-color: #ffcce6 !important;
  }
  .w3-light-purple {
    background-color: #e6ccff !important;
  }
  .w3-light-grey {
    background-color: #f2f2f2 !important;
  }
  .w3-text-pink {
    color: #ff99cc !important;
  }
  .w3-text-purple {
    color: #cc99ff !important;
  }
  .w3-text-white {
    color: #ffffff !important;
  }
  .w3-hover-pink:hover {
    color: #ff99cc !important;
  }
  .w3-hover-purple:hover {
    color: #cc99ff !important;
  }
  .feature-icon {
    font-size: 50px;
    color: #ff99cc;
  }
  .feature-card {
    border-radius: 15px;
    box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
    background-color: #ffffff;
    padding: 20px;
    margin-bottom: 20px;
  }
  .cta-button {
    background: linear-gradient(to right, #ff66b3, #ff99cc);
    border-radius: 25px;
    padding: 10px 20px;
    color: #fff;
    text-transform: uppercase;
    font-weight: bold;
    box-shadow: 0px 4px 10px rgba(255, 102, 179, 0.5);
  }
  .cta-button:hover {
    box-shadow: 0px 6px 12px rgba(255, 102, 179, 0.7);
  }
  .gradient-text {
    background: -webkit-linear-gradient(#ff99cc, #cc99ff);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  }
  .card-image {
    height: 150px;
    object-fit: cover;
    width: 100%;
    border-radius: 15px 15px 0 0;
  }
</style>
</head>
<body class="w3-content" style="max-width:1500px;">

<!-- Header with Slideshow -->
<header class="w3-display-container w3-center">
  <button class="w3-button w3-block w3-pink w3-hide-large w3-hide-medium" onclick="document.getElementById('download').style.display='block'">Download <i class="fa fa-android"></i> <i class="fa fa-apple"></i> <i class="fa fa-windows"></i></button>
  <div class="mySlides w3-animate-opacity">
    <img class="w3-image" src="https://source.unsplash.com/1500x1000/?skincare" alt="Image 1" style="min-width:500px" width="1500" height="1000">
    <div class="w3-display-left w3-padding w3-hide-small" style="width:35%">
      <div class="w3-light-pink w3-opacity w3-hover-opacity-off w3-padding-large w3-round-large">
        <h1 class="w3-xlarge gradient-text">Glow with Confidence</h1>
        <hr class="w3-opacity">
        <p class="w3-text-black">Your beauty journey starts here</p>
        <p><button class="w3-button cta-button" onclick="document.getElementById('download').style.display='block'">Download Now <i class="fa fa-download"></i></button></p>
      </div>
    </div>
  </div>
  <div class="mySlides w3-animate-opacity">
    <img class="w3-image" src="https://source.unsplash.com/1500x1000/?makeup" alt="Image 2" style="min-width:500px" width="1500" height="1000">
    <div class="w3-display-left w3-padding w3-hide-small" style="width:35%">
      <div class="w3-light-purple w3-opacity w3-hover-opacity-off w3-padding-large w3-round-large">
        <h1 class="w3-xlarge gradient-text"><b>Embrace Your Beauty</b></h1>
        <hr class="w3-opacity">
        <p class="w3-text-black">Discover personalized beauty tips and tricks</p>
        <p><button class="w3-button cta-button" onclick="document.getElementById('download').style.display='block'">Explore Now <i class="fa fa-heart"></i></button></p>
      </div>
    </div>
  </div>
  <div class="mySlides w3-animate-opacity">
    <img class="w3-image" src="https://source.unsplash.com/1500x1000/?beauty" alt="Image 3" style="min-width:500px" width="1500" height="1000">
    <div class="w3-display-left w3-padding w3-hide-small" style="width:35%">
      <div class="w3-light-pink w3-opacity w3-hover-opacity-off w3-padding-large w3-round-large">
        <h1 class="w3-xlarge gradient-text">Unleash Your Potential</h1>
        <hr class="w3-opacity">
        <p class="w3-text-black">Empower your beauty with our app</p>
        <p><button class="w3-button cta-button" onclick="document.getElementById('download').style.display='block'">Get Started <i class="fa fa-rocket"></i></button></p>
      </div>
    </div>
  </div>
  <a class="w3-button w3-purple w3-display-right w3-margin-right w3-round w3-hide-small w3-hover-light-grey" onclick="plusDivs(1)">Take Tour <i class="fa fa-angle-right"></i></a>
  <a class="w3-button w3-block w3-pink w3-hide-large w3-hide-medium" onclick="plusDivs(1)">Take Tour <i class="fa fa-angle-right"></i></a>
</header>

<!-- The App Section -->
<div class="w3-padding-64 w3-white">
  <div class="w3-row-padding">
    <div class="w3-col l8 m6">
      <h1 class="w3-jumbo gradient-text"><b>Beauty Finder</b></h1>
      <h1 class="w3-xxxlarge w3-text-purple"><b>Why Install It?</b></h1>
      <p class="w3-large">Beauty Finder is a comprehensive beauty application designed to help you enhance and maintain your beauty. From skincare routines to makeup tips, our app offers personalized solutions tailored to your unique beauty needs. Join thousands of satisfied users who have transformed their beauty regimen with Beauty Finder.</p>
      <button class="w3-button w3-light-pink w3-padding-large w3-section w3-hide-small cta-button" onclick="document.getElementById('download').style.display='block'">
        <i class="fa fa-download"></i> Download Application
      </button>
      <p>Available for <i class="fa fa-android w3-xlarge w3-text-green"></i> <i class="fa fa-apple w3-xlarge"></i> <i class="fa fa-windows w3-xlarge w3-text-blue"></i></p>
    </div>
    <div class="w3-col l4 m6">
      <img src="https://source.unsplash.com/335x471/?beauty-products" class="w3-image w3-right w3-hide-small" width="335" height="471">
    </div>
  </div>
</div>

<!-- The Features Section -->
<div class="w3-container w3-padding-64 w3-light-pink">
  <h1 class="w3-xxxlarge gradient-text"><b>Features</b></h1>
  <p class="w3-large">Explore the features of Beauty Finder that cater to your beauty needs.</p>
  <div class="w3-row-padding">
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="feature-card">
        <img src="https://source.unsplash.com/400x150/?skincare-routine" alt="Skincare" class="card-image">
        <div class="w3-container">
          <h3><i class="fa fa-magic feature-icon"></i></h3>
          <h3>Skincare</h3>
          <p>Get personalized skincare routines and product recommendations tailored to your unique skin type and concerns.</p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="feature-card">
        <img src="https://source.unsplash.com/400x150/?makeup-tutorial" alt="Makeup" class="card-image">
        <div class="w3-container">
          <h3><i class="fa fa-paint-brush feature-icon"></i></h3>
          <h3>Makeup</h3>
          <p>Explore makeup tutorials and tips to enhance your beauty with the latest trends and techniques.</p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="feature-card">
        <img src="https://source.unsplash.com/400x150/?hair-care" alt="Hair Care" class="card-image">
        <div class="w3-container">
          <h3><i class="fa fa-cut feature-icon"></i></h3>
          <h3>Hair Care</h3>
          <p>Discover hair care routines and products to keep your locks healthy, shiny, and beautiful.</p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="feature-card">
        <img src="https://source.unsplash.com/400x150/?perfume" alt="Perfume" class="card-image">
        <div class="w3-container">
          <h3><i class="fa fa-leaf feature-icon"></i></h3>
          <h3>Perfume</h3>
          <p>Find your signature scent with our curated list of perfumes that match your style and personality.</p>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- The Pricing Section -->
<div class="w3-container w3-white w3-padding-64" id="pricing">
  <div class="w3-content">
    <h1 class="w3-xxxlarge gradient-text"><b>Pricing</b></h1>
    <p class="w3-large">Choose a pricing plan that suits your needs and unlock additional features.</p>
    <div class="w3-row-padding" style="margin:0 -16px">
      <div class="w3-half w3-margin-bottom">
        <ul class="w3-ul w3-light-pink w3-center feature-card">
          <li class="w3-purple w3-xlarge w3-padding-32">Basic</li>
          <li class="w3-padding-16">5 Photo Uploads</li>
          <li class="w3-padding-16">Skin Assessment</li>
          <li class="w3-padding-16">Basic Features</li>
          <li class="w3-padding-16">Limited Support</li>
          <li class="w3-padding-16">
            <h2 class="w3-wide"><i class="fa fa-usd"></i> 0</h2>
            <span class="w3-opacity">Free</span>
          </li>
          <li class="w3-light-grey w3-padding-24">
            <button class="cta-button w3-button">Sign Up</button>
          </li>
        </ul>
      </div>
      <div class="w3-half">
        <ul class="w3-ul w3-pink w3-center feature-card">
          <li class="w3-purple w3-xlarge w3-padding-32">Premium</li>
          <li class="w3-padding-16">Unlimited Photo Uploads</li>
          <li class="w3-padding-16">Advanced Skin Assessment</li>
          <li class="w3-padding-16">All Features</li>
          <li class="w3-padding-16">Priority Support</li>
          <li class="w3-padding-16">
            <h2 class="w3-wide"><i class="fa fa-usd"></i> 29</h2>
            <span class="w3-opacity">Per Month</span>
          </li>
          <li class="w3-light-grey w3-padding-24">
            <button class="cta-button w3-button">Sign Up</button>
          </li>
        </ul>
      </div>
    </div>
  </div>
</div>

<!-- Footer -->
<footer class="w3-container w3-padding-64 w3-light-purple w3-center">
  <div class="w3-row-padding">
    <div class="w3-third">
      <h3 class="gradient-text">About Us</h3>
      <p>Beauty Finder is dedicated to helping you achieve the perfect skin.</p>
      <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" target="_blank" class="w3-hover-text-pink">w3.css</a></p>
    </div>

    <div class="w3-third">
      <h3 class="gradient-text">Blog Posts</h3>
      <ul class="w3-ul">
        <li class="w3-padding-16 w3-hover-white feature-card">
          <img src="https://source.unsplash.com/50x50/?skincare" class="w3-left w3-margin-right" style="width:50px; border-radius: 50%;">
          <span class="w3-large">Skincare Tips</span><br>
          <span>Get the latest skincare advice from our experts.</span>
        </li>
        <li class="w3-padding-16 w3-hover-white feature-card">
          <img src="https://source.unsplash.com/50x50/?makeup" class="w3-left w3-margin-right" style="width:50px; border-radius: 50%;">
          <span class="w3-large">Makeup Trends</span><br>
          <span>Discover the hottest makeup trends for this season.</span>
        </li> 
      </ul>
    </div>

    <div class="w3-third w3-serif">
      <h3 class="gradient-text">Popular Tags</h3>
      <p>
        <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">Skincare</span> 
        <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">Beauty</span> 
        <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">Makeup</span> 
        <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">Hair Care</span> 
        <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">Perfume</span>
        <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">Trends</span> 
        <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">Tips</span>
      </p>
    </div>
  </div>
</footer>

<script>
// Slideshow
var slideIndex = 1;

function plusDivs(n) {
  showDivs(slideIndex += n);
}

function showDivs(n) {
  var i;
  var x = document.getElementsByClassName("mySlides");
  if (n > x.length) {slideIndex = 1}
  if (n < 1) {slideIndex = x.length} ;
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";  
  }
  x[slideIndex-1].style.display = "block";  
}

// Initialize the slideshow
showDivs(slideIndex);
</script>

</body>
</html>
