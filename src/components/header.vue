<template>
<div class="header-grid">
    <img id="logo" alt="Vue logo" src="../assets/anime-logo.jpg">
    <div></div>
    <h3>About us</h3>
    <h3>Location</h3>
    <h3>Menu</h3>
</div>
    
</template>

<script>
export default {
    name: 'page-header'
}
</script>

<style  scoped>
    .header-grid{
        display: grid;
        justify-items: center;
        grid-template-columns: repeat(5, 1fr);
        width: 100%;
        margin-bottom: 5%;
        background-color: skyblue;
        top: 0px;
    }
    #logo{
       width: 100px;
       border: solid 3px lightskyblue;
       box-shadow: 2px 3px 5px midnightblue;
    }
</style>