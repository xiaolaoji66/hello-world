# hello-world
first
<div id="app">
  <p>{{totalprice}}</p>
  <p>{{num}}</p>
  <p>{{price}}</p>
  <button @click="num=0?0:num--">减少数量</button>
  <button @click="num++">增加数量</button>
  </div>
<script>
  var vm=new Vue({
  el:'#app',
  data:{
  price:20,
  num:0},
   computed:{ 
  totalprice(){
  return this.price*this.num}
  }
  })
  
  
  
  </script>
