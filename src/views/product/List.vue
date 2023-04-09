<template>
  <nav>
    <h1>Checkout</h1>
    <router-link style="text-decoration: none" to="/">Home</router-link> |
    <router-link style="text-decoration: none" to="/products/create">Checkout</router-link
    >
  </nav>
  <div class="producs-list">
    <div id="main">
      <div id="check-bill">
        <h2>BILLING DETAILS</h2>
        <ul>
          <li>
            first name<span class="ingredient">*</span><br />
            <input type="text" name="firstname" class="test" />
          </li>
          <li>
            last name<span class="ingredient">*</span><br />
            <input type="text" name="lastname" class="test" />
          </li>
          <li>
            your name<span class="ingredient">*</span><br />
            <input type="text" name="yourname" class="test" />
          </li>
          <li>
            street address<span class="ingredient">*</span><br />
            <input type="text" name="street" class="test"  />
          </li>
          <li>
            phone<span class="ingredient">*</span><br />
            <input type="text" name="phone" class="test"  />
          </li>
          <li>
            email<span class="ingredient">*</span><br />
            <input type="text" name="email" class="test" />
          </li>
        </ul>
      </div>
      <div id="check">
        <div class="bill">
          <ul><b>Product</b>
          <li>the story of Success</li>
          <li>My dearest darkest</li>
          <li>subtotal</li></ul>
        </div>
          <div class="bill">
          <ul><b>Subtotal</b>
            <li>1</li>
            <li>1</li>
            <li>2</li>
          </ul></div>
          <input type="submit" value="Place order" class="submit"/>
          <!-- <router-link to="order" style="text-decoration: none"> Place order</router-link> -->
      </div>
      </div>
      <div id="ship">
        <h3>SHIP TO A DIFEREENT ADDRESS?</h3>
        <ul>
          <li>
            Order notes(optional)<br />
            <input type="text" name="notes" class="test"  />
          </li>
        </ul>
      </div>
  </div>
</template>
<style>
h1{
  font-family:  'Times New Roman', Times, serif;
  font-size: 30px;
}
h2{
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
  padding: 10px;
}
#check-bill{
  width: 50%;
}
#check{
  width: 50%;
  border:1px solid black;
  border-radius: 10px;
}
.bill {
  float: left;
  font-size: 15px;

}
.bill{
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
</style>
