<template>
    <v-app>
        <router-view></router-view>
    </v-app>
</template>

<script>
export default {
    name: 'App',

    data: () => ({
        //
    }),
};
</script>

<style lang="scss">
@import url(https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.8.2/css/all.min.css);

// @import url('https://fonts.googleapis.com/css?family=poppins:300,400,500,600,700,800,900&display=swap');
@font-face {
    font-family: 'NEXON Lv1 Gothic OTF Light';
    src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_20-04@2.1/NEXON Lv1 Gothic OTF Light.woff')
        format('woff');
    font-weight: normal;
    font-style: normal;
}
@font-face {
    font-family: 'NEXONFootballGothicLA1';
    src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_20-04@2.1/NEXONFootballGothicLA1.woff')
        format('woff');
    font-weight: normal;
    font-style: normal;
}
html {
    scroll-behavior: smooth;
}
.v-application ul,
.v-application ol {
    padding: 0px !important;
}
a,
ul,
li {
    text-decoration: none;
    list-style: none;
}
* {
    margin: 0;
    padding: 0;
    // font-family: 'NEXON Lv1 Gothic Light', sans-serif;
    font-family: 'NEXONFootballGothicLA1';
}
</style>
