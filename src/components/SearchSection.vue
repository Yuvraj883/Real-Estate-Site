<template>
    <div class="container">

    <h1>Search properties to rent</h1>
    <input placeholder="Search with search bar"/>
    <div class="row">
    <div class="col border-right">
    <p class="secondary-txt">Location</p>
    <p class="primary-txt">New York, USA</p>
    </div>
      <div class="col border-right">
    <p class="secondary-txt">When</p>
    <p class="primary-txt">Select move in date</p>
    </div>
     <div class="col border-right">
    <p class="secondary-txt">Price</p>
    <p class="primary-txt">500$-700$</p>
    </div>
     <div class="col border-right">
    <p class="secondary-txt">Property Type</p>
    <p class="primary-txt">House</p>
    </div> 
    <div class="col">
    <button class="search-btn">Search</button>
    </div>
    
    </div>
    </div>
</template>
<script>
export default{
    name:'SearchSection'
}
</script>
<style scoped>
.container{
    padding-top:7em;
  background-color:#F8FAFC;
    
    
}
h1{
    color:black;
    display:inline;
    margin-left: 8rem;
}
input{
    position:fixed; 
    right:15em;
    border-radius:.2em;
    height:1.5rem;
    width:30%;
    margin-top:1em;
    border: 2px solid black;

}
.row{
    display:flex;
    margin: 2em 7em; 
    background:white;

}
.col{
    margin:.5em;
    padding:.3em;
    flex:1;
   
}
.border-right{
 border-right: 1px solid grey;  
    height:50%;
}
.primary-txt{
    font-weight:bold;
    font-size:1.2em;
    margin-top: 0;
}
.secondary-txt{
    font-size: .8em;
    color:grey;
}
.search-btn{
    color:white;
    background-color:#4F46E5;
    border:none;
    font-size:1.5em;
    padding:.5em 2em;
    margin-top:.7em;
    border-radius: .1em;
    
}
</style>
