<template>
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
.section {
    padding: 80px 0;
}

.section--devices {
    margin-bottom: 40px;
    padding-bottom: 0;

    background: url("../assets/images/devices-bg.jpg") center no-repeat;
    -webkit-background-size: cover;
    background-size: cover;
}

.section--gray {
    background-color: #f8f8f8;
}

.section--clients {
    background: #f5f5f5 url("../assets/images/clients-bg.jpg") center no-repeat;
    -webkit-background-size: cover;
    background-size: cover;
}

.section--map {
    padding: 40px 0;
    background: #e6e6e6 url("../assets/images/map-bg.jpg") center no-repeat / cover;
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

</style>