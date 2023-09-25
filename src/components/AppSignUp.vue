<template>
    <main>

        <div class="container d-flex justify-content-between">
            <a href="#" class="button">SIGN-UP NOW!</a>
            <div class="d-flex col-3 align-items-center justify-content-between">
                <div class="follow">FOLLOW US</div>
                <img class="img" src="../assets/img/footer-facebook.png" alt="">
                <img class="img" src="../assets/img/footer-twitter.png" alt="">
                <img class="img" src="../assets/img/footer-youtube.png" alt="">
                <img class="img" src="../assets/img/footer-pinterest.png" alt="">
                <img class="img" src="../assets/img/footer-periscope.png" alt="">

            </div>
        </div>
    </main>
</template>

<script>
export default {
    name: 'AppSignUp',

};
</script>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

main {
    background-color: $dc_secondary;
    color: white;
    padding: 20px 0;
}

.button {
    text-decoration: none;
    color: white;
    border: 2px solid $dc_primary;
    padding: 10px;

}

.img {
    height: 60%;
}

.follow {
    color: $dc_primary;
    font-weight: bold;
}
</style>
