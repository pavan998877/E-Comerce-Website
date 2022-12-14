# E-Comerce-Website
E Comerce website using HTML CSS

<!DOCTYPE html>
<html>
<head>
    <style>
        * {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
header {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  height: 60px;
  width: 100%;
  background: black;
}
.heading ul {
  display: flex;
}
.logo a {
  color: white;
  transition-duration: 1s;
  font-weight: 800;
}
.logo a:hover {
  color: rgb(240, 197, 6);
  transition-duration: 1s;
}
.heading ul li {
  list-style: none;
}
.heading ul li a {
  margin: 5px;
  text-decoration: none;
  color: black;
  font-weight: 500;
  position: relative;
  color: white;
  margin: 2px 14px;
  font-size: 18px;
  transition-duration: 1s;
}
.heading ul li a:active {
  color: red;
}
.heading ul li a:hover {
  color: rgb(243, 168, 7);
  transition-duration: 1s;
}

.heading ul li a::before {
  content: "";
  height: 2px;
  width: 0px;
  position: absolute;
  left: 0;
  bottom: 0;
  background-color: white;
  transition-duration: 1s;
}
.heading ul li a:hover::before {
  width: 100%;
  transition-duration: 1s;
  background-color: rgb(243, 168, 7);
}
#input {
  height: 30px;
  width: 300px;
  text-decoration: none;
  border: 0px;
  padding: 5px;
}
.logo a {
  color: white;
  font-size: 35px;
  font-weight: 500;
  text-decoration: none;
}
ion-icon {
  width: 30px;
  height: 30px;
  background-color: white;
  color: black;
}
ion-icon:hover {
  cursor: pointer;
}
.search a {
  display: flex;
}
header a ion-icon {
  position: relative;
  right: 3px;
}

.img-slider img {
  height: 720px;
  width: 1080px;
}
@keyframes slide {
  0% {
    left: 0px;
  }
  15% {
    left: 0px;
  }
  20% {
    left: -1080px;
  }
  32% {
    left: -1080px;
  }
  35% {
    left: -2160px;
  }
  47% {
    left: -2160px;
  }
  50% {
    left: -3240px;
  }
  63% {
    left: -3240px;
  }
  66% {
    left: -4320px;
  }
  79% {
    left: -4320px;
  }
  82% {
    left: -5400px;
  }
  100% {
    left: 0px;
  }
}
.img-slider {
  display: flex;
  float: left;
  position: relative;
  width: 1080px;
  height: 720px;
  animation-name: slide;
  animation-duration: 10s;
  animation-iteration-count: infinite;
  transition-duration: 5s;
}

.heading1 {
  opacity: 0;
}
.search {
  display: flex;
  position: relative;
}
.section1 {
  width: 1080px;
  overflow: hidden;

  justify-content: center;
  align-items: center;
  margin: 0px auto;
}

.section2 .container {
  display: flex;
  width: 100%;
  height: max-content;
  flex-wrap: wrap;
  justify-content: center;
  margin: 10px auto;
}
.section2 .container .items {
  margin: 10px;
  width: 200px;
  height: 300px;
  background-color: white;
  border: 2.5px solid black;
  border-radius: 12px;
}
.section2 .container .items .name {
  text-align: center;
  background-color: rgb(240, 197, 6);
  height: 25px;
  padding-top: 4px;
  color: white;
  margin: 0;
}
.section2 .container .items .price {
  float: left;
  padding-left: 10px;
  display: block;
  width: 100%;
  color: rgb(255, 0, 0);
  font-weight: 650;
}
.section2 .container .items .info {
  padding-left: 10px;
  color: rgb(243, 168, 7);
}
.section2 .container .items .img img {
  width: 200px;
  height: 200px;
  margin: 0;
  padding: 0;
  border-radius: 12px;
  transition-duration: 5s;
}
.section2 .container .items .img {
  overflow: hidden;
  margin: 0;
}
.section2 .container .items:hover .img img {
  transform: scale(1.2);
  transition-duration: 5s;
  border-radius: 12px;
}
footer {
  display: flex;
  flex-direction: column;
  background-color: black;
  align-items: center;
  color: white;
}

.footer1 {
  display: flex;
  flex-direction: column;
  align-items: center;
  color: white;
  margin-top: 15px;
}
.social-media {
  display: flex;
  justify-content: center;
  color: white;
  flex-wrap: wrap;
}
.social-media a {
  color: white;
  margin: 20px;
  border-radius: 5px;
  margin-top: 10px;
  color: white;
}
.social-media a ion-icon {
  color: white;
  background-color: black;
}
.social-media a:hover ion-icon {
  color: red;
  transform: translateY(5px);
}
.footer2 {
  display: flex;
  width: 100%;
  justify-content: space-evenly;
  align-items: center;
  text-decoration: none;
  flex-wrap: wrap;
}
.footer0 {
  font-weight: 1200;
  transition-duration: 1s;
}
.footer0:hover {
  color: rgb(243, 168, 7);
}
.footer2 .heading {
  font-weight: 900;
  font-size: 18px;
}
.footer3 {
  margin-top: 60px;
  margin-bottom: 20px;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}
.footer2 .heading:hover {
  color: rgb(243, 168, 7);
}
.footer2 .div:hover {
  transform: scale(1.05);
}
.footer3 h4 {
  margin: 0 10px;
}
.footer2 div {
  margin: 10px;
}
.menu {
  visibility: hidden;
}
.heading1 .ham:active {
  color: red;
}
.items {
  overflow: hidden;
}
.ham,
.close {
  cursor: pointer;
}

@media screen and (max-width: 1250px) {
  .heading ul li {
    display: none;
  }

  .items {
    transform: scale(0.9);
  }
  .img-slider img {
    height: 60vw;
    width: 80vw;
  }
  .ham:active {
    color: red;
  }
  .menu {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .menu a ion-icon {
    position: absolute;
  }

  @keyframes slide1 {
    0% {
      left: 0vw;
    }
    15% {
      left: 0vw;
    }
    20% {
      left: -80vw;
    }
    32% {
      left: -80vw;
    }
    35% {
      left: -160vw;
    }
    47% {
      left: -160vw;
    }
    50% {
      left: -240vw;
    }
    63% {
      left: -240vw;
    }
    66% {
      left: -320vw;
    }
    79% {
      left: -320vw;
    }
    82% {
      left: -400vw;
    }
    100% {
      left: 0vw;
    }
  }
  .menu ul {
    display: flex;
    flex-direction: column;
    position: absolute;
    width: 100vw;
    height: 100vh;
    background-color: black;
    left: 0;
    top: 0;
    z-index: 11;
    align-items: center;
    justify-content: center;
    opacity: 1;
  }
  .close {
    z-index: 34;

    color: white;
    background-color: black;
  }
  .close:active {
    color: red;
  }
  .menu ul li {
    list-style: none;
    margin: 20px;
    border-top: 3px solid white;
    width: 80%;
    text-align: center;

    padding-top: 10px;
  }
  .menu ul li a {
    text-decoration: none;
    padding-top: 10px;
    color: white;
    font-weight: 900;
  }
  .menu ul li a:hover {
    color: rgb(240, 197, 6);
  }
  .img-slider {
    display: flex;
    float: left;
    position: relative;
    width: 80%;
    height: 60%;
    animation-name: slide1;
    animation-duration: 10s;
    animation-iteration-count: infinite;
    transition-duration: 5s;
  }
  .section1 {
    width: 80%;
    overflow: hidden;

    justify-content: center;
    align-items: center;
    margin: 0px auto;
  }

  .heading1 {
    opacity: 1;
    position: relative;
    bottom: 8px;
  }
  .search a {
    display: flex;
    flex-wrap: nowrap;
  }

  .heading1 .ham {
    background-color: black;
    color: white;
  }
  #input {
    width: 200px;
    flex-shrink: 2;
  }
  header {
    height: 150px;
  }
}
@media screen and (max-width: 550px) {
  .heading ul li {
    display: none;
  }
  .heading1 {
    opacity: 1;

    bottom: 8px;
  }

  header {
    height: 250px;
    flex-wrap: wrap;
    display: flex;
    flex-direction: column;
  }
  #input {
    width: 150px;
  }
  .close {
    z-index: 34;
  }

  .search a {
    display: flex;
    flex-wrap: nowrap;
  }
}  

     </style>
     
</head>


<body>
    <script>const close = document.querySelector(".close");
        const open = document.querySelector(".ham");
        const menu = document.querySelector(".menu");
        close.addEventListener("click", () => {
          menu.style.visibility = "hidden";
        });
        open.addEventListener("click", () => {
          menu.style.visibility = "visible";
        });</script>
  <header>
    <div class="logo"><a href="#">TECH HACKS</a></div>
    <div class="menu">
      <a href="#">
        <ion-icon name="close" class="close"></ion-icon>
      </a>

      <ul>
        <li><a href="#" class="under">HOME</a></li>
        <li><a href="#" class="under">SHOP</a></li>
        <li><a href="#" class="under">OUR PRODUCTS</a></li>
        <li><a href="#" class="under">CONTACT US</a></li>
        <li><a href="#" class="under">ABOUT US</a></li>
      </ul>
    </div>
    <div class="search">

      <a href=""><input type="text" placeholder="search products" id="input">
        <ion-icon class="s" name="search"></ion-icon>
      </a>
    </div>
    <div class="heading">
      <ul>
        <li><a href="#" class="under">HOME</a></li>
        <li><a href="#" class="under">SHOP</a></li>
        <li><a href="#" class="under">OUR PRODUCTS</a></li>
        <li><a href="#" class="under">CONTACT US</a></li>
        <li><a href="#" class="under">ABOUT US</a></li>
      </ul>
    </div>
    <div class="heading1">
      <ion-icon name="menu" class="ham"></ion-icon>
    </div>
  </header>
  <section>
    <div class="section">
      <div class="section1">
        <div class="img-slider">
          <img src="https://d2d22nphq0yz8t.cloudfront.net/88e6cc4b-eaa1-4053-af65-563d88ba8b26/https://media.croma.com/image/upload/v1662703724/Croma%20Assets/Communication/Mobiles/Images/261934_qgssvy.png/mxw_2048,s_webp,f_auto"alt="" class="img">
          <img src="https://d2d22nphq0yz8t.cloudfront.net/88e6cc4b-eaa1-4053-af65-563d88ba8b26/https://media.croma.com/image/upload/v1662703653/Croma%20Assets/Communication/Mobiles/Images/261933_eiuolg.png/mxw_2048,s_webp,f_auto" alt="" class="img">
          <img src="https://m.media-amazon.com/images/I/71WS-0ITj7L._AC_UY327_FMwebp_QL65_.jpg" alt="" class="img">
          <img src="https://m.media-amazon.com/images/I/61ahn9N38zL._AC_UY327_FMwebp_QL65_.jpg" alt="" class="img">
          <img src="https://m.media-amazon.com/images/I/41op1vdp-UL._SX300_SY300_QL70_FMwebp_.jpg" alt="" class="img">
          <img src="https://m.media-amazon.com/images/I/71geVdy6-OS._AC_UY327_FMwebp_QL65_.jpg" alt="" class="img">
          <img src="https://m.media-amazon.com/images/I/71geVdy6-OS._AC_UY327_FMwebp_QL65_.jpg" alt="" class="img">
          <img src="https://m.media-amazon.com/images/I/71Od5yJbohL._SX679_.jpg" alt="" class="img">
          <img src="https://m.media-amazon.com/images/I/71Od5yJbohL._AC_SR180,120_QL70_.jpg" alt="" class="img">
          <img src="https://m.media-amazon.com/images/I/716uVx3Wr5L._AC_UY327_FMwebp_QL65_.jpg" alt="" class="img">
        </div>

      </div>
      <div class="section2">
        <div class="container">
          <div class="items">
            <div class="img img1"><img src="https://rukminim1.flixcart.com/image/612/612/l0h1g280/speaker/mobile-tablet-speaker/z/a/u/por-1578-portronics-original-imagc97tf7pfxxsv.jpeg?q=70" alt=""></div>
            <div class="name">Speakers</div>
            <div class="price">From @499</div>
            <div class="info">Portonics bass speaker</div>
          </div>
          <div class="items">
            <div class="img img2"><img src="https://rukminim1.flixcart.com/image/612/612/l0sgyvk0/headphone/f/2/o/buds-z2-oneplus-original-imagcg5ghj3ptrpg.jpeg?q=70" alt=""></div>
            <div class="name">Earphones</div>
            <div class="price">From @99</div>
            <div class="info">One plus bullet Z2</div>
          </div>
          <div class="items">
            <div class="img img3"><img src="https://rukminim1.flixcart.com/image/612/612/ksw4ccw0/headphone/w/e/y/rockerz-255-pro-fast-charging-rockerz-255f-pro-boat-original-imag6cvfc9g2zqbw.jpeg?q=70" alt=""></div>
            <div class="name">Bluetooth headphones</div>
            <div class="price">From @899</div>
            <div class="info">Boat Rockerz bluetooth headphones</div>
          </div>
          <div class="items">
            <div class="img img1"><img src="https://rukminim1.flixcart.com/image/312/312/kwpam4w0/smartwatch/m/f/6/-original-imag9bm4kzqh9yfb.jpeg?q=70" alt=""></div>
            <div class="name"> Smart WATCH</div>
            <div class="price">From @1499</div>
            <div class="info">Fire Bolt BT calling watch</div>
          </div>
          <div class="items">
            <div class="img img1"><img src="https://rukminim1.flixcart.com/image/312/312/l19m93k0/mobile/o/l/f/note-11-pro-5g-21091116i-redmi-original-imagcvg4ghr3ykge.jpeg?q=70" alt=""></div>
            <div class="name">SMART PHONE</div>
            <div class="price">@19999</div>
            <div class="info">Redmi Note 11 pro</div>
          </div>
          <div class="items">
            <div class="img img1"><img src="https://images.pexels.com/photos/5552789/pexels-photo-5552789.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt=""></div>
            <div class="name">TELEVISION</div>
            <div class="price">From @10999</div>
            <div class="info">4k telivisions</div>
          </div>
          <div class="items">
            <div class="img img1"><img src="https://rukminim1.flixcart.com/image/612/612/xif0q/headphone/9/j/c/phantom-550-wings-original-imaggvzvebfyu5sq.jpeg?q=70" alt=""></div>
            <div class="name">TWS</div>
            <div class="price">From @12999</div>
            <div class="info"></div>
          </div>
          <div class="items">
            <div class="img img1"><img src="https://rukminim1.flixcart.com/image/312/312/k3q76a80/camera/a/9/y/sony-apsc-ilce-6100l-b-in5-mirrorless-original-imafm6msv5uzrmgt.jpeg?q=70" alt=""></div>
            <div class="name">Cameras</div>
            <div class="price">From @24999</div>
            <div class="info">SONY ILCE-6100L/B IN5 Mirrorless Camera</div>
          </div>
          <div class="items">
            <div class="img img1"><img src="https://rukminim1.flixcart.com/image/612/612/knt7zbk0/tripod/tripod/f/6/9/13-inch-flexible-gorillapod-tripod-with-mobile-attachment-for-original-imag2ezmvpfwzfyw.jpeg?q=70" alt=""></div>
            <div class="name">Camera Accessories</div>
            <div class="price">From @299</div>
            <div class="info">Tygot 13 inch Flexible Gorillapod Tripod</div>
          </div>
          <div class="items">
            <div class="img img1"><img src="https://rukminim1.flixcart.com/image/312/312/l3929ow0/computer/d/n/c/82c3a008ih-laptop-lenovo-original-imageexr8yzmydfd.jpeg?q=70" alt=""></div>
            <div class="name">LAPTOP</div>
            <div class="price">From @29999</div>
            <div class="info">Dell laptops</div>
          </div>
          <div class="items">
            <div class="img img1"><img src="https://rukminim1.flixcart.com/image/612/612/kzegk280/keyboard/multi-device-keyboard/h/0/h/champ-executive-multimedia-combo-tvs-electronics-original-imagbeyzvxbn6nsz.jpeg?q=70" alt=""></div>
             <div class="name">Laptop Accessories</div>
            <div class="price">From @999</div>
            <div class="info">KeyBoards,Mouses,etc</div>
          </div>
          <div class="items">
            <div class="img img1"><img src="https://rukminim1.flixcart.com/image/612/612/xif0q/printer/p/q/g/flow-n7000-snw1-hp-original-imaggwfgnhqthmbt.jpeg?q=70" alt=""></div>
            <div class="name">Printers</div>
            <div class="price">From @9999</div>
            <div class="info">HP Laserjet Pro M405n Single Function Monochrome Laser Printer</div>
          </div>
          <div class="items">
            <div class="img img1"><img src="https://rukminim1.flixcart.com/image/612/612/kx50gi80/projector/r/9/p/zeb-pixa-play-12-5-6-dobly-audio-led-projector-zebronics-original-imag9z3yujqmzqt4.jpeg?q=70" alt=""></div>
            <div class="name">Projectors</div>
            <div class="price">From @11999</div>
            <div class="info">ZEBRONICS Zeb-Pixa Play 12 with Dolby Audio Support & 720p HD </div>
          </div>
          <div class="items">
            <div class="img img1"><img src="https://rukminim1.flixcart.com/image/312/312/xif0q/tablet/d/d/n/-original-imaggp4gtdze4hfd.jpeg?q=70" alt=""></div>
            <div class="name">Tablets</div>
            <div class="price">From @9999</div>
            <div class="info">Realme tablet mini</div>
          </div>
          <div class="items">
            <div class="img img1"><img src="https://rukminim1.flixcart.com/image/612/612/xif0q/mobile-holder/b/g/f/stand-mobile-stand-holder-for-table-with-adjustable-height-360-original-imaghmhawg5wg9zz.jpeg?q=70" alt=""></div>
            <div class="name">mobile Accessories</div>
            <div class="price">From @99</div>
            <div class="info">Mobile holders,chargers</div>
          </div>
          <div class="items">
            <div class="img img1"><img src="https://rukminim1.flixcart.com/image/612/612/xif0q/power-bank/m/g/c/-original-imagg5zzxpdfrdrs.jpeg?q=70" alt=""></div>
            <div class="name">Power Banks</div>
            <div class="price">From @999</div>
            <div class="info">MI 10000mah powerbank</div>
          </div>
          <div class="items">
            <div class="img img1"><img src="https://rukminim1.flixcart.com/image/612/612/kr2e3680/pendrive/type-a-to-type-c/9/z/s/dual-drive-go-upto-150mb-s-sandisk-original-imag4xq5g7jxk8aw.jpeg?q=70" alt=""></div>
            <div class="name">Pendrives</div>
            <div class="price">From @299</div>
            <div class="info">HP 32 gb pendrives</div>
          </div>
          <div class="items">
            <div class="img img1"><img src="https://rukminim1.flixcart.com/image/612/612/k33c4nk0/smart-assistant/a/j/k/nest-mini-ga00781-in-google-original-imafmauqguud8wsz.jpeg?q=70" alt=""></div>
            <div class="name">Assistants</div>
            <div class="price">From @4999</div>
            <div class="info">Google Nest mini</div>
          </div>
        </div>

      </div>
    </div>

  </section>
  <footer>
    <div class="footer0">
      <h1>TECH HACKS</h1>
    </div>
    <div class="footer1 ">
      Connect with us at<div class="social-media">
        <a href="#">
          <ion-icon name="logo-facebook"></ion-icon>
        </a>
        <a href="#">
          <ion-icon name="logo-linkedin"></ion-icon>
        </a>
        <a href="#">
          <ion-icon name="logo-youtube"></ion-icon>
        </a>
        <a href="#">
          <ion-icon name="logo-instagram"></ion-icon>
        </a>
        <a href="#">
          <ion-icon name="logo-twitter"></ion-icon>
        </a>
      </div>
    </div>
    <div class="footer2">
      <div class="product">
        <div class="heading">Products</div>
        <div class="div">Sell your Products</div>
        <div class="div">Advertise</div>
        <div class="div">Pricing</div>
        <div class="div">Product Buisness</div>

      </div>
      <div class="services">
        <div class="heading">Services</div>
        <div class="div">Return</div>
        <div class="div">Cash Back</div>
        <div class="div">Affiliate Marketing</div>
        <div class="div">Others</div>
      </div>
      <div class="Company">
        <div class="heading">Company</div>
        <div class="div">Complaint</div>
        <div class="div">Careers</div>
        <div class="div">Affiliate Marketing</div>
        <div class="div">Support</div>
      </div>
      <div class="Get Help">
        <div class="heading">Get Help</div>
        <div class="div">Help Center</div>
        <div class="div">Privacy Policy</div>
        <div class="div">Terms</div>
        <div class="div">Login</div>
      </div>
    </div>
    <div class="footer3">Copyright © <h4>TECH HACKS</h4> 2021-2028</div>
  </footer>
  <script src="https://unpkg.com/ionicons@4.5.10-0/dist/ionicons.js"></script>
  <script src="./ecommerce.js"></script>

</body>


</html>
