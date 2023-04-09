<template>
  <nav>
    <h1>Cart</h1>
    <router-link style="text-decoration: none; " to="/">Home</router-link> |
    <router-link style="text-decoration: none; " to="/products">Cart</router-link>
  </nav>
  <div class="producs-list">
    <div id="main">
      <div id="check">
        <div class="bill">
          <ul><b>Product</b>
          <li><img src="D:\xampp\htdocs\libary\libary\src\assets\tho.jpg">the story of Success</li>
          <li><img src="D:\xampp\htdocs\libary\libary\src\assets\tho.jpg">My dearest darkest</li>
          <li>subtotal</li></ul>
        </div>
        <div class="bill">
          <ul><b>Quantity</b>
            <li>
            <div class="buttons_added">
  <input class="minus is-form" type="button" value="-">
  <input aria-label="quantity" class="input-qty" max="2" min="1" name="" type="number" value="">
  <input class="plus is-form" type="button" value="+">
</div></li>
<li>
            <div class="buttons_added">
  <input class="minus is-form" type="button" value="-">
  <input aria-label="quantity" class="input-qty" max="2" min="1" name="" type="number" value="">
  <input class="plus is-form" type="button" value="+">
</div></li>
          </ul>
        </div>
          <div class="bill">
          <ul><b>Subtotal</b>
            <li>1</li>
            <li>1</li>
            <li>2</li>
          </ul></div>
      </div>
      <div id="check-bill">
        <h3>CART TOTALS</h3>
        <div class="bill2">
          <ul><b>Borrowed date</b>
          <li><b>Pay day</b></li>
          <li><b>subtotal</b></li></ul>
        </div>
          <div class="bill2"><ul>
            <li>1</li>
            <li>1</li>
            <li>2</li>
          </ul></div>
          <div id="checkout">
          <router-link style="text-decoration: none;" to="products/create">Proceed to checkout</router-link></div>
          <!-- <input type="submit" value="Proceed to checkout" class="submit"/> -->
          </div>
      </div>
  </div>
</template>
<style>
h1{
  font-family:  'Times New Roman', Times, serif;
  font-size: 30px;
}
h3{
  font-family: 'Times New Roman', Times, serif;
}
nav {
  text-align: center;
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
li {
  list-style: none;
  text-align:left;
}
#main{
  display: flex;
}
.producs-list{
  padding-top: 10px;
  padding-left: 20px;
}
#check{
  width: 48%;
  border:1px solid black;
  border-radius: 10px;
}
.bill {
  float: left;
  font-size: 20px;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  width: 33%;
}
.bill2{
  float: left;
  font-size: 20px;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  width: 50%;
}

#ship{
  float: inline-end;
  width: 100%;
  border-style: solid;
  border: 1ch;
}
span.ingredient {
    color: #f00;
}
.test{
  width: 300px;
  height: 30px;
border-radius: 5px;
}
.submit{
  background-color: white;
  width: 100%;
  height: 30px;
  border-radius: 5px;
}
.buttons_added {
    opacity:1;
    display:inline-block;
    display:-ms-inline-flexbox;
    display:inline-flex;
    white-space:nowrap;
    vertical-align:top;
}
.is-form {
    overflow:hidden;
    position:relative;
    background-color:#f9f9f9;
    height:20px;
    width:20px;
    padding:0;
    text-shadow:1px 1px 1px #fff;
    border:1px solid #ddd;
}
.is-form:focus,.input-text:focus {
    outline:none;
}
.is-form.minus {
    border-radius:4px 0 0 4px;
}
.is-form.plus {
    border-radius:0 4px 4px 0;
}
.input-qty {
    background-color:#fff;
    height: 20px;
    width: 30px;
    text-align:center;
    font-size:1rem;
    display:inline-block;
    vertical-align:top;
    margin:0;
    border-top:1px solid #ddd;
    border-bottom:1px solid #ddd;
    border-left:0;
    border-right:0;
    padding:0;
}
.input-qty::-webkit-outer-spin-button,.input-qty::-webkit-inner-spin-button {
    -webkit-appearance:none;
    margin:0;
}
#check-bill{
  width: 48%;
  margin-left: 10px;
  border: 1px solid black;
  border-radius: 10px;
  padding-left: 5px;
}
#check-bill a{
  text-align: center;
  background-color: white;
  width: 100%;
  height: 30px;
  border-radius: 5px;
}
#checkout {
text-align: center;
border: 1px solid black;
border-radius: 5px;
margin-top: 40%;
margin-bottom: 10px;
height: 20px;
}
</style>

