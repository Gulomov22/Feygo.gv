<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Feygo Sport Shop</title>

<style>
body{
margin:0;
font-family:Arial;
background:#0b0b0b;
color:white;
}

header{
background:linear-gradient(90deg, #ff0000, #990000);
padding:20px;
text-align:center;
}

header h1{
margin:0;
font-size:28px;
}

.hero{
text-align:center;
padding:35px 20px;
}

.hero p{
color:#bbb;
}

.btn{
background:red;
color:white;
padding:10px 15px;
border-radius:8px;
border:none;
cursor:pointer;
text-decoration:none;
display:inline-block;
margin-top:10px;
}

.section{
padding:25px;
text-align:center;
}

.products{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:15px;
}

.product{
background:#1a1a1a;
padding:15px;
border-radius:12px;
width:240px;
transition:0.3s;
}

.product:hover{
transform:scale(1.05);
}

.product img{
width:100%;
border-radius:10px;
height:150px;
object-fit:cover;
}

.cart{
background:#111;
margin:20px;
padding:15px;
border-radius:10px;
}

input{
padding:10px;
width:80%;
margin:5px;
border-radius:6px;
border:none;
}

footer{
text-align:center;
padding:20px;
color:#777;
background:#111;
}
</style>
</head>

<body>

<header>
<h1>⚽ FEYGO SPORT SHOP</h1>
</header>

<div class="hero">
<h2>Professional Football Store</h2>
<p>Jerseys • Boots • Training Kits • Accessories</p>

<a class="btn" href="https://t.me/feygogv">📦 Order on Telegram</a>
</div>

<div class="section">
<h2>🔥 Featured Products</h2>

<div class="products">

<div class="product">
<img src="https://images.unsplash.com/photo-1521412644187-c49fa049e84d">
<h3>Football Jersey</h3>
<p>$25</p>
<button class="btn" onclick="add('Football Jersey - $25')">Add to Cart</button>
</div>

<div class="product">
<img src="https://images.unsplash.com/photo-1517927033932-b3d18e61fb3a">
<h3>Football Boots</h3>
<p>$60</p>
<button class="btn" onclick="add('Football Boots - $60')">Add to Cart</button>
</div>

<div class="product">
<img src="https://images.unsplash.com/photo-1508098682722-e99c643e7f52">
<h3>Training Kit</h3>
<p>$40</p>
<button class="btn" onclick="add('Training Kit - $40')">Add to Cart</button>
</div>

</div>
</div>

<div class="section cart">
<h2>🛒 Your Cart</h2>

<ul id="cart"></ul>

<input type="text" id="name" placeholder="Your Name">
<input type="text" id="phone" placeholder="Phone Number">

<br>

<button class="btn" onclick="order()">Send Order to Telegram</button>
</div>

<footer>
© 2026 Feygo Sport Shop • All rights reserved
</footer>

<script>
let cart = [];

function add(item){
cart.push(item);
render();
}

function render(){
let list = document.getElementById("cart");
list.innerHTML = "";

cart.forEach(i=>{
let li = document.createElement("li");
li.textContent = i;
list.appendChild(li);
});
}

function order(){
let name = document.getElementById("name").value;
let phone = document.getElementById("phone").value;

let message =
"⚽ New Feygo Order%0A%0A" +
"👤 Name: " + name + "%0A" +
"📞 Phone: " + phone + "%0A%0A" +
"🛒 Items:%0A" + cart.join("%0A");

window.open("https://t.me/feygogv?text=" + message, "_blank");
}
</script>

</body>
</html>
