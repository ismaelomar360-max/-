<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>IsmaelOmar Brand</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#f5f5f5;
color:#333;
}

header{
background:#0f172a;
color:white;
padding:20px 50px;
display:flex;
justify-content:space-between;
align-items:center;
}

.logo{
font-size:28px;
font-weight:bold;
}

nav a{
color:white;
text-decoration:none;
margin-left:20px;
}

.hero{
height:80vh;
background:linear-gradient(rgba(0,0,0,.6),rgba(0,0,0,.6)),
url('https://images.unsplash.com/photo-1497366754035-f200968a6e72');
background-size:cover;
background-position:center;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
color:white;
}

.hero h1{
font-size:55px;
margin-bottom:15px;
}

.hero p{
font-size:20px;
margin-bottom:20px;
}

.btn{
background:#2563eb;
padding:12px 25px;
border-radius:5px;
color:white;
text-decoration:none;
}

section{
padding:80px 10%;
}

.section-title{
text-align:center;
font-size:35px;
margin-bottom:40px;
}

.about{
display:grid;
grid-template-columns:1fr 1fr;
gap:30px;
align-items:center;
}

.services{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.card{
background:white;
padding:25px;
border-radius:10px;
box-shadow:0 2px 10px rgba(0,0,0,.1);
}

.contact{
background:white;
padding:30px;
border-radius:10px;
}

input,textarea{
width:100%;
padding:12px;
margin-top:10px;
margin-bottom:15px;
border:1px solid #ddd;
border-radius:5px;
}

button{
background:#2563eb;
color:white;
border:none;
padding:12px 25px;
border-radius:5px;
cursor:pointer;
}

footer{
background:#0f172a;
color:white;
text-align:center;
padding:20px;
}
</style>

</head>
<body>

<header>
<div class="logo">IsmaelOmar</div>

<nav>
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#services">Services</a>
<a href="#contact">Contact</a>
</nav>
</header>

<section class="hero" id="home">
<div>
<h1>Welcome to IsmaelOmar Brand</h1>
<p>Professional Digital & Business Solutions</p>
<a href="#contact" class="btn">Contact Us</a>
</div>
</section>

<section id="about">
<h2 class="section-title">About Us</h2>

<div class="about">
<div>
<h3>Who We Are</h3>
<p>
We help businesses grow through modern websites,
branding, digital marketing, and technology solutions.
</p>
</div>

<div>
<img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f"
width="100%">
</div>
</div>
</section>

<section id="services">
<h2 class="section-title">Our Services</h2>

<div class="services">

<div class="card">
<h3>Website Development</h3>
<p>Modern responsive websites for businesses.</p>
</div>

<div class="card">
<h3>Brand Design</h3>
<p>Professional logos and branding packages.</p>
</div>

<div class="card">
<h3>Digital Marketing</h3>
<p>Grow your audience and online presence.</p>
</div>

<div class="card">
<h3>E-Commerce</h3>
<p>Online stores with payment integration.</p>
</div>

</div>
</section>

<section id="contact">
<h2 class="section-title">Contact Us</h2>

<div class="contact">

<form>
<input type="text" placeholder="Your Name">

<input type="email" placeholder="Your Email">

<textarea rows="5" placeholder="Your Message"></textarea>

<button type="submit">Send Message</button>
</form>

</div>
</section>

<footer>
<p>© 2026 IsmaelOmar Brand. All Rights Reserved.</p>
</footer>

</body>
</html>
