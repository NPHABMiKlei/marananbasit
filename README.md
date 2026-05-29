<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Judy Ann Maranan | Coquette Portfolio</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">
<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
scroll-behavior:smooth;
}
body{
font-family:'Poppins',sans-serif;
background:linear-gradient(135deg,#ffd6ec,#dff4ff);
color:#444;
overflow-x:hidden;
}
/* FLOATING HEARTS */
.hearts{
position:fixed;
width:100%;
height:100%;
top:0;
left:0;
pointer-events:none;
z-index:-1;
overflow:hidden;
}
.hearts span{
position:absolute;
bottom:-100px;
font-size:20px;
animation:float 15s linear infinite;
opacity:.7;
}
@keyframes float{
0%{
transform:translateY(0) rotate(0);
opacity:0;
}
20%{
opacity:1;
}
100%{
transform:translateY(-120vh) rotate(360deg);
opacity:0;
}
}
/* NAVIGATION */
nav{
position:fixed;
top:0;
left:0;
width:100%;
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 8%;
background:rgba(255,255,255,.7);
backdrop-filter:blur(15px);
z-index:1000;
}
.logo{
font-family:'Playfair Display',serif;
font-size:28px;
font-weight:700;
color:#ff69b4;
}
nav ul{
display:flex;
gap:25px;
list-style:none;
}
nav a{
text-decoration:none;
color:#555;
font-weight:500;
transition:.3s;
}
nav a:hover{
color:#ff69b4;
}
/* HERO */
.hero{
min-height:100vh;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
padding:120px 20px 50px;
text-align:center;
}
.profile-frame{
width:320px;
height:420px;
padding:10px;
background:linear-gradient(135deg,#ff9fd5,#9fdcff);
clip-path:polygon(20% 0%,100% 0%,80% 100%,0% 100%);
box-shadow:0 20px 50px rgba(255,105,180,.3);
animation:glow 3s infinite alternate;
}
@keyframes glow{
from{
box-shadow:0 0 20px pink;
}
to{
box-shadow:0 0 40px skyblue;
}
}
.profile-frame img{
width:100%;
height:100%;
object-fit:cover;
}
.hero h1{
font-size:55px;
margin-top:30px;
font-family:'Playfair Display',serif;
color:#ff5ea8;
}
.hero p{
max-width:700px;
margin-top:15px;
line-height:1.8;
}
/* SECTIONS */
section{
width:90%;
margin:auto;
margin-bottom:40px;
padding:40px;
background:rgba(255,255,255,.55);
backdrop-filter:blur(18px);
border-radius:30px;
box-shadow:0 10px 30px rgba(0,0,0,.08);
}
section h2{
font-size:35px;
margin-bottom:25px;
color:#ff69b4;
font-family:'Playfair Display',serif;
}
section p{
line-height:1.9;
margin-bottom:15px;
}
/* IMAGE */
.single-image{
width:100%;
max-width:500px;
display:block;
margin:20px auto;
border-radius:25px;
}
/* EDUCATION */
.edu{
margin-bottom:25px;
padding:20px;
background:white;
border-radius:20px;
}
/* INTERESTS */
.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}
.card{
background:white;
padding:15px;
border-radius:25px;
transition:.4s;
}
.card:hover{
transform:translateY(-10px);
}
.card img{
width:100%;
height:250px;
object-fit:cover;
border-radius:20px;
}
.card h3{
margin-top:15px;
color:#ff69b4;
}
/* GALLERY */
.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
}
.gallery img{
width:100%;
height:280px;
object-fit:cover;
border-radius:20px;
transition:.4s;
}
.gallery img:hover{
transform:scale(1.05);
}
/* VIDEO */
video{
width:100%;
border-radius:25px;
}
/* QUOTE */
blockquote{
padding:20px;
background:white;
border-left:6px solid pink;
border-radius:15px;
font-style:italic;
}
/* CONTACT */
.socials a{
display:inline-block;
margin:10px;
padding:12px 25px;
background:linear-gradient(135deg,pink,skyblue);
color:white;
border-radius:50px;
text-decoration:none;
}
/* FOOTER */
footer{
text-align:center;
padding:40px;
font-size:18px;
}
/* MOBILE */
@media(max-width:768px){
.hero h1{
font-size:40px;
}
.profile-frame{
width:250px;
height:330px;
}
nav{
flex-direction:column;
gap:10px;
}
nav ul{
flex-wrap:wrap;
justify-content:center;
}
section{
padding:25px;
}
}
</style>
</head>
<body>
<div class="hearts"></div>
<nav>
<div class="logo">Judy Ann ♡</div>
<ul>
<li><a href="#about">About</a></li>
<li><a href="#education">Education</a></li>
<li><a href="#family">Family</a></li>
<li><a href="#interests">Interests</a></li>
<li><a href="#gallery">Gallery</a></li>
<li><a href="#advocacy">Advocacy</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>
<div class="hero">
<div class="profile-frame">
<img src="IMG_7940.jpeg">
</div>
<h1>Judy Ann B. Maranan</h1>
<p>
Dreamer • Fur Mom • Coffee Lover
</p>
</div>
<section id="about">
<h2>🌷 About Me</h2>
<p><b>Full Name:</b> Judy Ann B. Maranan</p>
<p><b>Age:</b> 28 Years Old</p>
<p><b>Birthday:</b> April 09, 1998</p>
<p><b>Favorite Color:</b> Pink</p>
<p><b>Address:</b> Cainta, Rizal</p>
<p>
Hi! I am Judy Ann Maranan. I am a college student who loves learning new things, spending time with family, friends, and especially with my dogs while exploring creative ideas.
</p>
<p>
My dream is to become successful and inspire others through hard work and kindness.
</p>
</section>
<section id="education">
<h2>🎓 Educational Background</h2>
<div class="edu">
<h3>Grade School</h3>
<p>
I studied at Urdaneta Elementary School where I learned the importance of education, discipline, and friendship.
</p>
</div>
<div class="edu">
<h3>High School</h3>
<p>
I studied at Bendita National High School where I discovered my strengths and built my confidence.
</p>
</div>
<div class="edu">
<h3>College</h3>
<p>
I studied BS Accountancy at AMA University Quezon City. I am currently studying Customs Administration at LPU Manila.
</p>
</div>
</section>
<section>
<h2>🏆 Achievements</h2>
<img src="IMG_9215.jpg" class="single-image">
<p>Passed the NCIII Bookkeeping in 2018</p>
<img src="IMG_9216.jpg" class="single-image">
<p>Passed the IC3 Assessment</p>
</section>
<section id="family">
<h2>👨‍👩‍👧‍👦 Family Background</h2>
<img src="IMG_2387.jpg" class="single-image">
<p>
My father is my role model and my source of strength. His hard work, sacrifices, and unwavering support inspire me to face life's challenges with courage and determination.
</p>
<p>
My mother is the heart of our family. Her endless love, care, and encouragement make every day brighter.
</p>
<img src="IMG_8592.jpg" class="single-image">
<p>
My siblings are my lifelong friends and partners in every adventure.
</p>
<img src="Photoroom_20250525_165207.jpg" class="single-image">
<p>
My fur babies hold a special place in my heart. They are not just pets — they are family. ❤️🐶
</p>
</section>
<section id="interests">
<h2>💖 Interests & Hobbies</h2>
<div class="grid">
<div class="card">
<img src="IMG_9335.jpg">
<h3>Snoopy Things 🐶</h3>
<p>I enjoy collecting Snoopy-themed items because they bring comfort and happiness.</p>
</div>
<div class="card">
<img src="1000002044.jpg">
<h3>Baking 🧁</h3>
<p>Baking allows me to express creativity and share happiness through desserts.</p>
</div>
<div class="card">
<img src="IMG_9233.jpg">
<h3>Business 💼</h3>
<p>Learning entrepreneurship inspires me to turn ideas into opportunities.</p>
</div>
<div class="card">
<img src="Untitled design.jpg">
<h3>PBA Basketball 🏀</h3>
<p>I enjoy watching exciting basketball games and supporting my favorite teams.</p>
</div>
<div class="card">
<img src="realme C25s.jpg">
<h3>Playing with My Dogs 🐾</h3>
<p>My dogs bring joy, comfort, and unconditional love into my life.</p>
</div>
<div class="card">
<img src="att.J-gQVq_0TjjoQaJOyvXdOrVq7hQpNEWbof-wQNSkZkQ.jpeg">
<h3>Friends 🤍</h3>
<p>My friends make life more meaningful through laughter and support.</p>
</div>
</div>
</section>
<section id="gallery">
<h2>📸 Gallery</h2>
<div class="gallery">
<img src="IMG_0180.jpg">
<img src="IMG_9438.jpg">
<img src="IMG_8109.jpg">
<img src="IMG_7768.jpg">
<img src="IMG_8220.jpg">
<img src="IMG_5061.jpg">
</div>
</section>
<section>
<h2>🎥 My Video</h2>
<video controls>
<source src="copy_C29606BD-9360-4C6D-BDE7-033D2994FC18.mp4" type="video/mp4">
</video>
</section>
<section id="advocacy">
<h2>💚 Mental Health Awareness</h2>
<p>
Mental health awareness is an advocacy that is close to my heart. I believe everyone deserves to be heard, understood, and supported.
</p>
<blockquote>
"When the time is right, I, the Lord, will make it happen." — Isaiah 60:22
</blockquote>
</section>
<section id="contact">
<h2>📩 Contact Me</h2>
<p>Email: jmaranan0409@yahoo.com</p>
<div class="socials">
<a href="https://www.facebook.com/share/1KPvi4ufrd/?mibextid=wwXIfr" target="_blank">
Facebook
</a>
<a href="https://www.instagram.com/nphabmi_09" target="_blank">
Instagram
</a>
</div>
</section>
<footer>
Made with ♡ by Judy Ann Maranan 🌷🩷🩵
</footer>
<script>
const hearts=document.querySelector('.hearts');
const icons=[
'♡',
'🩷',
'💙',
'🎀',
'🌸',
'🤍'
];
for(let i=0;i<50;i++){
let span=document.createElement('span');
span.innerHTML=
icons[Math.floor(Math.random()*icons.length)];
span.style.left=
Math.random()*100+'vw';
span.style.animationDuration=
(8+Math.random()*12)+'s';
span.style.fontSize=
(12+Math.random()*20)+'px';
hearts.appendChild(span);
}
</script>
</body>
