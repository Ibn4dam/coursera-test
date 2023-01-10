<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - BB Brothers | Ecommerce website </title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,100;0,300;0,400;0,700;0,900;1,100&display=swap" rel="stylesheet">
 <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
        
  </head>
  <body>
      
     
     <div class= "container"> 
       <div class="navbar">
     <div class="logo">
     <a href="index.html"><img src="images/logo.jpg" width="125px"> </a>
          </div>
          <nav>
            <ul id="menuItems">
                <li><a href="index.html">Home</a></li>   
                <li><a href="products.html">Products</a></li>  
                <li><a href="about.html">About</a></li>  
                <li><a href="contact.html">Contact</a></li>  
                <li><a href="account.html">Account</a></li>  
            </ul> 
            
            <ul id="mobile-nav" class="hidden">
             <li><a href="index.html">Home</a></li>   
             <li><a href="products.html">Products</a></li>  
             <li><a href="about.html">About</a></li>  
             <li><a href="contact.html">Contact</a></li>  
             <li><a href="account.html">Account</a></li>  
         </ul>    
           </nav> 
           <a href="cart.html"><img src="images/cart.png" width="30px" height="30px"> </a>
           <img src="images/menu.png" class="menu-icon" onclick="menutoggle()">
     </div>
   </div>
<!--------------------------About Us---------------------->  
<section class="about">
  <div class="content">
    <div class="row">
      <div class="about-col-1">
        <img src="images/c1.png">
      </div>
      <div class="text about-col-1">
        <h1>About Us</h1>
        <h5>BB Brothers </h5>
        <small>Believers Are But Brothers</small>
         <p> Whoever fulfills the needs of his brother, Allah will fulfill his needs.  Whoever relieves a Muslim from distress, Allah will relieve him fromdistress on the Day of Resurrection."</p>
        <button type="btn">More Info</button>
      </div>
    </div>
  </div>
</section>   

      
      
      
      
      
<!--------------------------footer---------------------->      
      <div class="footer">
        <div class="container">
          <div class="row">
              <div class="footer-col-1">
                <h3>Download Our App</h3>
                  <p>Download App for Android and iOS mobile phone</p>
                   <div class="app-logo">
                    <img src="images/playstore.png" width="100" height="100">
                    <img src="images/appstore.png" width="100" height="100">   
                  </div>
              </div>
               <div class="footer-col-2">
                <img src="images/logo.jpg" width="50" height="150">
                  <p>Our purpose is to sustainably make the pleasure and the benefits of Fashion accesible to many.</p>
              </div>
               <div class="footer-col-3">
                <h3>Useful links</h3>
                  <ul>
                    <li>Coupons</li>
                    <li>Blog Post</li>
                    <li>Return Policy</li>
                    <li>Join Affiliate</li>
                  </ul>
              </div>
              <div class="footer-col-4">
                <h3>Follow Us</h3>
                  <ul>
                    <li>FaceBook</li>
                    <li>Twitter</li>
                    <li>Instagram</li>
                    <li>YouTube</li>
                  </ul>
              </div>
          </div>
            <hr>
            <p class="copyright">Copyright 2022 - BB Brothers</p>
        </div>
      </div>
   <!----------------js for  toggle menu-------------->
      <script>
         
          function menutoggle(){
            var MobileMenu = document.getElementById("mobile-nav");

            if(MobileMenu.classList.contains("hidden")){
              MobileMenu.classList.remove("hidden");
            }else{
              MobileMenu.classList.add("hidden");
            }
          }
      </script>
         
  </body>
</html>
