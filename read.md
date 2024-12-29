<section id="banners" class="section-p1">
        <div class="big-banners">
          <div class="big-banners-1">
            <h4>crazy deals</h4>
            <h2>buy 1 get 1 free</h2>
            <span>The best classic dress is on sale at coro</span>
            <button class="banner-btn">Learn More</button>
          </div>
          <div class="big-banners-2">
            <h4>spring/summer</h4>
            <h2>upcomming season</h2>
            <span>The best classic dress is on sale at cara</span>
            <button class="banner-btn">Collection</button>
          </div>
        </div>
        <div class="small-banners">
          <div class="small-banners-1">
            <h2>SEASONAL SALE</h2>
            <h5>Winter Collection 50% Off</h5>
          </div>
          <div class="small-banners-2">
            <h2>NEW FOOTWEAR COLLECTION</h2>
            <h5>Spring/Summer 2022</h5>
          </div>
          <div class="small-banners-3">
            <h2>T-SHIRTS</h2>
            <h5>New Trendy Prints</h4>
          </div>
        </div>
      </section>

      <section id="newsletter">
        <div class="newsletter-text">
          <h3>Sign Up For Newsletters</h3>
          <h5>get e-mail updates about out latest shop and <span>special offers</span></h5>
        </div>
        <div class="form">
          <input type="email" placeholder="Your email address" id="email-address-input">
          <button>Sign Up</button>
        </div>
      </section>

    </main>

    <!--footer section-->

    <footer>
      <div id="footer">
        <div class="contact">
          <a href="indext.html"><img src="images/images/logo.png" alt="" /></a>
          <br> <br>
          <br> 
          <h3>Contact</h3>
          <address>
            <p><b>Address:</b> Wellington Road, Street 32. San Francisco</p>
            <p><b>Phone:</b> Wellington Road, Street 32. San Francisco</p>
            <p><b>Hours</b> 10:00 - 18:00. Mon - Sat</p>
          </address>
          <h3>Follow Us</h3>
          <br> 
          <div class="socials">
            <a href="#"><i class="fa-brands fa-facebook-square"></i></a>
            <a href="#"><i class="fa-brands fa-youtube"></i></a>
            <a href="#"><i class="fa-brands fa-telegram"></i></a>
            <a href="#"><i class="fa-brands fa-instagram"></i></a>
            <a href="#"><i class="fa-brands fa-twitter"></i></a>
          </div>
        </div>
        <div class="about">
          <h3>About</h3>
          <br> 
          <a href="#">About Us</a>
          <a href="#">Delivery Information</a>
          <a href="#">Privacy Policy</a>
          <a href="#">Terms & Conditions</a>
          <a href="#">Contact Us</a>
        </div>
        <div class="myaccount ">
          <h3>My account</h3>
          <br> 
          <a href="#">Sign In</a>
          <a href="#">View Cart</a>
          <a href="#">My Wishlist</a>
          <a href="#">Track My Order</a>
          <a href="#">Help</a>
        </div>
        <div class="install">
          <h3>Install App</h3>
          <br> 
          <p>From App Store or Google Play</p>
          <div class="download">
            <a href="#"><img src="images/pay/app.jpg" alt=""></a>
            <a href="#"><img src="images/pay/play.jpg" alt=""></a>
          </div>
          <p>Secured Payment Gateways</p>
          <img src="images/pay/pay.png" alt="">
        </div>
        
      </div>
    </footer>





     <!-- Search bar-->
     
    <div class="wrap">
      <div class="search">
         <input type="text" class="searchTerm" placeholder="What are you looking for?">
         <button type="submit" class="searchButton">
           <i class="fa fa-search"></i>
        </button>
      </div>
   </div>




#banners {
    margin: 0 60px;
  }
  #banners h2,
  h4,
  span {
    color: rgb(248, 248, 248);
  }
  #banners .big-banners {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  #banners .big-banners div {
    min-width: 580px;
    margin: 15px;
    height: 300px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
    padding: 25px;
    background-size: cover;
    backdrop-filter: blur(8%);
  }
  #banners .big-banners button {
    margin-top: 20px;
    padding: 12px 20px;
    font-size: 16px;
    font-weight: 500;
    background-color: transparent;
    color: rgb(248, 248, 248);
    border: 1px solid rgb(248, 248, 248);
    cursor: pointer;
    transition: 0.3s ease;
  }
  #banners .big-banners div:hover button {
    background-color: #088178;
    border: 1px solid #088178;
  }
  #banners .big-banners-1 {
    background-image: url(images/images/banner/b17.jpg);
  }
  #banners .big-banners-2 {
    background-image: url(images/images/banner/b10.jpg);
  }
  #banners .small-banners-1 {
    background-image: url(images/images/banner/b7.jpg);
  }
  #banners .small-banners-2 {
    background-image: url(images/images/banner/b4.jpg);
  }
  #banners .small-banners-3 {
    background-image: url(images/images/banner/b18.jpg);
  }
  #banners .small-banners {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  #banners .small-banners div {
    min-width: 370px;
    height: 200px;
    margin: 15px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
    padding: 25px;
    background-size: cover;
  }
  #banners .small-banners h2 {
    font-size: 25px;
  }
  #banners .small-banners h5 {
    color: #771818;
  }
  
  /* newsletter section styles */
  
  #newsletter {
    background-image: url(images/images/banner/b14.png);
    background-repeat: no-repeat;
    background-position: 180px;
    background-color: #041e42;
    height: 160px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 75px;
  }
  #newsletter .newsletter-text h3 {
    color: white;
    font-size: 30px;
    padding: 0 0 15px 0;
  }
  #newsletter .newsletter-text h5 {
    color: rgb(151, 151, 151);
    font-size: 17px;
  }
  #newsletter .newsletter-text h5 span {
    color: rgb(216, 182, 29);
  }
  #newsletter .form input {
    padding: 20px;
    width: 350px;
    height: 56px;
    background-color: #d1d0d0;
    border-radius: 6px 0 0 6px;
    font-size: 18px;
  
    border: none;
    outline: none;
    margin-right: -4px;
    margin-top: 1px;
  }
  #newsletter .form button {
    margin-left: 0;
    padding: 20px;
    border: none;
    width: 120px;
    background-color: #088178;
    color: white;
    font-size: 17px;
    border-radius: 0 6px 6px 0;
    cursor: pointer;
  }
  
  /* footer section styles */
  
  #footer{
    display: flex;
    align-items:flex-start;
    justify-content: space-between;
    padding: 75px;
    background-color: #ececec;
  }
  #footer div{
  }
  #footer p, #footer a{
    color: rgb(109, 109, 109);
    text-decoration: none;
  }
  #footer a:hover{
    color:#088178;
  }
  #footer .about a{
    display: block;
    padding:8px 0;
  }
  #footer .myaccount a{
    display: block;
    padding:8px 0;
  }
  #footer .download img{
    border: 1px solid #08817969;
    border-radius: 7px;
  }


  /* Search bar css */

  /* .search {
    width: 100%;
    
    position: relative;
    display: flex;
  }
  
  .searchTerm {
    width: 100%;
    height: 30px;
    border: 3px solid #00B4CC;
    border-right: none;
    padding: 5px;
    height: 20px;
    border-radius: 5px 0 0 5px;
    outline: none;
    color: #9DBFAF;
  }
  
  .searchTerm:focus{
    color: #00B4CC;
  }
  
  .searchButton {
    width: 40px;
    height: 36px;
    border: 1px solid #00B4CC;
    background: #00B4CC;
    text-align: center;
    color: #fff;
    border-radius: 0 5px 5px 0;
    cursor: pointer;
    font-size: 20px;
  }
  
  /*Resize the wrap to see the search bar change!*/
  /* .wrap{
    width: 30%;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  } */ 