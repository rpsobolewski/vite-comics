<template>
    <main>

        <div class="container d-flex">
            <div class="left d-flex">
                <div class="col-1">
                    <div class="title">DC COMICS</div>
                    <div class="link">Characters</div>
                    <div class="link">Comics</div>
                    <div class="link">Movies</div>
                    <div class="link">TV</div>
                    <div class="link">Games</div>
                    <div class="link">Videos</div>
                    <div class="link">News</div>
                    <div class="title">SHOP</div>
                    <div class="link">Shop DC</div>
                    <div class="link">Shop DC Collectibles</div>




                </div>
                <div class="col-2">
                    <div class="title">DC</div>
                    <div class="link">Terms Of Use</div>
                    <div class="link">Privacy Policy (New)</div>
                    <div class="link">Ad Choises</div>
                    <div class="link">Advertising</div>
                    <div class="link">Jobs</div>
                    <div class="link">Subscriptions</div>
                    <div class="link">Talent Workshop</div>
                    <div class="link">CPSC Certificates</div>
                    <div class="link">Ratings</div>
                    <div class="link">Shop Help</div>
                    <div class="link">Contact Us</div>


                </div>
                <div class="col-1">
                    <div class="title">SITES</div>
                    <div class="link">DC</div>
                    <div class="link">MAD Magazine</div>
                    <div class="link">DC Kids</div>
                    <div class="link">DC Universe</div>
                    <div class="link">DC Power Visa</div>


                </div>
            </div>
            <div class="col-5 right">
                <img class="bgLogo" src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </main>
</template>

<script>
export default {
    name: 'AppFooter',

};
</script>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

main {
    background-color: $dc_secondary;
    color: white;
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;
    z-index: 0;
}

.left {
    width: 100%;
}

.title {
    font-size: large;
    font-weight: bold;
    padding: 10px 0;

}

[class^="col-"] {
    padding: 20px 0;
    margin-right: 30px;
}



.link {
    color: $dc_light;
}

.bgLogo {
    margin: -100px 0;
    height: 650px;
}
</style>
