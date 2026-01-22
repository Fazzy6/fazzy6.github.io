![Uploading medium.png…]()
<!DOCTYPE html>
<html lang="en">
<head>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/5/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<style>
body,h1,h2,h3,h4,h5 {font-family: "Raleway", sans-serif}
.w3-third img{margin-bottom: -6px; opacity: 0.8; cursor: pointer}
.w3-third img:hover{opacity: 1}
</style>
</head>
<body class="w3-light-grey w3-content" style="max-width:1600px">

<!-- Sidebar/menu -->
<nav class="w3-sidebar w3-bar-block w3-white w3-animate-left w3-text-grey w3-collapse w3-top w3-center" style="z-index:3;width:300px;font-weight:bold" id="mySidebar"><br>
  <h3 class="w3-padding-64 w3-center"><b>SOME<br>NAME</b></h3>
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-bar-item w3-button w3-padding w3-hide-large">CLOSE</a>
  <a href="#" onclick="w3_close()" class="w3-bar-item w3-button">PORTFOLIO</a> 
  <a href="#about" onclick="w3_close()" class="w3-bar-item w3-button">ABOUT ME</a> 
  <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button">CONTACT</a>
</nav>

<!-- Top menu on small screens -->
<header class="w3-container w3-top w3-hide-large w3-white w3-xlarge w3-padding-16">
  <span class="w3-left w3-padding">SOME NAME</span>
  <a href="javascript:void(0)" class="w3-right w3-button w3-white" onclick="w3_open()">☰</a>
</header>

<!-- Overlay effect when opening sidebar on small screens -->
<div class="w3-overlay w3-hide-large w3-animate-opacity" onclick="w3_close()" style="cursor:pointer" title="close side menu" id="myOverlay"></div>

<!-- !PAGE CONTENT! -->
<div class="w3-main" style="margin-left:300px">

  <!-- Push down content on small screens --> 
  <div class="w3-hide-large" style="margin-top:83px"></div>
  
  <!-- Photo grid -->
  <div class="w3-row">
    <div class="w3-third">
      <img src="/w3images/natureboy.jpg" style="width:100%" onclick="onClick(this)" alt="A boy surrounded by beautiful nature">
      <img src="/w3images/girl_mountain.jpg" style="width:100%" onclick="onClick(this)" alt="What a beautiful scenery this sunset">
      <img src="/w3images/girl.jpg" style="width:100%" onclick="onClick(this)" alt="The Beach. Me. Alone. Beautiful">
    </div>

    <div class="w3-third">
      <img src="/w3images/boy.jpg" style="width:100%" onclick="onClick(this)" alt="Quiet day at the beach. Cold, but beautiful">
      <img src="/w3images/man_bench.jpg" style="width:100%" onclick="onClick(this)" alt="Waiting for the bus in the desert">
      <img src="/w3images/natureboy.jpg" style="width:100%" onclick="onClick(this)" alt="Nature again.. At its finest!">
    </div>
    
    <div class="w3-third">
      <img src="/w3images/girl.jpg" style="width:100%" onclick="onClick(this)" alt="Canoeing again">
      <img src="/w3images/girl_train.jpg" style="width:100%" onclick="onClick(this)" alt="A girl, and a train passing">
      <img src="/w3images/closegirl.jpg" style="width:100%" onclick="onClick(this)" alt="What a beautiful day!">
    </div>
  </div>

  <!-- Pagination -->
  <div class="w3-center w3-padding-32">
    <div class="w3-bar">
      <a href="#" class="w3-bar-item w3-button w3-hover-black">«</a>
      <a href="#" class="w3-bar-item w3-black w3-button">1</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">2</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">3</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">4</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">»</a>
    </div>
  </div>
  
  <!-- Modal for full size images on click-->
  <div id="modal01" class="w3-modal w3-black" style="padding-top:0" onclick="this.style.display='none'">
    <span class="w3-button w3-black w3-xlarge w3-display-topright">×</span>
    <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
      <img id="img01" class="w3-image">
      <p id="caption"></p>
    </div>
  </div>

  <!-- About section -->
  <div class="w3-container w3-dark-grey w3-center w3-text-light-grey w3-padding-32" id="about">
    <h4><b>About Me</b></h4>
    <img src="/w3images/avatar_hat.jpg" alt="Me" class="w3-image w3-padding-32" width="600" height="650">
    <div class="w3-content w3-justify" style="max-width:600px">
      <h4>My Name</h4>
      <p>Some text about me. I love taking photos of PEOPLE. I am lorem ipsum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure
        dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod tempor
        incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
      </p>
      <p>mail: example@example.com</p>
      <p>tel: 5353 35531</p>
      <hr class="w3-opacity">
      <h4 class="w3-padding-16">Technical Skills</h4>
      <p class="w3-wide">Photography</p>
      <div class="w3-white">
        <div class="w3-container w3-padding-small w3-center w3-grey" style="width:95%">95%</div>
      </div>
      <p class="w3-wide">Web Design</p>
      <div class="w3-white">
        <div class="w3-container w3-padding-small w3-center w3-grey" style="width:85%">85%</div>
      </div>
      <p class="w3-wide">Photoshop</p>
      <div class="w3-white">
        <div class="w3-container w3-padding-small w3-center w3-grey" style="width:80%">80%</div>
      </div>
      <p><button class="w3-button w3-light-grey w3-padding-large w3-margin-top w3-margin-bottom">Download Resume</button></p>
      <hr class="w3-opacity">

      <h4 class="w3-padding-16">How much I charge</h4>
      <div class="w3-row-padding" style="margin:0 -16px">
        <div class="w3-half w3-margin-bottom">
          <ul class="w3-ul w3-white w3-center w3-opacity w3-hover-opacity-off">
            <li class="w3-black w3-xlarge w3-padding-32">Basic</li>
            <li class="w3-padding-16">Web Design</li>
            <li class="w3-padding-16">Photography</li>
            <li class="w3-padding-16">5GB Storage</li>
            <li class="w3-padding-16">Mail Support</li>
            <li class="w3-padding-16">
              <h2>$ 10</h2>
              <span class="w3-opacity">per month</span>
            </li>
            <li class="w3-light-grey w3-padding-24">
              <button class="w3-button w3-white w3-padding-large">Sign Up</button>
            </li>
          </ul>
        </div>
        
        <div class="w3-half">
          <ul class="w3-ul w3-white w3-center w3-opacity w3-hover-opacity-off">
            <li class="w3-black w3-xlarge w3-padding-32">Pro</li>
            <li class="w3-padding-16">Web Design</li>
            <li class="w3-padding-16">Photography</li>
            <li class="w3-padding-16">50GB Storage</li>
            <li class="w3-padding-16">Endless Support</li>
            <li class="w3-padding-16">
              <h2>$ 25</h2>
              <span class="w3-opacity">per month</span>
            </li>
            <li class="w3-light-grey w3-padding-24">
              <button class="w3-button w3-white w3-padding-large">Sign Up</button>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>

  <!-- Contact section -->
  <div class="w3-container w3-light-grey w3-padding-32 w3-padding-large" id="contact">
    <div class="w3-content" style="max-width:600px">
      <h4 class="w3-center"><b>Contact Me</b></h4>
      <p>Do you want me to photograph you? Fill out the form and fill me in with the details :) I love meeting new people!</p>
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
        <button type="submit" class="w3-button w3-block w3-black w3-margin-bottom">Send Message</button>
      </form>
    </div>
  </div>

  <!-- Footer -->
  <footer class="w3-container w3-padding-32 w3-grey">  
    <div class="w3-row-padding">
      <div class="w3-third">
        <h3>INFO</h3>
        <p>Praesent tincidunt sed tellus ut rutrum. Sed vitae justo condimentum, porta lectus vitae, ultricies congue gravida diam non fringilla.</p>      
      </div>
    
      <div class="w3-third">
        <h3>BLOG POSTS</h3>
        <ul class="w3-ul">
          <li class="w3-padding-16 w3-hover-black">
            <img src="/w3images/workshop.jpg" class="w3-left w3-margin-right" style="width:50px">
            <span class="w3-large">Lorem</span><br>
            <span>Sed mattis nunc</span>
          </li>
          <li class="w3-padding-16 w3-hover-black">
            <img src="/w3images/gondol.jpg" class="w3-left w3-margin-right" style="width:50px">
            <span class="w3-large">Ipsum</span><br>
            <span>Praes tinci sed</span>
          </li> 
        </ul>
      </div>

      <div class="w3-third">
        <h3>POPULAR TAGS</h3>
        <p>
          <span class="w3-tag w3-black w3-margin-bottom">Travel</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">New York</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">London</span>
          <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">IKEA</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">NORWAY</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">DIY</span>
          <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Ideas</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Baby</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Family</span>
          <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">News</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Clothing</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Shopping</span>
          <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Sports</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Games</span>
        </p>
      </div>
    </div>
  </footer>
  
  <div class="w3-black w3-center w3-padding-24">Powered by <a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-opacity">w3.css</a></div>

<!-- End page content -->
</div>

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



!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Name Javide Vatan,Persian Nationalism</title>
<h1>poem by Bijan Taraghi</h1>
<br>
<a href="https://youtu.be/hDlMictEQsI?si=jns3T1eleFkOUsmX"
performed by Darya Dadvar
target="_blank"
title="Darya Dadvar - YouTube">
Click here to listen
</a>




<style>
body {
font-family: 'Poppins', sans-serif;
background: #f5f5f5;
color: #222;
line-height: 1.6;
padding: 40px;
}
.lyrics-container {
max-width: 700px;
margin: auto;
background: white;
padding: 25px 35px;
border-radius: 20px;
box-shadow: 0 4px 15px rgba(0,0,0,0.1);
}
h1 {
text-align: center;
color: #b30000;
margin-bottom: 20px;
}
.line {
margin: 10px 0;
}
.finglish {
font-weight: 600;
color: #333;
}
.english {
color: #555;
font-style: italic;
margin-left: 15px;
display: block;
}
</style>
</head>
<body>
<div class="lyrics-container">
<h1>Name Javide Vatan</h1>

<div class="line"><span class="finglish">Name Javide Vatan</span> <span class="english">(Immortal name of the homeland)</span></div>
<div class="line"><span class="finglish">Sobhe Omide Vatan</span> <span class="english">(Morning of hope for the homeland)</span></div>
<div class="line"><span class="finglish">Jelveh kon dar aseman</span> <span class="english">(Shine in the sky)</span></div>
<div class="line"><span class="finglish">Hamcho mehr-e javedan</span> <span class="english">(Like an eternal sun)</span></div>
<div class="line"><span class="finglish">Vatan ey hasti-ye man</span> <span class="english">(My homeland, my very existence)</span></div>
<div class="line"><span class="finglish">Shoor o sar-masti-ye man</span> <span class="english">(My passion and joy)</span></div>
<div class="line"><span class="finglish">Jelveh kon dar aseman</span> <span class="english">(Shine in the sky)</span></div>
<div class="line"><span class="finglish">Hamcho mehr-e javedan</span> <span class="english">(Like an eternal sun)</span></div>
<div class="line"><span class="finglish">Beshno sooz-e sokhanam</span> <span class="english">(Listen to the burning of my words)</span></div>
<div class="line"><span class="finglish">Ke hamavaz-e to manam</span> <span class="english">(For I sing in harmony with you)</span></div>
<div class="line"><span class="finglish">Hame jan o tanam</span> <span class="english">(My whole soul and body)</span></div>
<div class="line"><span class="finglish">Vatanam, vatanam, vatanam, vatanam</span> <span class="english">(My homeland, my homeland, my homeland, my homeland)</span></div>
<div class="line"><span class="finglish">Beshno sooz-e sokhanam</span> <span class="english">(Listen to the burning of my words)</span></div>
<div class="line"><span class="finglish">Ke nava-gar-e in chamanam</span> <span class="english">(For I am the melody of this land)</span></div>
<div class="line"><span class="finglish">Hame jan o tanam</span> <span class="english">(My whole soul and body)</span></div>
<div class="line"><span class="finglish">Vatanam, vatanam, vatanam, vatanam</span> <span class="english">(My homeland, my homeland, my homeland, my homeland)</span></div>
<div class="line"><span class="finglish">Hame ba yek nam o neshan</span> <span class="english">(All united under one name and identity)</span></div>
<div class="line"><span class="finglish">Be tafavot har rang o zaban</span> <span class="english">(Regardless of every color and language)</span></div>
<div class="line"><span class="finglish">Hame ba yek nam o neshan</span> <span class="english">(All united under one name and identity)</span></div>
<div class="line"><span class="finglish">Be tafavot har rang o zaban</span> <span class="english">(Regardless of every color and language)</span></div>
<div class="line"><span class="finglish">Hame shad o khosh o naghmeh-zanan</span> <span class="english">(All happy, joyful, and singing)</span></div>
<div class="line"><span class="finglish">Ze salabat-e Iran-e javan</span> <span class="english">(From the strength of young Iran)</span></div>
<div class="line"><span class="finglish">Ze salabat-e Iran-e javan</span> <span class="english">(From the strength of young Iran)</span></div>
<div class="line"><span class="finglish">Ze salabat-e Iran-e javan</span> <span class="english">(From the strength of young Iran)</span></div>
</div>
</body>
</html>
Attachments area
Preview YouTube video Darya Dadvar - Vatanam - Iran National Anthem - Hymne d'IranPreview YouTube video Darya Dadvar - Vatanam - Iran National Anthem - Hymne d'Iran


<!DOCTYPE html>
<html>
<head>
<title>Lesson 5 Project</title>
<!-- Internal CSS -->
<style>
   body {
     background-color: #fff7cc;
     font-family: Arial, sans-serif;
     margin: 0;
     padding: 0;
   }
   h1 {
     text-align: center;
     color: #333366;
   }
   .nav {
     text-align: center;
     background-color: #ffec99;
     padding: 10px;
     border-bottom: 2px solid #999966;
   }
   .nav ul {
     list-style-type: none;
     margin: 0;
     padding: 0;
   }
   .nav ul li {
     display: inline;
     margin: 0 15px;
   }
   .nav ul li a {
     text-decoration: none;
     color: #333366;
     font-weight: bold;
   }
   .nav ul li a:hover {
     color: #cc6600;
   }
   section {
     padding: 30px;
     text-align: center;
   }
   img {
     border-radius: 10px;
     margin: 20px auto;
     display: block;
   }
   footer {
     text-align: center;
     padding: 20px;
     background-color: #ffec99;
     border-top: 2px solid #999966;
   }
</style>
</head>
<body>
<!-- Navigation Menu -->
<div class="nav">
<ul>
<li><a href="#home">Home</a></li>
<li><a href="#about">About</a></li>
<li><a href="#gallery">Gallery</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</div>
<!-- Home Section -->
<section id="home">
<h1>Welcome to My Website</h1>
<p>This site shows everything I learned in Lesson 5: HTML links, CSS, email links and more!</p>
<p style="color:#990000; font-weight:bold;">This paragraph uses inline CSS (colour and bold text).</p>
<img src="https://www.apple.com/newsroom/images/product/mac/standard/Apple-MacBook-Air-M2-hero-220606_big.jpg.large.jpg"
        alt="MacBook Air" width="400">
<p>
     Visit the official <a href="https://www.apple.com/uk/" target="_blank">Apple website</a> for more info.
</p>
</section>
<!-- About Section -->
<section id="about" style="background-color:#e6f0ff;">
<h1>About Us</h1>
<p>We’re students learning HTML and CSS. This page is part of our class project where we practise making links, adding colours, and styling with CSS.</p>
<img src="https://upload.wikimedia.org/wikipedia/commons/f/fa/Apple_logo_black.svg"
        alt="Apple logo" width="100">
</section>
<!-- Gallery Section -->
<section id="gallery" style="background-color:#f0fff0;">
<h1>Gallery</h1>
<p>Here are some images of Apple products we love!</p>
<img src="https://store.storeimages.cdn-apple.com/4982/as-images.apple.com/is/ipad-air-select-cell-skyblue-202203?wid=940&hei=1112&fmt=png-alpha&.v=1645066724046"
        alt="iPad Air" width="250">
<img src="https://store.storeimages.cdn-apple.com/4982/as-images.apple.com/is/macbook-air-m2-midnight-gallery1-202402?wid=400&hei=400&fmt=png-alpha&.v=1707414153779"
        alt="MacBook Air" width="250">
</section>
<!-- Contact Section -->
<section id="contact" style="background-color:#ffe6e6;">
<h1>Contact Us</h1>
<p>If you’d like to get in touch, please send me an email!</p>
<p><a href="mailto:student@example.com">Click here to email me!</a></p>
</section>
<footer>
<p>© 2025 My Lesson 5 Project</p>
</footer>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
<title>Lesson 5 Project</title>
<!-- Internal CSS -->
<style>
   body {
     background-color: #fff7cc;
     font-family: Arial, sans-serif;
     margin: 0;
     padding: 0;
   }
   h1 {
     text-align: center;
     color: #6fa1c9;
   }
   .nav {
     text-align: center;
     background-color: #a9e0b1;
     padding: 10px;
     border-bottom: 2px solid #79791c;
   }
   .nav ul {
     list-style-type: none;
     margin: 0;
     padding: 0;
   }
   .nav ul li {
     display: inline;
     margin: 0 15px;
   }
   .nav ul li a {
     text-decoration: none;
     color: #0303b8;
     font-weight: bold;
   }
   .nav ul li a:hover {
     color: #e44b83;
   }
   section {
     padding: 30px;
     text-align: center;
   }
   img {
     border-radius: 10px;
     margin: 20px auto;
     display: block;
   }
   footer {
     text-align: center;
     padding: 20px;
     background-color: #ffec99;
     border-top: 2px solid #999966;
   }
</style>
</head>
<body>
<!-- Navigation Menu -->
<div class="nav">
<ul>
<li><a href="#home">Home</a></li>
<li><a href="#about">About</a></li>
<li><a href="#gallery">Gallery</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</div>
<!-- Home Section -->
<section id="home">
<h1>Welcome to My Website</h1>
<p>This site shows everything I learned in Lesson 5: HTML links, CSS, email links and more!</p>
<p style="color:#990000; font-weight:bold;">This paragraph uses inline CSS (colour and bold text).</p>
<img src="https://www.apple.com/newsroom/images/product/mac/standard/Apple-MacBook-Air-M2-hero-220606_big.jpg.large.jpg"
        alt="MacBook Air" width="400">
<p>
     Visit the official <a href="https://www.apple.com/uk/" target="_blank">Apple website</a> for more info.
</p>
</section>
<!-- About Section -->
<section id="about" style="background-color:#e6f0ff;">
<h1>About Us</h1>
<p>We’re students learning HTML and CSS. This page is part of our class project where we practise making links, adding colours, and styling with CSS.</p>
<img src="https://upload.wikimedia.org/wikipedia/commons/f/fa/Apple_logo_black.svg"
        alt="Apple logo" width="100">
</section>
<!-- Gallery Section -->
<section id="gallery" style="background-color:#f0fff0;">
<h1>Gallery</h1>
<p>Here are some images of Apple products we love!</p>
<img src="https://store.storeimages.cdn-apple.com/4982/as-images.apple.com/is/ipad-air-select-cell-skyblue-202203?wid=940&hei=1112&fmt=png-alpha&.v=1645066724046"
        alt="iPad Air" width="250">
<img src="https://store.storeimages.cdn-apple.com/4982/as-images.apple.com/is/macbook-air-m2-midnight-gallery1-202402?wid=400&hei=400&fmt=png-alpha&.v=1707414153779"
        alt="MacBook Air" width="250">
</section>
<!-- Contact Section -->
<section id="contact" style="background-color:#ffe6e6;">
<h1>Contact Us</h1>
<p>If you’d like to get in touch, please send me an email!</p>
<p><a href="mailto:student@example.com">Click here to email me!</a></p>
</section>
<footer>
<p>© 2025 My Lesson 5 Project</p>
</footer>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
 <title>My first website</title>   
</head>

<img src="https://i.ytimg.com/vi/bKHq2bdm8GA/maxresdefault.jpg" 
   hieght="600" width="600">

   
    <a href="https://www.bing.com/search?q=MMS+Lyrics&filters=dtbk:%22MCFvdmVydmlldyFMeXJpY3MhZjY4OWY0ZTUtMGU0Ni02MmVhLWQ4ZDEtNWY3MGYxZGQ3ZTc5%22+sid:%22f689f4e5-0e46-62ea-d8d1-5f70f1dd7e79%22&FORM=DEPNAV"
    target="_blank"
    title="go to MMS lyrics">
        Click here
    
  
    <hi>This is MMS icon pis </hi>
  <br>
   
  
  <a href="mailto:nwajianyafavour@gmail.com">
        Email me 
    </a>
    

</html>
<html>

<head> <style>

.myDivElement{ text-align:center;

}

.myDivElement ul li{ display:inline;

}

</style> </head>


<body>

<div class="myDivElement">

<ul>

<li>Home</li>

<li><a href="About.htm">About us</a></li>

<li>Gallery</li>

<li>Contact</li>

</ul>

</div>

<p> </p>



<h2>My First JavaScript</h2>


<button type="button"

onclick="document.getElementById('demo').innerHTML = Date()">

Click me to display Date and Time.</button>

<p id="demo"></p>

</body>

</html>
<!DOCTYPE html>
<html>
    <head>
        <title>my song lyrics</title>
    </head>
    <body>
        <h1>MMS</h1>
        <h4>Song by Wizkid Asake</h3>
       <a href="https://youtu.be/iiOHqmmjdGk">
          Original Video  
            </a>
           
           
           
            <hr>
            <br>
            <pre>
See this life thing, yeah
The life is all about understanding, bro
You gotta understand what you're doing
You gotta-, you need a direction, bro

O ye Ọlọhun, o ye Ọlọhun
Gbogbo nnkan ma lo ye Ọlọhun
O ye Ọlọhun, o ye Ọlọhun, uhn-uhn
Gbogbo nnkan ma lo ye Ọlọhun
Ki la mu w'aye? Ko soun ta mu w'aye
Ko si nnkan ta ma mu lọ-ọ
Ki la mu wa aye? Ko soun ta mu w'aye
Ko si nnkan ta ma mu lọ ọ-ọ-ọ, mm
(Sit back and watch it)

Once upon a time, once upon a time (time, time)
When I just dey try, when I just dey try (try)
When I drop a song, I go need to dance (dance, dance)
I dey waka kurukere, I dey pay my price
Then, I found a sound among all the sounds (sound)
I no get name, I know say na sound (sound)
Sound, sound, Mr. Money sound
I wan dey precise, I wan dey precise, huh-huh

I be like militant, military, military
Match on my enemies, mm-mm
Vigilante, vigilante, forgive me Lord, I dey on Your mercy
Cemetery, cemetery, people wey don die dey for cemetery, mm-mm
Life e no easy, I know e no easy, you gats to dey take am easy (mm-mm)
(It's all vanity upon vanity, bro)

O ye Ọlọhun, o ye Ọlọhun
Gbogbo nnkan ma lo ye Ọlọhun
O ye Ọlọhun, o ye Ọlọhun, uhn-uhn
Gbogbo nnkan ma lo ye Ọlọhun
Ki la mu w'aye? Ko soun ta mu w'aye
Ko si nnkan ta ma mu lọ-ọ
Ki la mu wa aye? Ko soun ta mu w'aye
Ko si nnkan ta ma mu lọ ọ-ọ-ọ, mm

Wabillahi Taufiq gan-an
Mo dupẹ lọwọ Ọlọhun for my city gan-an (yeah-yeah)
You no fit run from who you are
Man, wetin go be, man, is cast in stone
Mo dupẹ lọwọ Ọlọhun ta wa sa nle o
Mo ware, ware titi, mo dẹ ṣaamin o
A dupẹ lọwọ Ọlọhun to ko mi yọ
Ka dẹ ma ṣeun ta le ṣe, ka dẹ ma yọọ

O ye Ọlọhun, o ye Ọlọhun
My mama leave me here, e no long
Lost myself, and I found my purpose
Yeah, every day, I know that I am blessed
Tonight, we go jolomi o, mm
Yeah, jẹ ka joromi, uhn-uhn
Nothing man no face, so vibe today
This kind thing, say na life we dey

Mo dupẹ lọwọ Ọlọhun ta wa sa nle o
Mo ware, ware titi, mo dẹ ṣaamin o
A dupẹ lọwọ ọlọun to ko mi yọ
Ka dẹ ma ṣeun ta le ṣe, ka dẹ ma yọọ
Songwriters: Ayodeji Ibrahim Balogun, Peace Emmanuel Oredope, Ololade Ahmed, Joseph Kier Gordon Caleb. For non-commercial use only.
        
</pre>
    </body>
</html>
body {
font-family: Arial, sans-serif;
margin: 0;
background-color: #f4f6f8;
}

/* Header */
header {
background-color: #0b5ed7;
color: white;
padding: 20px;
text-align: center;
}

/* Navigation */
nav {
background-color: #083d9c;
padding: 10px;
text-align: center;
}

nav a {
color: white;
margin: 0 15px;
text-decoration: none;
font-weight: bold;
}

nav a:hover {
text-decoration: underline;
}

/* Hero Section */
.hero {
background-color: #e9ecef;
text-align: center;
padding: 40px;
}

.hero h2 {
color: #0b5ed7;
}

/* Content Sections */
.content {
padding: 30px;
background-color: white;
margin: 20px;
border-radius: 5px;
}

/* Footer */
footer {
background-color: #0b5ed7;
color: white;
text-align: center;
padding: 10px;
}

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Amazing Glory International School</title>
<link rel="stylesheet" href="MAIN.css">
</head>
<body>


<header>
<h1>Amazing Glory International School</h1>
<p>Eziama Uli, Anambra State, Nigeria</p>
</header>

<nav>
<a href="#">Home</a>
<a href="#">About Us</a>
<a href="#">Academics</a>
<a href="#">Admissions</a>
<a href="#">Contact</a>
</nav>


<section class="hero">
<h2>Raising Future Leaders</h2>
<p>Quality education with moral excellence</p>
</section>


<section class="content">
<h2>About Our School</h2>
<p>
Amazing Glory International School is a reputable institution located in
Eziama Uli, Anambra State, Nigeria. We are committed to academic excellence,
discipline, and character building.
</p>
</section>

<section class="content">
<h2>Our Academics</h2>
<ul>
<li>Nursery Education</li>
<li>Primary Education</li>
<li>Junior Secondary School</li>
<li>Senior Secondary School</li>
</ul>
</section>


<section class="content">
<h2>Contact Us</h2>
<p><strong>Address:</strong> Eziama Uli, Anambra State, Nigeria</p>
<p><strong>Phone:</strong> +447424458078</p>
<p><strong>Email:</strong> amazinggloryintschool@gmail.com</p>
</section>


<footer>
<p>&copy; 2026 Amazing Glory International School. All Rights Reserved.</p>
</footer>
</body>
</html>
body {
font-family: Arial, sans-serif;
margin: 0;
background-color: #f4f6f8;
}

/* Header */
header {
background-color: #0b5ed7;
color: white;
padding: 20px;
text-align: center;
}

/* Navigation */
nav {
background-color: #083d9c;
padding: 10px;
text-align: center;
}

nav a {
color: white;
margin: 0 15px;
text-decoration: none;
font-weight: bold;
}

nav a:hover {
text-decoration: underline;
}

/* Hero Section */
.hero {
background-color: #e9ecef;
text-align: center;
padding: 40px;
}

.hero h2 {
color: #0b5ed7;
}

/* Content Sections */
.content {
padding: 30px;
background-color: white;
margin: 20px;
border-radius: 5px;
}

/* Footer */
footer {
background-color: #0b5ed7;
color: white;
text-align: center;
padding: 10px;
}
