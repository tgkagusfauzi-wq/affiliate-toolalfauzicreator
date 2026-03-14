# affiliate-toolalfauzicreator
Simple TikTok affiliate content generator for fashion products. Generate video script, hooks, and captions.
<!DOCTYPE html>
<html>
<head>
<title>Tool Affiliate TikTok</title>
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>
body{
font-family:Arial;
padding:20px;
background:#f2f2f2;
}

input{
width:100%;
padding:10px;
margin-top:10px;
}

button{
width:100%;
padding:12px;
background:black;
color:white;
border:none;
margin-top:10px;
}

.box{
background:white;
padding:15px;
margin-top:20px;
border-radius:8px;
}
</style>
</head>

<body>

<h2>Tool Ide Video Affiliate</h2>

<label>Nama Produk</label>
<input id="produk" placeholder="contoh: Hoodie Oversize">

<button onclick="buat()">Buat Ide Video</button>

<div class="box" id="hasil"></div>

<script>

function buat(){

var produk = document.getElementById("produk").value;

var hasil = "

SCRIPT VIDEO:
Produk "+produk+" ini lagi viral di TikTok.
Bahannya nyaman dipakai sehari hari.
Modelnya stylish dan cocok untuk berbagai gaya.
Cek sekarang di keranjang kuning.

IDE VIDEO:
1. zoom pelan produk
2. fokus detail bahan
3. before after outfit
4. teks lagi viral
5. close up bahan

CAPTION:
"+produk+" lagi viral 🔥
nyaman dipakai sehari hari
link di keranjang kuning

#tiktokshop #fashionviral
";

document.getElementById("hasil").innerText = hasil;

}

</script>

</body>
</html>
