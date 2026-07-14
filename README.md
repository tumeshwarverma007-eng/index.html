<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Vyara Clothes</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#f8f8f8;
color:#222;
}

header{
background:#111;
color:white;
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 10%;
position:sticky;
top:0;
}

.logo{
font-size:28px;
font-weight:bold;
color:#ff9800;
}

nav a{
color:white;
text-decoration:none;
margin-left:20px;
}

.hero{
height:90vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
background:linear-gradient(rgba(0,0,0,.5),rgba(0,0,0,.5)),url("https://images.unsplash.com/photo-1523381210434-271e8be1f52b?auto=format&fit=crop&w=1500&q=80");
background-size:cover;
background-position:center;
color:white;
}

.hero h1{
font-size:55px;
}

.hero p{
margin:20px 0;
font-size:20px;
}

.btn{
background:#ff9800;
padding:15px 35px;
color:white;
text-decoration:none;
border-radius:30px;
}

section{
padding:60px 10%;
}

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:white;
padding:20px;
border-radius:10px;
box-shadow:0 5px 15px rgba(0,0,0,.1);
text-align:center;
}

.card img{
width:100%;
height:300px;
object-fit:cover;
border-radius:10px;
}

.card h3{
margin:15px 0;
}

.price{
color:#ff9800;
font-size:22px;
font-weight:bold;
}

button{
margin-top:15px;
padding:12px 25px;
background:#111;
color:white;
border:none;
cursor:pointer;
border-radius:5px;
}

footer{
background:#111;
color:white;
text-align:center;
padding:20px;
}
</style>

</head>
<body>

<header>
<div class="logo">Vyara Clothes</div>

<nav>
<a href="#">Home</a>
<a href="#">Men</a>
<a href="#">Women</a>
<a href="#">New</a>
<a href="#">Contact</a>
</nav>

</header>

<div class="hero">

<div>

<h1>Wear Your Style</h1>

<p>Premium Fashion Collection For Everyone</p>

<a href="#" class="btn">Shop Now</a>

</div>

</div>

<section>

<h2 style="text-align:center;margin-bottom:40px;">Best Sellers</h2>

<div class="products">

<div class="card">
<img src="https://images.unsplash.com/photo-1512436991641-6745cdb1723f?auto=format&fit=crop&w=600&q=80">
<h3>Classic T-Shirt</h3>
<p class="price">₹699</p>
<button>Add to Cart</button>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1541099649105-f69ad21f3246?auto=format&fit=crop&w=600&q=80">
<h3>Blue Denim Jeans</h3>
<p class="price">₹1,299</p>
<button>Add to Cart</button>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1496747611176-843222e1e57c?auto=format&fit=crop&w=600&q=80">
<h3>Women's Dress</h3>
<p class="price">₹1,499</p>
<button>Add to Cart</button>
</div>

</div>

</section>

<footer>

<h2>Vyara Clothes</h2>

<p>Style • Quality • Comfort</p>

<p>Email: info@vyaraclothes.com</p>

<p>© 2026 Vyara Clothes. All Rights Reserved.</p>

</footer>

</body>
</html>
