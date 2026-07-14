<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Click-Maza</title>

<style>
body{
margin:0;
font-family:Arial,sans-serif;
background:#111;
color:white;
text-align:center;
}

header{
background:#ff3b3b;
padding:20px;
font-size:30px;
font-weight:bold;
}

.search{
margin:20px;
}

.search input{
width:80%;
padding:12px;
border:none;
border-radius:8px;
font-size:16px;
}

.container{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
padding:20px;
}

.card{
background:#222;
padding:15px;
border-radius:10px;
transition:.3s;
}

.card:hover{
transform:scale(1.05);
}

.btn{
display:inline-block;
margin-top:10px;
padding:10px 20px;
background:#ff3b3b;
color:white;
text-decoration:none;
border-radius:8px;
}

footer{
margin-top:30px;
padding:20px;
background:#000;
}
</style>
</head>

<body>

<header>🔥 Click-Maza 🔥</header>

<div class="search">
<input type="text" placeholder="Search...">
</div>

<div class="container">

<div class="card">
<h2>Sample Video 1</h2>
<p>Demo content</p>
<a class="btn" href="#">Open</a>
</div>

<div class="card">
<h2>Sample Video 2</h2>
<p>Demo content</p>
<a class="btn" href="#">Open</a>
</div>

<div class="card">
<h2>Sample Video 3</h2>
<p>Demo content</p>
<a class="btn" href="#">Open</a>
</div>

</div>

<footer>
© 2026 Click-Maza
</footer>

</body>
</html>
<section style="padding:60px 20px;text-align:center;background:#1a1a1a;color:white;">
  <h1>Welcome to Click-Maza</h1>
  <p>Latest Updates • Fast • Mobile Friendly</p>

  <a href="#latest"
     style="display:inline-block;margin-top:20px;padding:12px 25px;
     background:#ff3b3b;color:white;text-decoration:none;border-radius:8px;">
     Explore
  </a>
</section> <section id="latest" style="padding:30px;color:white;">
  <h2>Latest Updates</h2>

  <div style="background:#222;padding:15px;border-radius:10px;margin-top:15px;">
    <h3>Example Post</h3>
    <p>Description...</p>
  </div>
</section> <footer style="background:#000;color:#aaa;text-align:center;padding:20px;">
© 2026 Click-Maza
</footer>
