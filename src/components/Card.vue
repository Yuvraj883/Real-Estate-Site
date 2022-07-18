<template>
<div class="card">
<img class="house-icon" src="../assets/house1.webp"/>
<section>
<span class="price"><b>$2000</b>/month</span>

<p class="title">God Yuvi </p>
<p class="address">Raj Nagar, Palam, New Delhi</p>
<div class="container">
<div>
<img src="../assets/bedIcon.png" alt="bed-icon"/>
<span>3 Beds</span>
</div>
<div>
<img src="../assets/bathtub.png" alt="bathroom-icon"/>
<span>2 Bathrooms</span>
</div>
<div>
<img src="../assets/square-meter.webp" alt="square-meter-icon"/>
<span>5x7m<sup>2</sup></span>
</div>
</div>

</section>
</div>
</template>
<script>

</script>
<style scoped>
.card{
    margin:1.2rem;
    height:auto; 
    width:30%;
    background:white;
    box-shadow:0 0 .3em;

}
.house-icon{
    height:auto; 
    width: 100%; 

}
b{
    color:#4F46E5;
    font-size:1.6em;
}
.price{
    font-size:1em;
    color:grey;
}
section{
    padding:.5em 1em;
}
.title{
    font-size:1.2em;
    font-weight:bold;
    margin-top:0.2em;
}
.address{
color:grey;
font-size: .8em;
margin-top:-1em;
font-weight:800;
}
.container{
    display:flex;
}
.container div img{
    height:1.6em;
    margin-top:0em;
}
.container div span{
    font-size: 1em;
    color:grey;
    margin-top: 1em;
}
.container div{
    padding:.2em;
    margin:.1em;

}
</style>