<template>
<nav>
<div class="logo"><img class="brand-icon" src="../assets/brand-icon.png" alt="brand-icon"/>
    <span>RealEstate</span></div>



    <div><ul>
        <li>Rent</li>
        <li>Buy</li>
        <li>Sell</li>
        <li>Manage Property</li>
        <li>Resources</li>
    </ul></div>
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
    width: 5.5em;
    height:5.5em;
}
nav{
    background:white;
    color:black;
    width:100%;
    display: flex;
    justify-content: space-around;
    align-items: center;   
    box-shadow: 0 2px 2px -2px rgba(0,0,0,.2);

}
.logo{
    display: flex;
    flex-direction: row;
    align-items: center;
}
ul{
    display:flex;
    justify-content: center;
    align-items: center;
       margin:.5em;
}
li{
    list-style-type:none;
    padding: .5em;
    margin: .3em;
    cursor:pointer;
    font-weight: 500;
     transition: all 300ms ease;
     color: rgb(82, 82, 82);
 
}
li:hover{
     padding: .5em;
    margin: .3em;

    color: #3b4193;
}
span{
    font-size:1.9em;
    font-weight: 900;
       color: #3b4193;
}

button{
      font-family: 'Poppins', sans-serif;
    border:none;
    padding:.7em 2em;
    margin-left:1em;
    box-shadow: 0 0 .1em black;
    font-weight:bold;
    border-radius: .1rem;
    cursor:pointer;
    border-radius: .5em;
    outline: none;

}
.button-div{
  /*  */
}
.login{
     transition: all 300ms ease;
      color: #3b4193;
    background:white;
    /* border: 1px solid #4F46E5; */
}
.login:hover{
       color:white;
    background: linear-gradient(to right, #4F46E5, #467ee5);
}
.logout{
    /* border: 1px solid #4F46E5; */
      color:white;
    background: linear-gradient(to right, #4F46E5, #467ee5);
      transition: all 300ms ease;
}

</style>