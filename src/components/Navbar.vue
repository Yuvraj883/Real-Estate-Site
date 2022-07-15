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
    <button class="login">LOG IN</button>
    <button class="logout">LOG Out</button>
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
    position:fixed;
    top: 0;
}
ul{
    display:flex;
    margin-top:0;
    
}
li{
    list-style-type:none;
    margin:1em;
}
span{
    display:inline;
    margin-top:1rem;
    font-size:larger;
    font-weight: 900;
}
button{
    border:none;
    margin-top:-.8em;
    padding:.2em 1em;
    margin-left:1em;
    box-shadow: 0 0 .1em black;
    font-weight:bold;
}
.login{
      color:#4F46E5;
    background:white;
}
.logout{

      color:white;
    background:#4F46E5;
}
</style>