<template>
    <div class="page" style="text-align:center">
        <h1 :class="['wow','animate__animated',list[i]] " data-wow-offset="100" v-for="i in 43" :key="i"></h1>
    </div>
</template>

<script>
export default {
    data() {
        return {
            list: [
                "animate__bounce",
                "animate__flash",
                "animate__pulse",
                "animate__rubberBand",
                "animate__shakeX",
                "animate__shakeY",
                "animate__headShake",
                "animate__swing",
                "animate__tada",
                "animate__wobble",
                "animate__jello",
                "animate__heartBeat",
                "animate__backInDown",
                "animate__backInLeft",
                "animate__backInRight",
                "animate__backInUp",
                "animate__backOutDown",
                "animate__backOutLeft",
                "animate__backOutRight",
                "animate__backOutUp",
                "animate__bounceIn",
                "animate__bounceInDown",
                "animate__bounceInLeft",
                "animate__bounceInRight",
                "animate__bounceInUp",
                "animate__bounceOut",
                "animate__bounceOutDown",
                "animate__bounceOutLeft",
                "animate__bounceOutRight",
                "animate__bounceOutUp",
                "animate__fadeIn",
                "animate__fadeInDown",
                "animate__fadeInDownBig",
                "animate__fadeInLeft",
                "animate__fadeInLeftBig",
                "animate__fadeInRight",
                "animate__fadeInRightBig",
                "animate__fadeInUp",
                "animate__fadeInUpBig",
                "animate__fadeInTopLeft",
                "animate__fadeInTopRight",
                "animate__fadeInBottomLeft",
                "animate__fadeInBottomRight",
            ],
        };
    },
    created() {
        console.log(this.list.length);
    },
};
</script>
<style lang="scss" scoped>
h1 {
    // style="visibility: visible; animation-duration: 2s; animation-delay: 300ms; animation-iteration-count: infinite; animation-name: pulse;"
    margin: auto;
    background: pink;
    width: 200px;
    height: 200px;
    margin-bottom: 20px;
    // animation-iteration-count: 3;
    // animation-delay: 300ms;
    animation-duration: 1s;
}
</style>