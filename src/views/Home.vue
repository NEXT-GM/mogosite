<template>
  <section class="home">
      <div class="header">
          <div class="container">
        <div class="header__inner">
            <div class="header__logo" data-scroll="#intro">MoGo</div>

            <nav class="nav" id="nav">
                <a class="nav__link" href="#" data-scroll="#about">Aboutnpm</a>
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
    </div>
    <div class="welcom">
      <welcome />    
    </div>
    <div class="about">
      <about />    
    </div>
  </section>
</template>

<script>
import Welcome from '../components/Welcome.vue'
import About from '../components/About.vue'
export default {
    components:{
    Welcome,
    About
    }
}
</script>

<style scoped>
#home{
    margin: 0;
    font-family: 'Montserrat', sans-serif;

    font-size: 15px;
    line-height: 1.6;
    color: #333;
}
.container {
    width: 100%;
    max-width: 1230px;
    padding: 0 15px;
    margin: 0 auto;
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


</style>