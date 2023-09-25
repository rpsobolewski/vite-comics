<template>
    <main>
        <div class="container d-flex justify-content-between">
            <div class="" v-for="item in navItem" :key="item.text">
                <img :src="item.src" alt="">
                <span>{{ item.text }}</span>
            </div>

        </div>
    </main>
</template>

<script>
export default {
    name: 'AppBlueNav',
    data() {
        return {
            navItem: [
                {
                    src: 'src/assets/img/buy-comics-digital-comics.png',
                    text: 'DIGITAL COMICS',
                },
                {
                    src: 'src/assets/img/buy-comics-merchandise.png',
                    text: 'DC MERCHANDISE',
                },
                {
                    src: 'src/assets/img/buy-comics-subscriptions.png',
                    text: 'SUBSCRIPTION',
                },
                {
                    src: 'src/assets/img/buy-comics-shop-locator.png',
                    text: 'COMIC SHOP LOCATOR',
                },
                {
                    src: 'src/assets/img/buy-dc-power-visa.svg',
                    text: 'DC POWER VISA',
                },
            ]
        };
    },

};

</script>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

main {
    background-color: $dc_primary;
    z-index: 1;
}

img {
    height: 60px;
    margin: 40px 15px;
}

span {
    color: white;
}
</style>
