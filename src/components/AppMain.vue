<template>
    <main>

        <div class="d-flex flex-wrap container">
            <div v-for="(comic, index) in comics" :key="index" class="col-2 p-2 ">
                <div>
                    <img :src="comic.thumb" alt="Comic Thumbnail" class="">
                    <div class="">
                        <h5 class="text-center">{{ comic.series }}</h5>

                    </div>
                </div>
            </div>
        </div>
        <div class="d-flex justify-content-center">
            <a href="#" class="button">LOAD MORE</a>
        </div>



    </main>
</template>

<script>
import comics from '../data/comics.js'


export default {
    name: 'AppMain',
    data() {
        return {
            comics
        };
    },

};
</script>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

main {
    background-color: $dc_dark;
    color: white;
}

img {
    width: 100%;
    aspect-ratio: 1;
    object-fit: contain;

}

.container {
    padding-top: 20px;
}

.button {
    color: white;
    background-color: $dc_primary;
    text-decoration: none;
    font-weight: bold;
    padding: 8px 15px;
    margin-bottom: 7px;

}
</style>
