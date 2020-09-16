<template>
    <div class="page-footer">
        <div></div>
        <h3>Jobs</h3>
        <h3>Support</h3>
        <h3>Contact</h3>
        <div></div>
    </div>
</template>

<script>
export default {
    name : "page-footer"
}
</script>

<style  scoped>
    .page-footer{
        display: grid;
        justify-items: center;
        grid-template-columns: repeat(5 1fr);
    }

</style>