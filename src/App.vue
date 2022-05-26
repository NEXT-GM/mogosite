<template>
  <div id="app">
    <router-view/>
  </div>
</template>
<script>
export default {

}
</script>

<style>
.material-icons, .material-icons-outlined {
  /* font-family: 'Material Icons'; */
  font-weight: normal;
  font-style: normal;
  /* font-size: 42px; */
  display: inline-block;
  line-height: 1;
  text-transform: none;
  letter-spacing: normal;
  word-wrap: normal;
  white-space: nowrap;
  direction: ltr;

  /* Support for all WebKit browsers. */
  -webkit-font-smoothing: antialiased;
  /* Support for Safari and Chrome. */
  text-rendering: optimizeLegibility;

  /* Support for Firefox. */
  -moz-osx-font-smoothing: grayscale;

  /* Support for IE. */
  font-feature-settings: 'liga';
}

/* Rules for using icons as black on a light background. */
.material-icons.md-dark, .material-icons-outlined.md-dark { color: rgba(0, 0, 0, 0.54); }
.material-icons.md-dark.md-inactive, .material-icons-outlined.md-dark.md-inactive { color: rgba(0, 0, 0, 0.26); }

/* Rules for using icons as white on a dark background. */
.material-icons.md-light, .material-icons-outlined.md-light { color: rgba(255, 255, 255, 1); }
.material-icons.md-light.md-inactive, .material-icons-outlined.md-light.md-inactive { color: rgba(255, 255, 255, 0.3); }

/* Rules for sizing the icon. */
.material-icons.md-18, .material-icons-outlined.md-18 { font-size: 18px; }
.material-icons.md-24, .material-icons-outlined.md-24 { font-size: 24px; }
.material-icons.md-36, .material-icons-outlined.md-36 { font-size: 36px; }
.material-icons.md-42, .material-icons-outlined.md-42 { font-size: 42px; }
.material-icons.md-48, .material-icons-outlined.md-48 { font-size: 48px; }

body {
  min-height: 100vh;
}
#app {
  min-height: 100vh;
}
</style>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="assets/css/style.css">
    <link href="https://fonts.googleapis.com/css?family=Kaushan+Script|Montserrat:300i,400,700&amp;subset=cyrillic-ext" rel="stylesheet">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.2/css/all.css" integrity="sha384-fnmOCqbTlWIlj8LyTjo7mOUStjsKC4pOpQbqyi7RrhN7udi9RwhKkMHpvLbHG9Sr" crossorigin="anonymous">
    <link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.css"/>
    <title>Mogo</title>
</head>
<body>


<header class="header" id="header">
    <div class="container">
        <div class="header__inner">
            <div class="header__logo" data-scroll="#intro">MoGo</div>

            <nav class="nav" id="nav">
                <a class="nav__link" href="#" data-scroll="#about">About</a>
                <a class="nav__link" href="#" data-scroll="#services">Service</a>
                <a class="nav__link" href="#" data-scroll="#blog">Blog</a>
                <a class="nav__link" href="#" data-scroll="#works">Work</a>
                <a class="nav__link" href="#" data-scroll="#footer">Contact</a>
                <a class="nav__link" href="#">
                    <i class="fas fa-shopping-cart"></i>
                </a>
                <a class="nav__link" href="#">
                    <i class="fas fa-search"></i>
                </a>
            </nav>

            <button class="nav-toggle" id="nav_toggle" type="button">
                <span class="nav-toggle__item">Menu</span>
            </button>
        </div>
    </div>
</header>


<div class="page">

    <!-- Intro -->
    <div class="intro" id="intro">
        <div class="container">
            <div class="intro__inner">
                <h2 class="intro__suptitle">Creative Template</h2>
                <h1 class="intro__title">Welcome to MoGo</h1>

                <a class="btn" href="#">Learn More</a>
            </div>
        </div>

        <div class="slider">
            <div class="container">
                <div class="slider__inner">
                    <div class="slider__item active">
                        <span class="slider__num">01</span>
                        <span class="slider__text">Intro</span>
                    </div>
                    <div class="slider__item">
                        <span class="slider__num">02</span>
                        <span class="slider__text">Work</span>
                    </div>
                    <div class="slider__item">
                        <span class="slider__num">03</span>
                        <span class="slider__text">About</span>
                    </div>
                    <div class="slider__item">
                        <span class="slider__num">04</span>
                        <span class="slider__text">Contacts</span>
                    </div>
                </div>
            </div>
        </div>

    </div><!-- /.intro -->


    <!-- About -->
    <section class="section" id="about">
        <div class="container">

            <div class="section__header">
                <h3 class="section__suptitle">What we do</h3>
                <h2 class="section__title">Story about us</h2>
                <div class="section__text">
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                </div>
            </div>

            <div class="card">
                <div class="card__item">
                    <div class="card__inner">
                        <div class="card__img">
                            <img src="assets/images/about/1.jpg" alt="">
                        </div>
                        <div class="card__text">super team</div>
                    </div>
                </div>

                <div class="card__item">
                    <div class="card__inner">
                        <div class="card__img">
                            <img src="assets/images/about/2.jpg" alt="">
                        </div>
                        <div class="card__text">super team</div>
                    </div>
                </div>

                <div class="card__item">
                    <div class="card__inner">
                        <div class="card__img">
                            <img src="assets/images/about/3.jpg" alt="">
                        </div>
                        <div class="card__text">super team</div>
                    </div>
                </div>
            </div>

        </div><!-- /.container -->
    </section>


    <!-- Statistics -->
    <div class="statistics">
        <div class="container">

            <div class="stat">
                <div class="stat__item">
                    <div class="stat__count">42</div>
                    <div class="stat__text">Web Design Projects</div>
                </div>
                <div class="stat__item">
                    <div class="stat__count">123</div>
                    <div class="stat__text">happy client</div>
                </div>
                <div class="stat__item">
                    <div class="stat__count">15</div>
                    <div class="stat__text">award winner</div>
                </div>
                <div class="stat__item">
                    <div class="stat__count">99</div>
                    <div class="stat__text">cup of coffee</div>
                </div>
                <div class="stat__item">
                    <div class="stat__count">24</div>
                    <div class="stat__text">members</div>
                </div>
            </div>

        </div>
    </div>


    <!-- Services -->
    <section class="section" id="services">
        <div class="container">

            <div class="section__header">
                <h3 class="section__suptitle">We work with</h3>
                <h2 class="section__title">Amazing Services</h2>
            </div>

            <div class="services">
                <div class="services__item  services__item--border">
                    <img class="services__icon" src="assets/images/services/photography.png" alt="">

                    <div class="services__title">Photography</div>
                    <div class="services__text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</div>
                </div>
                <div class="services__item  services__item--border">
                    <img class="services__icon" src="assets/images/services/webdesign.png" alt="">

                    <div class="services__title">Web Design</div>
                    <div class="services__text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</div>
                </div>
                <div class="services__item  services__item--border">
                    <img class="services__icon" src="assets/images/services/creativity.png" alt="">

                    <div class="services__title">Creativity</div>
                    <div class="services__text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</div>
                </div>
                <div class="services__item">
                    <img class="services__icon" src="assets/images/services/seo.png" alt="">

                    <div class="services__title">seo</div>
                    <div class="services__text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</div>
                </div>
                <div class="services__item">
                    <img class="services__icon" src="assets/images/services/css-html.png" alt="">

                    <div class="services__title">Css/Html</div>
                    <div class="services__text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</div>
                </div>
                <div class="services__item">
                    <img class="services__icon" src="assets/images/services/digital.png" alt="">

                    <div class="services__title">digital</div>
                    <div class="services__text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</div>
                </div>
            </div>

        </div><!-- /.container -->
    </section>


    <!-- Devices -->
    <section class="section  section--devices">
        <div class="container">

            <div class="section__header">
                <h3 class="section__suptitle">For all devices</h3>
                <h2 class="section__title">Unique design</h2>
            </div>

            <div class="devices">
                <img class="devices__item" src="assets/images/ipad.png" alt="">
                <img class="devices__item  devices__item--iphone" src="assets/images/iphone.png" alt="">
            </div>

        </div>
    </section>


    <!-- Wedo -->
    <section class="section">
        <div class="container">

            <div class="section__header">
                <h3 class="section__suptitle">Service</h3>
                <h2 class="section__title">what we do</h2>
                <div class="section__text">
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                </div>
            </div>

            <div class="wedo">
                <div class="wedo__item">
                    <img class="wedo__img" src="assets/images/wedo.jpg" alt="">
                </div>

                <div class="wedo__item">

                    <div class="accordion">
                        <div class="accordion__item" data-collapse="#wedo_1">
                            <div class="accordion__header">
                                <img class="accordion__icon" src="assets/images/services/photography.png" alt="">
                                <div class="accordion__title">Photography</div>
                            </div>
                            <div class="accordion__content" id="wedo_1">
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
                            </div>
                        </div>

                        <div class="accordion__item active" data-collapse="#wedo_2">
                            <div class="accordion__header">
                                <img class="accordion__icon" src="assets/images/services/creativity.png" alt="">
                                <div class="accordion__title">Creativity</div>
                            </div>
                            <div class="accordion__content" id="wedo_2">
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
                            </div>
                        </div>

                        <div class="accordion__item" data-collapse="#wedo_3">
                            <div class="accordion__header">
                                <img class="accordion__icon" src="assets/images/services/webdesign.png" alt="">
                                <div class="accordion__title">web design</div>
                            </div>
                            <div class="accordion__content" id="wedo_3">
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
                            </div>
                        </div>
                    </div><!-- /.accordion -->

                </div><!-- /.wedo__item -->
            </div><!-- /.wedo -->

        </div>
    </section>


    <!-- Reviews 1 -->
    <div class="section  section--gray">
        <div class="container">

            <div class="reviews">
                <div data-slider>
                    <div>
                        <div class="reviews__item">
                            <img class="reviews__photo" src="assets/images/avatar.png" alt="">
                            <div class="reviews__text">“Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation.”</div>
                            <div class="reviews__author">Jon Doe</div>
                        </div>
                    </div>

                    <div>
                        <div class="reviews__item">
                            <img class="reviews__photo" src="assets/images/avatar.png" alt="">
                            <div class="reviews__text">“Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation.”</div>
                            <div class="reviews__author">Jon Doe</div>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </div>


    <!-- Team -->
    <section class="section">
        <div class="container">

            <div class="section__header">
                <h3 class="section__suptitle">Who we are</h3>
                <h2 class="section__title">Meet our team</h2>
                <div class="section__text">
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                </div>
            </div>

            <div class="card">
                <div class="card__item">
                    <div class="card__inner">
                        <div class="card__img">
                            <img src="assets/images/team/1.jpg" alt="">
                        </div>
                        <div class="card__text">
                            <div class="social">
                                <a class="social__item" href="#" target="_blank">
                                    <i class="fab fa-facebook-f"></i>
                                </a>
                                <a class="social__item" href="#" target="_blank">
                                    <i class="fab fa-twitter"></i>
                                </a>
                                <a class="social__item" href="#" target="_blank">
                                    <i class="fab fa-pinterest-p"></i>
                                </a>
                                <a class="social__item" href="#" target="_blank">
                                    <i class="fab fa-instagram"></i>
                                </a>
                            </div>
                        </div>
                    </div>
                    <div class="card__info">
                        <div class="card__name">Matthew Dix</div>
                        <div class="card__prof">Graphic Design</div>
                    </div>
                </div><!-- /.card__item -->

                <div class="card__item">
                    <div class="card__inner">
                        <div class="card__img">
                            <img src="assets/images/team/2.jpg" alt="">
                        </div>
                        <div class="card__text">
                            <div class="social">
                                <a class="social__item" href="#" target="_blank">
                                    <i class="fab fa-facebook-f"></i>
                                </a>
                                <a class="social__item" href="#" target="_blank">
                                    <i class="fab fa-twitter"></i>
                                </a>
                                <a class="social__item" href="#" target="_blank">
                                    <i class="fab fa-pinterest-p"></i>
                                </a>
                                <a class="social__item" href="#" target="_blank">
                                    <i class="fab fa-instagram"></i>
                                </a>
                            </div>
                        </div>
                    </div>
                    <div class="card__info">
                        <div class="card__name">Christopher Campbell</div>
                        <div class="card__prof">Branding/UX design</div>
                    </div>
                </div><!-- /.card__item -->

                <div class="card__item">
                    <div class="card__inner">
                        <div class="card__img">
                            <img src="assets/images/team/3.jpg" alt="">
                        </div>
                        <div class="card__text">
                            <div class="social">
                                <a class="social__item" href="#" target="_blank">
                                    <i class="fab fa-facebook-f"></i>
                                </a>
                                <a class="social__item" href="#" target="_blank">
                                    <i class="fab fa-twitter"></i>
                                </a>
                                <a class="social__item" href="#" target="_blank">
                                    <i class="fab fa-pinterest-p"></i>
                                </a>
                                <a class="social__item" href="#" target="_blank">
                                    <i class="fab fa-instagram"></i>
                                </a>
                            </div>
                        </div>
                    </div>
                    <div class="card__info">
                        <div class="card__name">Michael Fertig </div>
                        <div class="card__prof">Developer</div>
                    </div>
                </div><!-- /.card__item -->

            </div><!-- /.card -->

        </div><!-- /.container -->
    </section>


    <!-- Logos -->
    <div class="section  section--gray">
        <div class="container">

            <div class="logos">
                <div class="logos__item">
                    <img class="logos__img" src="assets/images/logos/1.png" alt="">
                </div>
                <div class="logos__item">
                    <img class="logos__img" src="assets/images/logos/2.png" alt="">
                </div>
                <div class="logos__item">
                    <img class="logos__img" src="assets/images/logos/3.png" alt="">
                </div>
                <div class="logos__item">
                    <img class="logos__img" src="assets/images/logos/4.png" alt="">
                </div>
                <div class="logos__item">
                    <img class="logos__img" src="assets/images/logos/5.png" alt="">
                </div>
                <div class="logos__item">
                    <img class="logos__img" src="assets/images/logos/6.png" alt="">
                </div>
            </div>

        </div>
    </div>


    <!-- Works -->
    <section class="section" id="works">
        <div class="container">
            <div class="section__header">
                <h3 class="section__suptitle">What we do</h3>
                <h2 class="section__title">some of our work</h2>
                <div class="section__text">
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                </div>
            </div>
        </div>

        <div class="works">
            <div class="works__col">
                <div class="works__item">
                    <img class="works__image" src="assets/images/works/1.jpg" alt="">
                    <div class="works__info">
                        <div class="works__title">creatively designed</div>
                        <div class="works__text">Lorem ipsum dolor sit</div>
                    </div>
                </div>
                <div class="works__item">
                    <img class="works__image" src="assets/images/works/2.jpg" alt="">
                    <div class="works__info">
                        <div class="works__title">creatively designed</div>
                        <div class="works__text">Lorem ipsum dolor sit</div>
                    </div>
                </div>
            </div>

            <div class="works__col">
                <div class="works__item">
                    <img class="works__image" src="assets/images/works/3.jpg" alt="">
                    <div class="works__info">
                        <div class="works__title">creatively designed</div>
                        <div class="works__text">Lorem ipsum dolor sit</div>
                    </div>
                </div>
                <div class="works__item">
                    <img class="works__image" src="assets/images/works/4.jpg" alt="">
                    <div class="works__info">
                        <div class="works__title">creatively designed</div>
                        <div class="works__text">Lorem ipsum dolor sit</div>
                    </div>
                </div>
            </div>

            <div class="works__col">
                <div class="works__item">
                    <img class="works__image" src="assets/images/works/5.jpg" alt="">
                    <div class="works__info">
                        <div class="works__title">creatively designed</div>
                        <div class="works__text">Lorem ipsum dolor sit</div>
                    </div>
                </div>
            </div>

            <div class="works__col">
                <div class="works__item">
                    <img class="works__image" src="assets/images/works/6.jpg" alt="">
                    <div class="works__info">
                        <div class="works__title">creatively designed</div>
                        <div class="works__text">Lorem ipsum dolor sit</div>
                    </div>
                </div>
                <div class="works__item">
                    <img class="works__image" src="assets/images/works/7.jpg" alt="">
                    <div class="works__info">
                        <div class="works__title">creatively designed</div>
                        <div class="works__text">Lorem ipsum dolor sit</div>
                    </div>
                </div>
            </div>
        </div><!-- /.works -->
    </section>


    <!-- Reviews 2 -->
    <div class="section">
        <div class="container">

            <div class="reviews">

                <div data-slider>
                    <div>
                        <div class="reviews__item">
                            <img class="reviews__photo" src="assets/images/avatar.png" alt="">
                            <div class="reviews__text">“Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation.”</div>
                            <div class="reviews__author">Jon Doe</div>
                        </div>
                    </div>

                    <div>
                        <div class="reviews__item">
                            <img class="reviews__photo" src="assets/images/avatar.png" alt="">
                            <div class="reviews__text">“Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation.”</div>
                            <div class="reviews__author">Jon Doe</div>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </div>


    <!-- Clients -->
    <section class="section  section--clients">
        <div class="container">

            <div class="section__header">
                <h3 class="section__suptitle">Happy Clients</h3>
                <h2 class="section__title">What people say</h2>
            </div>

            <div class="clients">
                <div class="clients__item">
                    <img class="clients__photo" src="assets/images/clients/1.png" alt="">
                    <div class="clients__content">
                        <div class="clients__name">Matthew Dix</div>
                        <div class="clients__prof">Graphic Design</div>
                        <div class="clients__text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim.</div>
                    </div>
                </div>

                <div class="clients__item">
                    <img class="clients__photo" src="assets/images/clients/2.png" alt="">
                    <div class="clients__content">
                        <div class="clients__name">Nick Karvounis</div>
                        <div class="clients__prof">Graphic Design</div>
                        <div class="clients__text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim.</div>
                    </div>
                </div>

                <div class="clients__item">
                    <img class="clients__photo" src="assets/images/clients/3.png" alt="">
                    <div class="clients__content">
                        <div class="clients__name">Jaelynn Castillo </div>
                        <div class="clients__prof">Graphic Design</div>
                        <div class="clients__text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim.</div>
                    </div>
                </div>

                <div class="clients__item">
                    <img class="clients__photo" src="assets/images/clients/4.png" alt="">
                    <div class="clients__content">
                        <div class="clients__name">Mike Petrucci</div>
                        <div class="clients__prof">Graphic Design</div>
                        <div class="clients__text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim.</div>
                    </div>
                </div>
            </div><!-- /.clients -->

        </div><!-- /.container -->
    </section>


    <!-- Blog -->
    <section class="section" id="blog">
        <div class="container">

            <div class="section__header">
                <h3 class="section__suptitle">Our stories</h3>
                <h2 class="section__title">Latest blog</h2>
            </div>

            <div class="blog">
                <div class="blog__item">
                    <div class="blog__header">
                        <a href="#">
                            <img class="blog__photo" src="assets/images/blog/1.jpg" alt="">
                        </a>
                        <div class="blog__date">
                            <div class="blog__date-day">15</div>
                            Jan
                        </div>
                    </div>
                    <div class="blog__content">
                        <div class="blog__title">
                            <a href="#">Lorem ipsum dolor sit amet</a>
                        </div>
                        <div class="blog__text">Consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</div>
                    </div>
                    <div class="blog__footer">
                        <div class="blog-stat">
                            <span class="blog-stat__item">
                                <i class="far fa-eye"></i> 542
                            </span>
                            <span class="blog-stat__item">
                                <i class="far fa-comment-dots"></i> 17
                            </span>
                        </div>
                    </div>
                </div>

                <div class="blog__item">
                    <div class="blog__header">
                        <a href="#">
                            <img class="blog__photo" src="assets/images/blog/2.jpg" alt="">
                        </a>
                        <div class="blog__date">
                            <div class="blog__date-day">15</div>
                            Jan
                        </div>
                    </div>
                    <div class="blog__content">
                        <div class="blog__title">
                            <a href="#">Lorem ipsum dolor sit amet</a>
                        </div>
                        <div class="blog__text">Consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</div>
                    </div>
                    <div class="blog__footer">
                        <div class="blog-stat">
                            <span class="blog-stat__item">
                                <i class="far fa-eye"></i> 542
                            </span>
                            <span class="blog-stat__item">
                                <i class="far fa-comment-dots"></i> 17
                            </span>
                        </div>
                    </div>
                </div>

                <div class="blog__item">
                    <div class="blog__header">
                        <a href="#">
                            <img class="blog__photo" src="assets/images/blog/3.jpg" alt="">
                        </a>
                        <div class="blog__date">
                            <div class="blog__date-day">15</div>
                            Jan
                        </div>
                    </div>
                    <div class="blog__content">
                        <div class="blog__title">
                            <a href="#">Lorem ipsum dolor sit amet</a>
                        </div>
                        <div class="blog__text">Consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</div>
                    </div>
                    <div class="blog__footer">
                        <div class="blog-stat">
                            <span class="blog-stat__item">
                                <i class="far fa-eye"></i> 542
                            </span>
                            <span class="blog-stat__item">
                                <i class="far fa-comment-dots"></i> 17
                            </span>
                        </div>
                    </div>
                </div>
            </div><!-- /.blog -->

        </div><!-- /.container -->
    </section>


    <!-- Map -->
    <section class="section  section--map">
        <div class="container">
            <div class="map">
                <h2 class="map__title">
                    <div><i class="fas fa-map-marker-alt"></i></div>
                    <a href="https://goo.gl/maps/F8YpeCGqwrG2" target="_blank">Open Map</a>
                </h2>
            </div>
        </div>
    </section>


    <!-- Footer -->
    <footer class="footer" id="footer">
        <div class="container">

            <div class="footer__inner">
                <div class="footer__col  footer__col--first">
                    <div class="footer__logo">MoGo</div>
                    <div class="footer__text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</div>

                    <div class="footer__social">
                        <div class="footer__social-header">
                            <b>15k</b> followers
                        </div>
                        <div class="footer__social-content">
                            Follow Us:
                            <a href="#" target="_blank">
                                <i class="fab fa-facebook"></i>
                            </a>
                            <a href="#" target="_blank">
                                <i class="fab fa-twitter"></i>
                            </a>
                            <a href="#" target="_blank">
                                <i class="fab fa-instagram"></i>
                            </a>
                        </div>
                    </div>

                    <form class="subscribe" action="/" method="post">
                        <input class="subscribe__input" type="email" name="name" placeholder="Your Email...">
                        <button class="subscribe__btn" type="submit">Subscribe</button>
                    </form>
                </div><!-- /.footer__col -->

                <div class="footer__col  footer__col--second">
                    <div class="footer__title">Blogs</div>

                    <div class="blogs">
                        <div class="blogs__item">
                            <img class="blogs__img" src="assets/images/blog/1.jpg" alt="">
                            <div class="blogs__content">
                                <a class="blogs__title" href="#">Lorem ipsum dolor sit amet, consectetur adipiscing</a>
                                <div class="blogs__date">Jan 9, 2016</div>
                            </div>
                        </div>

                        <div class="blogs__item">
                            <img class="blogs__img" src="assets/images/blog/2.jpg" alt="">
                            <div class="blogs__content">
                                <a class="blogs__title" href="#">Lorem ipsum dolor</a>
                                <div class="blogs__date">Jan 9, 2016</div>
                            </div>
                        </div>

                        <div class="blogs__item">
                            <img class="blogs__img" src="assets/images/blog/3.jpg" alt="">
                            <div class="blogs__content">
                                <a class="blogs__title" href="#">Lorem ipsum dolor sit amet, consectetur adipiscing</a>
                                <div class="blogs__date">Jan 9, 2016</div>
                            </div>
                        </div>
                    </div><!-- /.blogs -->
                </div>

                <div class="footer__col  footer__col--third">
                    <div class="footer__title">Instagram</div>

                    <div class="instagram">
                        <a class="instagram__item" href="#" target="_blank">
                            <img src="assets/images/instagram/1.jpg" alt="">
                        </a>
                        <a class="instagram__item" href="#" target="_blank">
                            <img src="assets/images/instagram/2.jpg" alt="">
                        </a>
                        <a class="instagram__item" href="#" target="_blank">
                            <img src="assets/images/instagram/3.jpg" alt="">
                        </a>
                        <a class="instagram__item" href="#" target="_blank">
                            <img src="assets/images/instagram/4.jpg" alt="">
                        </a>
                        <a class="instagram__item" href="#" target="_blank">
                            <img src="assets/images/instagram/5.jpg" alt="">
                        </a>
                        <a class="instagram__item" href="#" target="_blank">
                            <img src="assets/images/instagram/6.jpg" alt="">
                        </a>
                        <a class="instagram__item" href="#" target="_blank">
                            <img src="assets/images/instagram/7.jpg" alt="">
                        </a>
                        <a class="instagram__item" href="#" target="_blank">
                            <img src="assets/images/instagram/8.jpg" alt="">
                        </a>
                        <a class="instagram__item" href="#" target="_blank">
                            <img src="assets/images/instagram/9.jpg" alt="">
                        </a>
                    </div>
                </div>

            </div><!-- /.footer__inner -->

            <div class="copyright">
                © 2016 MoGo free PSD template by <span>Laaqiq</span>
            </div>

        </div><!-- /.container -->
    </footer>

</div><!-- /.page -->



<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.min.js"></script>
<script src="assets/js/app.js"></script>


</body>
</html>
body {
    margin: 0;
    font-family: 'Montserrat', sans-serif;

    font-size: 15px;
    line-height: 1.6;
    color: #333;
}

*,
*:before,
*:after {
    box-sizing: border-box;
}

h1, h2, h3, h4, h5, h6 {
    margin: 0;
}

hr {
    display: block;
    width: 100%;
    height: 1px;
    margin: 40px 0;

    border: 0;
    background-color: #e5e5e5;
}


/* Page */
.page {
    overflow: hidden;
}


/* Container */
.container {
    width: 100%;
    max-width: 1230px;
    padding: 0 15px;
    margin: 0 auto;
}



/* Intro */
.intro {
    display: flex;
    flex-direction: column;
    justify-content: center;
    width: 100%;
    height: 100vh;
    min-height: 820px;
    position: relative;

    background: url("../images/intro.jpg") center no-repeat;
    -webkit-background-size: cover;
    background-size: cover;
}

.intro__inner {
    width: 100%;
    max-width: 880px;
    margin: 0 auto;

    text-align: center;
}

.intro__title {
    color: #fff;
    font-size: 150px;
    font-weight: 700;
    text-transform: uppercase;
    line-height: 1;
}

.intro__title:after {
    content: "";
    display: block;
    width: 60px;
    height: 3px;
    margin: 60px auto;

    background-color: #fff;
}

.intro__suptitle {
    margin-bottom: 20px;

    font-family: 'Kaushan Script', cursive;
    font-size: 72px;
    color: #fff;
}


/* Header */
.header {
    width: 100%;
    padding-top: 30px;

    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    z-index: 1000;
}

.header.fixed {
    padding: 10px 0;

    background-color: #eb8b8d;
    box-shadow: 0 3px 10px rgba(0, 0, 0, 0.2);

    position: fixed;
    top: 0;
    left: 0;
    right: 0;

    transform: translate3d(0, 0, 0);
}

.header.active {
    background-color: #eb8b8d;
}

.header__inner {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.header__logo {
    font-size: 30px;
    font-weight: 700;
    color: #fff;
}


/* Nav */
.nav {
    font-size: 14px;
    text-transform: uppercase;
}

.nav__link {
    display: inline-block;
    vertical-align: top;
    margin: 0 15px;
    position: relative;

    color: #fff;
    text-decoration: none;

    transition: color .1s linear;
}

.nav__link:after {
    content: "";
    display: block;
    width: 100%;
    height: 3px;

    background-color: #fce38a;
    opacity: 0;

    position: absolute;
    top: 100%;
    left: 0;
    z-index: 1;

    transition: opacity .1s linear;
}

.nav__link:hover {
    color: #fce38a;
}

.nav__link:hover:after,
.nav__link.active:after {
    opacity: 1;
}

.nav__link.active {
    color: #fce38a;
}


/* Nav toggle */
.nav-toggle {
    width: 30px;
    padding: 10px 0;
    display: none;

    font-size: 0;
    color: transparent;

    border: 0;
    background: none;
    cursor: pointer;

    position: absolute;
    top: 24px;
    right: 24px;
    z-index: 1;
}

.nav-toggle:focus {
    outline: 0;
}

.nav-toggle__item {
    display: block;
    width: 100%;
    height: 3px;

    background-color: #fff;

    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    margin: auto;

    transition: background .2s linear;
}

.nav-toggle.active .nav-toggle__item {
    background: none;
}

.nav-toggle__item:before,
.nav-toggle__item:after {
    content: "";
    width: 100%;
    height: 3px;

    background-color: #fff;

    position: absolute;
    left: 0;
    z-index: 1;

    transition: transform .2s linear;
}

.nav-toggle__item:before {
    top: -8px;
}

.nav-toggle__item:after {
    bottom: -8px;
}

.nav-toggle.active .nav-toggle__item:before {
    transform-origin: left top;
    transform: rotate(45deg) translate3d(0px, -2px, 0)
}

.nav-toggle.active .nav-toggle__item:after {
    transform-origin: left bottom;
    transform: rotate(-45deg) translate3d(0px, 3px, 0);
}


/* Button */
.btn {
    display: inline-block;
    vertical-align: top;
    padding: 8px 30px;

    border: 3px solid #fff;

    font-size: 14px;
    font-weight: 700;
    color: #fff;
    text-transform: uppercase;
    text-decoration: none;

    transition: background .1s linear, color .1s linear;
}

.btn:hover {
    background-color: #fff;
    color: #333;
}



/* Slider */
.slider {
    width: 100%;

    position: absolute;
    bottom: 0;
    left: 0;
    z-index: 1;
}

.slider__inner {
    display: flex;
    justify-content: space-between;
}

.slider__item {
    width: 23%;
    padding: 20px 0;
    position: relative;

    border-top: 3px solid #fff;
    opacity: .7;

    font-size: 18px;
    color: #fff;
    text-transform: uppercase;
}

.slider__item.active {
    opacity: 1;
}

.slider__item.active:before {
    content: "";
    display: block;
    width: 70px;
    height: 3px;

    background-color: #f38181;

    position: absolute;
    top: -3px;
    left: 0;
    z-index: 1;
}

.slider__num {
    font-size: 24px;
    font-weight: 700;
}


/* Section */
.section {
    padding: 80px 0;
}

.section--devices {
    margin-bottom: 40px;
    padding-bottom: 0;

    background: url("../images/devices-bg.jpg") center no-repeat;
    -webkit-background-size: cover;
    background-size: cover;
}

.section--gray {
    background-color: #f8f8f8;
}

.section--clients {
    background: #f5f5f5 url("../images/clients-bg.jpg") center no-repeat;
    -webkit-background-size: cover;
    background-size: cover;
}

.section--map {
    padding: 40px 0;
    background: #e6e6e6 url("../images/map-bg.jpg") center no-repeat / cover;
}

.section__header {
    width: 100%;
    max-width: 950px;
    margin: 0 auto 50px;

    text-align: center;
}

.section__suptitle {
    font-family: 'Kaushan Script', cursive;
    font-size: 24px;
    color: #333;
}

.section__title {
    font-size: 30px;
    font-weight: 700;
    color: #333;
    text-transform: uppercase;
}

.section__title:after {
    content: "";
    display: block;
    width: 60px;
    height: 3px;
    margin: 30px auto;

    background-color: #f38181;
}

.section__text {
    font-size: 15px;
    color: #999;
}



/* Card */
.card {
    margin: 80px -15px 0;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}

.card__item {
    width: 33.33333%;
    padding: 0 15px;
}

.card__inner {
    position: relative;
    background-color: #95e1d3;
}

.card__inner:hover .card__img {
    transform: translate3d(-10px, -10px, 0);
}

.card__inner:hover .card__img img {
    opacity: .1;
}

.card__inner:hover .card__text {
    opacity: 1;
}

.card__img {
    background: linear-gradient(to bottom, #f38181, #fce38a);

    transition: transform .2s linear;
}

.card__img img {
    display: block;
    max-width: 100%;
    height: auto;
    transition: opacity .1s linear;
}

.card__text {
    width: 100%;

    font-size: 18px;
    color: #fff;
    text-transform: uppercase;
    font-weight: 700;
    text-align: center;
    opacity: 0;

    position: absolute;
    top: 50%;
    left: 0;
    z-index: 2;
    transform: translate3d(0, -50%, 0);

    transition: opacity .2s linear;
}

.card__info {
    margin-top: 20px;

    text-align: center;
}

.card__name {
    margin-bottom: 5px;

    font-size: 14px;
    color: #333;
    text-transform: uppercase;
}

.card__prof {
    font-size: 15px;
    font-style: italic;
    font-weight: 300;
    color: #999;
}



/* Statistics */
.statistics {
    background-color: #95e1d3;
}

.stat {
    display: flex;
    flex-wrap: wrap;
}

.stat__item {
    flex: 1 1 0;
    padding: 70px 25px;

    border-left: 1px solid #b5eae0;

    text-align: center;
    color: #fff;
}

.stat__item:last-child {
    border-right: 1px solid #b5eae0;
}

.stat__count {
    margin-bottom: 10px;

    font-size: 72px;
    font-weight: 700;
    line-height: 1;
}

.stat__text {
    font-size: 14px;
    text-transform: uppercase;
}


/* Services */

.services {
    display: flex;
    flex-wrap: wrap;
}

.services__item {
    width: 33.33333%;
    padding: 0 35px 40px 85px;
    position: relative;
    margin-bottom: 40px;
}

.services__item--border {
    border-bottom: 1px solid #e5e5e5;
}

.services__icon {
    position: absolute;
    top: 0;
    left: 28px;
    z-index: 1;
}

.services__title {
    margin-bottom: 10px;

    font-size: 14px;
    color: #333;
    text-transform: uppercase;
}

.services__text {
    font-size: 15px;
    color: #999;
}

/* Devices */

.devices {
    width: 100%;
    max-width: 600px;
    margin: 0 auto;
    position: relative;
}

.devices__item {
    display: block;
    max-width: 100%;
    height: auto;
}

.devices__item--iphone {
    position: absolute;
    bottom: -80px;
    right: 0;
    z-index: 1;
}


/* We do */
.wedo {
    display: flex;
    flex-wrap: wrap;
    margin: 0 -15px;
}

.wedo__item {
    width: 50%;
    padding: 0 15px;
}

.wedo__img {
    display: block;
    max-width: 100%;
    height: auto;
}

/* Accordion */

.accordion__item {
    margin-bottom: 10px;
    border: 1px solid #e5e5e5;
}

.accordion__item.active .accordion__content {
    display: block;
}

.accordion__item.active .accordion__header {
    border-bottom-color: #e5e5e5;
}

.accordion__item.active .accordion__header:after {
    transform: translateY(-50%) rotate(-45deg);
    margin-top: 5px;
}

.accordion__header {
    padding: 15px 20px 15px 65px;
    position: relative;

    border-bottom: 1px solid transparent;
    cursor: pointer;
}

.accordion__header:after {
    content: "";
    display: block;
    width: 16px;
    height: 16px;

    border-top: 2px solid #ccc;
    border-right: 2px solid #ccc;

    position: absolute;
    top: 50%;
    right: 20px;
    z-index: 1;

    transform: translateY(-50%) rotate(135deg);
}

.accordion__icon {
    position: absolute;
    top: 50%;
    left: 20px;
    z-index: 1;

    transform: translateY(-50%);
}

.accordion__content {
    padding: 15px 20px;
    display: none;

    font-size: 15px;
    color: #999;
    font-style: italic;
    font-weight: 300;
}

.accordion__title {
    font-size: 14px;
    color: #333;
    text-transform: uppercase;
}



/* Reviews */
.reviews {
    position: relative;
}

.reviews .slick-slider {
    padding: 0 110px;
}

.reviews__item {
    min-height: 210px;
    padding-left: 255px;
    position: relative;
}

.reviews__photo {
    display: block;
    width: 210px;
    height: 210px;

    border: 2px solid #95e1d3;
    border-radius: 50%;

    position: absolute;
    top: 0;
    left: 0;
    z-index: 1;
}

.reviews__text {
    margin-bottom: 15px;

    font-size: 24px;
    font-style: italic;
    font-weight: 300;
    color: #999;
}

.reviews__author {
    font-family: 'Kaushan Script', cursive;
    font-size: 24px;
    color: #333;
}

.reviews__author:before {
    content: "";
    display: inline-block;
    vertical-align: middle;
    width: 60px;
    height: 3px;
    margin-right: 10px;

    background-color: #f38181;
}

.slick-arrow {
    display: block;
    font-size: 0;
    color: transparent;

    border: 0;
    background: none;
    cursor: pointer;

    position: absolute;
    top: 50%;
    z-index: 1;
    transform: translateY(-50%);
}

.slick-arrow:focus {
    outline: 0;
}

.slick-arrow:after {
    content: "";
    display: block;
    width: 16px;
    height: 16px;

    border-top: 2px solid #ccc;
    border-left: 2px solid #ccc;
}

.slick-prev {
    left: 0;
    transform: rotate(-45deg);
}

.reviews__btn--next,
.slick-next {
    right: 0;
    transform: rotate(135deg);
}


/* Social */
.social {
    display: flex;
    justify-content: center;
}

.social__item {
    width: 55px;
    height: 55px;
    padding: 12px 10px;

    background-color: #fce38a;
    border-right: 1px solid #f38181;

    font-size: 30px;
    text-decoration: none;
    color: #f38181;
    line-height: 1;

    transition: background .1s linear, color .1s linear;
}

.social__item:last-child {
    border-right: 0;
}

.social__item:hover {
    color: #fff;
    background-color: #f38181;
}


/* Logos */
.logos {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 0 -15px;
}

.logos__item {
    padding: 0 15px;
}

.logos__img {
    display: block;
    max-width: 100%;
    height: auto;
}


/* Works */
.works {
    display: flex;
}

.works__col {
    flex: 1 1 0;
}

.works__item {
    position: relative;

    background: linear-gradient(to bottom, #f38181, #fce38a);
}

.works__item:hover .works__image {
    opacity: .1;
}

.works__item:hover .works__info {
    opacity: 1;
}

.works__image {
    display: block;
    max-width: 100%;
    height: auto;

    transition: opacity .2s linear;
}

.works__info {
    width: 100%;
    padding: 0 15px;

    text-align: center;
    color: #fff;
    opacity: 0;

    position: absolute;
    top: 50%;
    left: 0;
    z-index: 1;

    transform: translate3d(0, -50%, 0);
    transition: opacity .2s linear;
}

.works__title {
    margin-bottom: 5px;

    font-size: 14px;
    text-transform: uppercase;
}

.works__text {
    font-size: 15px;
    font-weight: 300;
    font-style: italic;
}



/* Clients */
.clients {
    display: flex;
    flex-wrap: wrap;
    margin-top: 70px;
}

.clients__item {
    width: 50%;
    padding: 0 45px 0 175px;
    position: relative;
    margin-bottom: 60px;
}

.clients__photo {
    width: 110px;
    height: 110px;

    border-radius: 50%;

    position: absolute;
    top: 0;
    left: 40px;
    z-index: 1;
}

.clients__name {
    margin-bottom: 5px;

    font-size: 14px;
    color: #333;
    text-transform: uppercase;
}

.clients__prof {
    font-size: 15px;
    color: #333;
    font-style: italic;
    font-weight: 300;
}

.clients__text {
    font-size: 15px;
    color: #999;
}

.clients__text:before {
    content: "";
    display: block;
    width: 60px;
    height: 3px;
    margin: 15px 0;

    background-color: #f38181;
}


/* Blog */

.blog {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}

.blog__item {
    width: 31%;
}

.blog__header {
    position: relative;
    margin-bottom: 14px;
}

.blog__photo {
    display: block;
    max-width: 100%;
    height: auto;
}

.blog__date {
    padding: 10px 20px;

    background-color: #95e1d3;

    font-style: italic;
    font-size: 15px;
    color: #fff;
    font-weight: 300;
    text-align: center;

    position: absolute;
    bottom: 10px;
    left: -10px;
    z-index: 1;
}

.blog__date-day {
    font-size: 30px;
    line-height: 1;
    font-weight: 700;
    font-style: normal;
}

.blog__content {
    margin-bottom: 14px;
}

.blog__title {
    margin-bottom: 10px;

    font-size: 14px;
    color: #333;
    text-transform: uppercase;
}

.blog__title a {
    color: inherit;
    text-decoration: none;
}

.blog__title a:hover {
    text-decoration: underline;
}

.blog__text {
    font-size: 15px;
    color: #999;
}

.blog__footer {
    padding-top: 14px;
    border-top: 1px solid #e5e5e5;

    font-size: 15px;
    font-weight: 300;
    font-style: italic;
    color: #999;
}

.blog-stat__item {
    display: inline-block;
    vertical-align: top;
    margin-right: 10px;
}

.blog-stat__item i {
    color: #95e1d3;
}


/* Map */

.map {
    text-align: center;
}

.map__title {
    font-size: 24px;
    color: #f38181;
    font-weight: 700;
    text-transform: uppercase;
}

.map__title:after {
    content: "";
    display: block;
    width: 60px;
    height: 3px;
    margin: 15px auto 0;

    background-color: #f38181;
}

.map__title a {
    color: inherit;
    text-decoration: none;
}

.map__title a:hover {
    text-decoration: underline;
}



/* Footer */
.footer {
    padding-top: 65px;

    background-color: #f8f8f8;
}

.footer__inner {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    margin: 0 -15px;
    padding-bottom: 65px;
}

.footer__col {
    padding: 0 15px;
}

.footer__col--first {
    width: 40%;
}

.footer__col--second {
    width: 29%;
}

.footer__col--third {
    width: 22%;
}

.footer__logo {
    margin-bottom: 30px;

    font-size: 46px;
    font-weight: 700;
    color: #ccc;
}

.footer__text {
    margin-bottom: 30px;

    font-size: 15px;
    color: #999;
}

.footer__social {
    margin-bottom: 25px;
}

.footer__social-header {
    padding-bottom: 15px;

    font-size: 14px;
    color: #333;

    border-bottom: 1px solid #e5e5e5;
}

.footer__social-header b {
    font-size: 18px;
}

.footer__social-content {
    padding-top: 15px;

    font-size: 15px;
    color: #999;
    font-style: italic;
    font-weight: 300;
}

.footer__social-content a {
    display: inline-block;
    vertical-align: middle;
    margin-left: 10px;

    font-size: 18px;
    color: #95e1d3;
}

.footer__title {
    margin: 30px 0;

    font-size: 14px;
    color: #333;
    text-transform: uppercase;
}



/* Blogs */
.blogs__item {
    display: flex;
    align-items: center;
    margin-bottom: 30px;
}

.blogs__img {
    width: 120px;
    height: 80px;
}

.blogs__content {
    padding-left: 20px;
}

.blogs__title {
    display: block;
    margin-bottom: 5px;

    color: #333;
    font-size: 12px;
    line-height: 1.5;
    text-transform: uppercase;
    text-decoration: none;
}

.blogs__title:hover {
    text-decoration: underline;
}

.blogs__date {
    font-size: 13px;
    color: #999;
    font-style: italic;
    font-weight: 300;
}


/* Instagram */
.instagram {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}

.instagram__item {
    width: 33%;
    border-bottom: 1px solid #fff;
}

.instagram__item img {
    display: block;
    max-width: 100%;
    height: auto;
}


/* Subscribe */
.subscribe {
    width: 100%;
    max-width: 380px;
    display: flex;
}

.subscribe__input {
    width: 60%;
    height: 40px;
    padding: 12px;

    background: #fff;
    border: 1px solid #e7e7e7;
    border-right: 0;

    font-family: 'Montserrat', sans-serif;
    font-size: 15px;
    line-height: 1.1;
    color: #333;
    font-style: italic;
    font-weight: 300;
}

.subscribe__input::placeholder {
    color: #ccc;
}

.subscribe__input:focus {
    outline: 0;
    border-color: #95e1d3;
}

.subscribe__btn {
    width: 40%;
    height: 40px;
    padding: 12px 30px;

    background-color: #95e1d3;
    border: 0;
    cursor: pointer;

    font-family: 'Montserrat', sans-serif;
    font-size: 14px;
    line-height: 1.1;
    font-weight: 700;
    color: #fff;
    text-transform: uppercase;

    transition: background .2s linear;
}

.subscribe__btn:hover {
    background-color: #74c7b8;
}

.subscribe__btn:focus {
    outline: 0;
}


/* Copyright */
.copyright {
    padding: 20px 0;

    border-top: 1px solid #e5e5e5;

    font-size: 14px;
    color: #333;
    text-align: center;
}

.copyright span {
    color: #f38181;
}




@media (max-width: 1230px) {

    /* Intro */
    .intro__suptitle {
        font-size: 52px;
    }

    .intro__title {
        font-size: 120px;
    }

    /* Reviews */
    .reviews__text {
        font-size: 20px;
    }
}

@media (max-width: 990px) {

    /* Intro */
    .intro__suptitle {
        font-size: 32px;
    }

    .intro__title {
        font-size: 80px;
    }

    /* Stat */
    .stat {
       justify-content: center;
    }

    .stat__item {
        flex: none;
        width: 33.33333%;
        padding-top: 30px;
        padding-bottom: 30px;

        border: 0;
    }

    .stat__item:last-child {
        border-right: 0;
    }

    /* Services */
    .services__item {
        width: 50%;
        padding-bottom: 0;
    }

    .services__item--border {
        border-bottom: 0;
    }

    /* Reviews */
    .reviews .slick-slider {
        padding: 0 60px;
    }

    .reviews__photo {
        width: 150px;
        height: 150px;
    }

    .reviews__item {
        padding-left: 175px;
    }

    /* Clients */
    .clients {
        max-width: 600px;
        margin: 0 auto;
    }

    .clients__item {
        width: 100%;
        padding-right: 0;
    }

    .clients__item:last-child {
        margin-bottom: 0;
    }


    /* Footer */
    .footer__col--first {
        width: 100%;
    }

    .footer__col--second,
    .footer__col--third {
        width: 50%;
    }

    /* Instagram */
    .instagram {
        justify-content: flex-start;
    }

    .instagram__item {
        width: auto;
        border-right: 1px solid white;
    }
}

@media (max-width: 770px) {

    /* Intro */
    .intro {
        min-height: 650px;
    }


    /* Header */
    .header {
        padding: 10px 0;
    }

    /* Nav */
    .nav {
        display: none;
        width: 100%;

        position: absolute;
        top: 100%;
        left: 0;

        background-color: #eb8b8d;
    }

    .nav.active {
        display: block;
    }

    .nav__link {
        display: block;
        margin: 0;
        padding: 8px 20px;
    }

    .nav-toggle {
        display: block;
    }


    /* Section */
    .section {
        padding: 40px 0;
    }

    .section--devices {
        padding-bottom: 0;
    }


    /* Card */
    .card {
        margin-top: 50px;
        justify-content: center;
    }

    .card__item {
        width: 100%;
        max-width: 410px;
        margin-bottom: 30px;
    }

    .card__item:last-child {
        margin-bottom: 0;
    }


    /* Slider */
    .slider__text {
        display: none;
    }

    .slider__item.active:before {
        width: 50%;
    }

    /* Services */
    .services {
        justify-content: center;
    }

    .services__item {
        width: 100%;
        max-width: 400px;
        padding-left: 55px;
        padding-right: 0;
    }

    .services__icon {
        left: 0;
    }


    /* Wedo */
    .wedo__img {
        display: none;
    }

    .wedo__item {
        width: 100%;
    }

    /* Reviews */
    .reviews__photo {
        position: static;
        margin: 0 auto 20px;
    }

    .reviews__item {
        padding-left: 0;
    }

    .reviews__text {
        font-size: 16px;
    }

    .reviews__author {
        font-size: 20px;
    }

    /* Works */
    .works {
        flex-wrap: wrap;
    }

    .works__col {
        flex: none;
        width: 50%;
    }

    /* Blog */
    .blog {
        max-width: 380px;
        margin: 0 auto;
    }

    .blog__item {
        width: 100%;
        margin-bottom: 30px;
    }

    .blog__item:last-child {
        margin-bottom: 0;
    }


    /* Footer */
    .footer__col--second,
    .footer__col--third {
        width: 100%;
    }
}


@media (max-width: 575px) {

    /* Intro */
    .intro__suptitle {
        font-size: 22px;
    }

    .intro__title {
        font-size: 40px;
    }

    /* Section */
    .section__header {
        margin-bottom: 50px;
    }

    .section__suptitle {
        font-size: 20px;
    }

    .section__title {
        font-size: 24px;
    }

    .section__title:after {
        margin: 20px auto;
    }

    /* Stat */
    .stat__item {
        width: 100%;

        border-bottom: 1px solid #b5eae0;
    }

    .stat__item:last-child {
        border-bottom: 0;
    }

    .stat__count {
        font-size: 52px;
    }


    /* Devices */
    .devices {
        max-width: 320px;
    }

    .devices__item--iphone {
        width: 180px;
        bottom: -50px;
        right: -80px;
    }


    /* Reviews */
    .reviews .slick-slider {
        padding: 0;
    }

    .slick-arrow {
        top: 18%;
    }

    /* Logos */
    .logos {
        flex-wrap: wrap;
        justify-content: center;
    }

    .logos__item {
        width: 50%;
        margin-bottom: 20px;
    }

    .logos__img {
        margin: 0 auto;
    }

    /* Works */
    .works__col {
        width: 100%;
    }


    /* Clients */
    .clients__photo {
        position: static;
    }

    .clients__item {
        padding-left: 0;
        text-align: center;
    }

    .clients__text:before {
        margin: 15px auto;
    }


    /* Blogs */
    .blogs__img {
        width: 80px;
        height: 50px;
    }

    .blogs__title {
        font-size: 10px;
    }

    /* Subscribe */
    .subscribe {
        flex-wrap: wrap;
        max-width: none;
    }

    .subscribe__input {
        margin-bottom: 10px;
        border-right: 1px solid #e7e7e7;
    }

    .subscribe__input,
    .subscribe__btn {
        width: 100%;
    }

}
