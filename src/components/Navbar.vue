<template>
<nav>
<img class="brand-icon" src="../assets/brand-icon.jpeg" alt="brand-icon"/>
    <span>House</span>



    <ul>
        <li>Rent</li>
        <li>Buy</li>
        <li>Sell</li>
        <li>Manage Property</li>
        <li>Resources</li>
    </ul>
    <div class="button-div">
    <button class="login">Log In</button>
    <button class="logout">Sign Up</button>
    </div>
    </nav>
</template>
<script>
export default{
name:'Navbar'
}
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Splash&display=swap');
.brand-icon{
    height:3.5em;

}
nav{
    background:white;
    color:black;
    display:flex;
    position:fixed;
    width:100%;
    position:fixed;
    top: 0;
    padding:1em 2.5em;
    box-shadow:0 0 2px black;
    
}
ul{
    display:flex;
    margin-top:0;
    
}
li{
    list-style-type:none;
    margin:1em;
    cursor:pointer;
}
span{
    display:inline;
    margin-top:0rem;
    font-size:2em;
    font-weight: 900;
    font-family:'Splash',cursive;
}
button{
    border:none;
    margin-top:.8em;
    padding:.5em 2em;
    margin-left:1em;
    box-shadow: 0 0 .1em black;
    font-weight:bold;
    border-radius: .1rem;
    cursor:pointer;
}
.button-div{
       right:9em;
    position:absolute;
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