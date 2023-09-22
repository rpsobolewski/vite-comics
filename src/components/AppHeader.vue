<script>

export default {
    name: 'AppHeader',
    components: {

    }
}
</script>

<template >
    <div class="pt-4 text-center d-flex align-items-center">

        <div class="col-4 text-center ">
            <img src="../assets/img/dc-logo.png" alt="">
        </div>
        <div class="col-7 ">
            <ul class="nav justify-content-center">
                <li class="nav-item">
                    <a class="nav-link" aria-current="page" href="#">CHARACTERS</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">COMICS</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link active" href="#">MOVIES</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link " href="#">TV</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link " href="#">GAMES</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link " href="#">COLLECTIBLES</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link " href="#">VIDEOS</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link " href="#">FANS</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link " href="#">NEWS</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link " href="#">SHOP</a>
                </li>
            </ul>
        </div>
    </div>

    <!-- /#app_header -->
</template>



<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.nav-link {
    color: $dc_dark;

}

.active {
    color: $dc_primary;
    border-bottom: 2px solid $dc_primary;
}
</style>