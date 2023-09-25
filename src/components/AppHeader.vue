<script>

export default {
    name: 'AppHeader',
    data() {
        return {
            navItems: ['CHARACTERS', 'COMICS', 'MOVIES', 'TV', 'GAMES', 'COLLECTIBLES', 'VIDEOS', 'FANS', 'NEWS', 'SHOP'],
            activeIndex: null,
        };
    },
    methods: {
        setActive(index) {
            this.activeIndex = index;
        },
        resetActive() {
            this.activeIndex = null;
        },
        isActive(index) {
            return this.activeIndex === index;
        },
    },
};

</script>

<template >
    <div class="container">
        <div class="pt-4 text-center d-flex align-items-center">

            <div class="col-3 text-start ">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>
            <div class="col-9 ">
                <ul class="nav justify-content-center">
                    <li class="nav-item" v-for="(item, index) in navItems" :key="index" @mouseenter="setActive(index)"
                        @mouseleave="resetActive">
                        <a class="nav-link" :class="{ active: isActive(index) }" aria-current="page" href="#">{{ item }}</a>
                    </li>


                </ul>
            </div>
        </div>
    </div>
    <!-- /#app_header -->
</template>



<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.nav-link {
    color: $dc_dark;
    padding-bottom: 69px;

}

img {
    margin-bottom: 8px;
}

.active {
    color: $dc_primary;
    border-bottom: 6px solid $dc_primary;
    margin-bottom: -6px;
}
</style>