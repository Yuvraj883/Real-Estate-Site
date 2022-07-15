<template>
<nav>
    <span>BrandName</span>

    <ul>
        <li>Rent</li>
        <li>Buy</li>
        <li>Sell</li>
        <li>Manage Property</li>
        <li>Resources</li>
    </ul>
    </nav>
</template>
<script>
export default{
name:'Navbar'
}
</script>
<style scoped>
nav{
    background:white;
    color:black;
    display:flex;
    position:fixed;
    width:100%;
}
ul{
    display:flex;
}
</style>