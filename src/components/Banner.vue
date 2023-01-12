<template>
    <div id="main-banner">
        <h1>Make Your Burger</h1>
    </div>
</template>

<script>
export default {
    name:"Banner",

}
</script>

<style scoped>
    #main-banner{
        background-image: url('/img/burger.jpg');
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center right;
        height: 40vmax;
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }

    #main-banner h1{
        color: #fff;
        text-align: center;
        font-size: 3.1vmax;
        background-color: #222;
        padding: 1% 2%;
    }
</style>