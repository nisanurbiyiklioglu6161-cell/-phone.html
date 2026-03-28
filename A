<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<title>Apple iPhone 17 Pro Max</title>

<style>
body{
margin:0;
font-family:-apple-system,Arial;
background:black;
color:white;
text-align:center;
}

/* Üst Menü */
.nav{
background:#111;
padding:15px;
display:flex;
justify-content:center;
gap:25px;
font-size:14px;
color:#ccc;
}

.nav span:hover{
color:white;
cursor:pointer;
}

/* Giriş ekranı */
#login{
margin-top:80px;
}

input{
padding:10px;
font-size:16px;
background:black;
color:#0f0;
border:1px solid #0f0;
}

button{
padding:10px 20px;
background:#0f0;
border:none;
cursor:pointer;
}

/* Ana içerik */
.container{
display:none;
padding-top:60px;
}

h1{
font-size:50px;
margin-bottom:10px;
}

.subtitle{
color:#aaa;
}

/* iPhone görsel */
img{
width:280px;
margin-top:30px;
border-radius:25px;
box-shadow:0 10px 40px rgba(255,255,255,0.2);
}

/* Fiyat */
.price{
font-size:40px;
margin-top:20px;
color:#00ffcc;
}

.small{
font-size:12px;
color:gray;
margin-top:10px;
}
</style>
</head>

<body>

<!-- Üst Menü -->
<div class="nav">
<span>Store</span>
<span>Mac</span>
<span>iPhone</span>
<span>iPad</span>
<span>Watch</span>
<span>AirPods</span>
</div>

<!-- Giriş -->
<div id="login">
<h2>Secure Access</h2>
<input id="bin" placeholder="01010111">
<button onclick="giris()">Enter</button>
</div>

<!-- Site -->
<div class="container" id="site">
<h1>iPhone 17 Pro Max</h1>
<p class="subtitle">Titanium. Powerful. Next level.</p>

<img src="https://store.storeimages.cdn-apple.com/4982/as-images.apple.com/is/iphone-15-pro-max-blue-titanium-select-2023?wid=940&hei=1112&fmt=png-alpha"
onerror="this.src='https://images.unsplash.com/photo-1598327105666-5b89351aff97?q=80&w=800&auto=format&fit=crop'">

<div class="price" id="price">119.999 TL</div>
<div class="small">*Made in Turkey</div>
</div>

<script>
function giris(){
if(document.getElementById("bin").value==="01010111"){
document.getElementById("login").innerHTML="Connecting...";

setTimeout(()=>{
document.getElementById("login").style.display="none";
document.getElementById("site").style.display="block";

setTimeout(()=>{
document.getElementById("price").innerText="200 TL";
},2000);

},1500);

}else{
alert("Wrong code!");
}
}
</script>

</body>
</html>
