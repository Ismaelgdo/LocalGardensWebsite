<template>
    <v-container fluid fill-height class="home-hero">
        <!-- This is what controls the text -->
        <v-layout justify-center align-center column pa-5>
            <div class="display-4 font-weight-black white--text text-xs-center">FIND A LOCAL</div>
            <div class="display-4 font-weight-black white--text text-xs-center mb-3">COMMUNITY GARDEN</div>
                <div class="display-4 font-weight-black white--text text-xs-center mb-3">OR START YOUR OWN</div>
            <v-btn fab class="mt-5 brown darken-4">
            <v-icon large color="white">expand_more</v-icon>
            </v-btn>
        </v-layout>
    </v-container>
</template>

<script>
export default {
    name: 'HomeHero'
};
</script>

<style scoped>
.hero-image {
    background: url("../assests/garden.jpg");
    background-size: cover;
    width: 100%;
    height: 100%;
}
</style>