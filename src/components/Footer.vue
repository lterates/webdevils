<template>
    <div style="position: fixed; bottom: 0rem; width: 100%" class="py-3">
        <span style="position: fixed; left: 10rem"><i>&copy; 2021 WebDevils</i></span>
        <a href="https://www.facebook.com/webdevilsofficial/" target="_blank"><b-icon icon="facebook" style="margin-right: 10px;"></b-icon></a>
        <a href="https://www.instagram.com/webdevilsofficial/" target="_blank"><b-icon icon="instagram" style="margin-right: 10px;"></b-icon></a>
        <a href="https://twitter.com/webdevilsesmad?s=20" target="_blank"><b-icon icon="twitter" style="margin-right: 10px;"></b-icon></a>
        <span style="position: fixed; right: 10rem"><i> Contact us at webdevils@protonmail.com</i></span>
    </div>
</template>

<script>
import { BIcon } from 'bootstrap-vue'

export default ({
    components: {
            BIcon,
    },
})
</script>

<style scoped>
    div {
        font-family: 'Poppins';
        font-style: italic;
        overflow: hidden;
        color: black;
        background-color: rgba(255, 255, 255, .8);
    }

    a {
        color: black;
    }

    a:hover {
        color: #D33F49;
    }
</style>