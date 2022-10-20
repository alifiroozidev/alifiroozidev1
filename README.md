Here’s some of my favorite subjects that I tried make them only by Web technologies like JavaScript! That was a nice challenge that could improve my web development skills. Check out the Repos
![subjects](web-ab.png)
before programming I was a 3D artist years ago and now I can create 3D AR and VR commercial apps and 3D web experiences with the help of WebGL and javascript
<link
      rel="stylesheet"
      href="https://unpkg.com/swiper/swiper-bundle.min.css"
    />


    <style>
      html,
      body {
      direction:rtl;
        position: relative;
        height: 100%;
      }

      body {
        background: #888;
        font-family: Helvetica Neue, Helvetica, Arial, sans-serif;
        font-size: 14px;
        color: #000;
        margin: 0;
        padding: 0;
      }

      .swiper {
        width: 100%;
        padding-top: 50px;
        padding-bottom: 50px; 
        
      }

      .swiper-slide {
        background-position: center;
        background-size: cover;
        width: 300px;
        height: 400px;
        border-radius:20px;
        background:#fff;
        /*  box-shadow: 0px 0px 30px 0px #00000066;*/
        
      }

      .swiper-slide img {
        display: block;
        width: 90%;
        margin:5%;
        border-radius:20px;
           
      }
    </style>

    <!-- Swiper -->
    <div class="swiper mySwiper">
      <div class="swiper-wrapper">
        <div class="swiper-slide">
        
          <img src="https://swiperjs.com/demos/images/nature-1.jpg" />
        </div>
        <div class="swiper-slide">
          <img src="https://swiperjs.com/demos/images/nature-2.jpg" />
        </div>
        
        <div class="swiper-slide">
          <img src="https://swiperjs.com/demos/images/nature-3.jpg" />
        </div>
        
        <div class="swiper-slide">
          <img src="https://swiperjs.com/demos/images/nature-4.jpg" />
        </div>
        
        <div class="swiper-slide">
          <img src="https://swiperjs.com/demos/images/nature-5.jpg" />
        </div>
        
        <div class="swiper-slide">
          <img src="https://swiperjs.com/demos/images/nature-6.jpg" />
        </div>
        
        <div class="swiper-slide">
          <img src="https://swiperjs.com/demos/images/nature-7.jpg" />
        </div>
        
 
      </div>
      <div class="swiper-pagination"></div>
    </div>

    <!-- Swiper JS -->
    <script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>

    <!-- Initialize Swiper -->
    
    
    <script>
      var swiper = new Swiper(".mySwiper", {
        effect: "coverflow",
        grabCursor: true,
        centeredSlides: true,
        slidesPerView: "auto",
        coverflowEffect: {
          rotate: 20,
          stretch: 0,
          depth: 300,
          modifier: 1,
          slideShadows: true,
        },
        pagination: {
          el: ".swiper-pagination",
           clickable: true,
              dynamicBullets: true,
        },
      });
      

    </script>
