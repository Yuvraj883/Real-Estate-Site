<template>
<div class="cards">
<Card  />
<Card  />
<Card  />
<Card  />


</div>
</template>
<script>

import Card from './Card.vue'
export default {
  name:'Cards', 
  components:{
    Card
  }

}
</script>
<style scoped>
.cards{
  margin:0em 7em;
  display:flex;
  flex-wrap:wrap;
}
</style>
