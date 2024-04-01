<template>
  <div class="container-fluid">
            
            <div class="row">
                <div class="col-md-12">
                    <div class="hamburger-menu mobile">
                        <div class="mobile-logo text-center">
                            <img :src="require('@/assets/images/lovely-logo.png')" alt="lovely-logo">
                        </div>
                        <div class="button_container" id="toggle"><span class="top"></span><span class="middle"></span><span class="bottom"></span></div>
                        <div class="overlay" id="overlay">
                            <nav class="overlay-menu">
                                <ul>
                                    <li><a href="#home">HOME</a></li>
                                    <li><a href="#about">ABOUT</a></li>
                                    <li><a href="#gallery">MY GALLERY</a></li>
                                    <li><a href="#contact">CONTACT ME!</a></li>
                                </ul>
                            </nav>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="row menu top-nav align-items-center desktop">
                <div class="col-md-3 logo-container" >
                  <img :src="require('@/assets/images/lovely-logo.png')" alt="lovely-logo">
                </div>
                <div class="col-md-9 right-menu">
                    <ul class="navigation">
                        <li>
                            <a href="#home">HOME</a>
                        </li>
                        <li>
                            <a href="#about">ABOUT ME</a>
                        </li>
                        <li>
                            <a href="#gallery">GALLERY</a>
                        </li>
                        <li>
                            <a href="#contact">CONTACT ME</a>
                        </li>
                   </ul>
                </div>
            </div>
            <div class="row align-items-center text-center bg-container" id="home">
                <div class="bg-overlay"></div>
                <div class="col-md-12 box-content">
                    <h1>Portfolio</h1>
                    <div class="verse">
                        <span>For I know the plans I have for you,” declares the Lord, “plans to prosper you and not to harm you, plans to give you hope and a future.</span>
                        <br><small>-Jeremiah 29'11</small>
                    </div>
                </div>
            </div>
            <div class="row align-items-center text-center bg-title team" id="about">
                <div class="bg-overlay"></div>
                <div class="col-md-12">
                    <h1>ABOUT ME</h1>
                </div>
            </div>
            <div class="row about-box-content team-box">
                <h1>Hola Amigos! Somos Preciosa Mancuerna.</h1>
                <div class="col-md-6 col-sm-12 text-right">
                    <div class="box">
                        <a class="" data-bs-toggle="modal" data-bs-target="#exampleModal1">Lovely Jean Garcia Celades</a>
                        <div class="social">
                            <ul>
                                <li>
                                    <a href="https://www.facebook.com/Lovely.Jean.8?mibextid=LQQJ4d" target="_blank">
                                        <i class="fa-brands fa-facebook"></i>
                                    </a>
                                </li>
                                <li>
                                    <a href="https://www.instagram.com/ms.love_on_ig?igsh=MTRuMnJzanZhNWJ5ag%3D%3D&utm_source=qr" target="_blank">
                                        <i class="fa-brands fa-instagram"></i>
                                    </a>
                                </li>
                                <li>
                                    <a href="mailto:lovelyjean0882@gmail.com">
                                        <i class="fa-brands fa-google"></i>
                                    </a>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-sm-12 about-content">
                    <p>
                        Hi I am Lovely Jean Garcia Celades, a 22-year-old individual residing in the vibrant town of Catarman, Cordova, Cebu. 
                        My passion for learning and exploring new ideas fuels my enthusiasm for various projects and endeavors. I am driven by a strong sense of self-motivation, constantly seeking ways to improve myself and excel in everything I do.
                    </p>
                    <p>
                        Reliability is one of my core values, and I take pride in being someone others can depend on. Whether it's meeting deadlines, fulfilling commitments, or supporting my team, I strive to be a reliable and trustworthy individual. Responsibility is another aspect that defines my work ethic. 
                        I take ownership of my actions and decisions, always aiming for excellence and accountability.
                    </p>
                </div>
            </div>
            <div class="row" id="gallery"></div>
            <div class="row align-items-center text-center bg-title gallery-head">
                <div class="bg-overlay"></div>
                <div class="col-md-12">
                    <h1>GALLERY</h1>
                </div>
            </div>
            <div class="row gallery">
                <div class="col-md-4 box">
                    <div class="box-img">
                      <img :src="require('@/assets/images/Lovely-6.jpeg')" alt="fp-logo">
                    </div>
                </div>
                <div class="col-md-4 box">
                    <div class="box-img">
                      <img :src="require('@/assets/images/Lovely-1.jpeg')" alt="fp-logo">
                    </div>
                </div>
                <div class="col-md-4 box">
                    <div class="box-img">
                      <img :src="require('@/assets/images/Lovely-2.jpeg')" alt="fp-logo">
                    </div>
                </div>
                <div class="col-md-4 box">
                    <div class="box-img">
                      <img :src="require('@/assets/images/Lovely-3.jpeg')" alt="fp-logo">
                    </div>
                </div>
                <div class="col-md-4 box">
                    <div class="box-img">
                      <img :src="require('@/assets/images/Lovely-4.jpeg')" alt="fp-logo">
                    </div>
                </div>
                <div class="col-md-4 box">
                    <div class="box-img">
                      <img :src="require('@/assets/images/Lovely-5.jpeg')" alt="fp-logo">
                    </div>
                </div>
            </div>
             <div class="row" id="contact"></div>
            <div class="row align-items-center text-center bg-title contact">
                <div class="bg-overlay"></div>
                <div class="col-md-12">
                    <h1>CONTACT ME</h1>
                </div>
            </div>
            <div class="row contact-container">
                <div class="col-md-12">
                    <div class="row contact-box align-items-center">
                        <div class="col-md-8 form text-center">
                            <h1>Get in Touch!</h1>
                            <span>Feel free to message me</span>
                            <form action="">
                                <input type="text" name="" id="" placeholder="Your Full Name">
                                <input type="text" name="" id="" placeholder="Your Email">
                                <textarea name="" id="" cols="30" rows="10" placeholder="Type here your concerns"></textarea>
                                <button>Submit</button>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row footer align-items-center">
                <div class="col-md-12 text-center">
                    <p>Copyright 2023. All Rights Reserved</p>
                </div>
            </div>
        </div>
</template>

<script>
export default {
  name: 'App',
  mounted() {
    $('#toggle').click(function() {
      $(this).toggleClass('active');
      $('#overlay').toggleClass('open');
    });
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
