<template>
  <div class="welcom">
      <div class="intro" id="intro">
        <div class="container">
            <div class="intro__inner">
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

    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.container {
    width: 100%;
    max-width: 1230px;
    padding: 0 15px;
    margin: 0 auto;
}
.intro {
    display: flex;
    flex-direction: column;
    justify-content: center;
    width: 100%;
    height: 100vh;
    min-height: 820px;
    position: relative;

    background: url("../assets/images/intro.jpg") center no-repeat;
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
</style>