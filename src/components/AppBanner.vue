<template>
    <main>
        <div class="container">
            <a href="#" class="button">CURRENT SERIES</a>
        </div>
    </main>
</template>

<script>


export default {
    name: 'AppBanner',

};
</script>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

main {
    background-image: url(../assets/img/jumbotron.jpg);


}

.container {
    position: relative;
    height: 500px;
}

.button {
    color: white;
    background-color: $dc_primary;
    text-decoration: none;
    font-weight: bold;
    padding: 10px;
    position: absolute;
    bottom: -20px;
    left: 47px;
}
</style>
