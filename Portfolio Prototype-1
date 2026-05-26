<!DOCTYPE html>
<html>
<head>
    <title>My Portfolio</title>

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
    rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">

<style>
body{
    background:white smoke;
    font-family:Lato;
}

/* Navbar */
.navbar{
    background:#222;
}
.navbar a{
    color:white !important;
}

/* Hero section */
.hero{
    text-align:center;
    padding:80px;
    background:linear-gradient(to right,#a07dc7,#8f94fb);
    color:white;
}
.hero img{
    width:350px;
    border-radius:100%;
    border:4px solid white;
}

/* About */
.about{
    padding:50px;
}

/* Cards */
.card{
    transition:0.3s;
}
.card:hover{
    transform:scale(1.05);
}

/* Contact */
.contact{
    background:#222;
    color:white;
    padding:40px;
    text-align:center;
}
footer{
    text-align:center;
    padding:15px;
}
.progress{
    height:25px;
    border-radius:20px;
}
.progress-bar{
    font-weight:bold;
    animation:load 2s;
}
@keyframes load{
    from{
        width:0;
    }
}

/* Dark Mode */
.dark-mode{
    background:#121212;
    color:white;
}
.dark-mode .card{
    background:#1f1f1f;
    color:white;
}
.dark-mode .about{
    color:white;
}
.dark-mode .navbar{
    background:black;
}
.dark-mode .contact{
    background:black;
}
.dark-mode .progress{
    background:#444;
}
.dark-mode footer{
    background:#111;
    color:white;
}

.social-icons a{
	font-size:30px;
	margin:15px;
	color:white;
	text-decoration:none;
	transition:0.3s;
}
.social-icons a:hover{
	color:gold;
	transform:scale(1.2);
}

#clock{
font-size:25px;
margin-top:15px;
font-weight:bold;
}

#topBtn{
display:none;
position:fixed;
bottom:20px;
right:20px;
z-index:99;
border:none;
outline:none;
background:#222;
color:white;
cursor:pointer;
padding:12px 18px;
border-radius:50%;
font-size:20px;
transition:0.3s;
}
#topBtn:hover{
transform:scale(1.1);
}

#interests .card{
transition:0.4s;
border-radius:15px;
}
#interests .card:hover{
transform:translateY(-10px);
}

#contactForm{
max-width:600px;
margin:auto;
}
#successMsg{
margin-top:20px;
font-weight:bold;
color:lightgreen;
}

#quote{
font-style:italic;
font-size:22px;
padding:15px;
}
.card{
border-radius:15px;
}

</style>
</head>

<body>
<!-- Navbar -->
<nav class="navbar navbar-expand-lg">
<div class="container">

<a class="navbar-brand text-white" href="#"><big>My Portfolio</big></a>

<button class="navbar-toggler bg-light" data-bs-toggle="collapse" data-bs-target="#menu">
<span>☰</span>
</button>

<div class="collapse navbar-collapse" id="menu">
<ul class="navbar-nav ms-auto">
<li class="nav-item">
<a class="nav-link" href="#about">About</a>
</li>

<li class="nav-item">
<a class="nav-link" href="#skills">Skills</a>
</li>

<li class="nav-item">
<a class="nav-link" href="#projects">Projects</a>
</li>

<li class="nav-item">
<a class="nav-link" href="#contact">Contact</a>
</li>

<li class="nav-item">
<a class="nav-link" href="#interests">Interests</a>
</li>
</ul>

<button class="btn btn-light ms-3" onclick="toggleMode()">~ Dark Mode</button>

</div>
</div>
</nav>

<!-- Hero -->
<section class="hero">
<img src="C://Users//ADMIN//Desktop//New folder.jpeg//" >
<h1 class="mt-3">
Hello, I'm Giannina Alwyn
</h1>
<p><big>
Web Developer | Student | Designer
</big></p>

<h4 id="clock"></h4>

<button class="btn btn-light" onclick="welcome()">Hire Me</button>
</section>

<!-- About -->
<section id="about" class="about container">
<h2><big>About Me</big></h2>
<p>
I am a student interested in web
development and design.
I enjoy learning HTML, CSS,
Bootstrap and JavaScript while
creating responsive websites.
</p>
</section>

<!-- Interests -->
<section id="interests"
class="container mb-5">

<h2 class="text-center mb-4">My Interests</h2>
<div class="row text-center">
<div class="col-md-3">
<div class="card p-4">

<h1>💻</h1>
<h5>Coding</h5>
<p>
Building websites and learning
new technologies.
</p>
</div>
</div>

<div class="col-md-3">
<div class="card p-4">

<h1>🎵</h1>
<h5>Music</h5>
<p>
Listening to music and enjoying
instruments.
</p>
</div>
</div>

<div class="col-md-3">
<div class="card p-4">

<h1>📚</h1>
<h5>Reading</h5>
<p>
Exploring stories and gaining
knowledge.
</p>
</div>
</div>

<div class="col-md-3">
<div class="card p-4">

<h1>🎮</h1>
<h5>Gaming</h5>
<p>
Playing games for fun and
problem solving.
</p>
</div>
</div>

</div>
</section>

<!-- Skills -->
<section id="skills" class="container mb-5">

<h2 class="mb-4"><big>
Skills
</big></h2>
<div class="mb-4">
<h5>HTML</h5>
<div class="progress">
<div class="progress-bar bg-success"
style="width:90%;">90%
</div>
</div>
</div>

<div class="mb-4">
<h5>CSS</h5>
<div class="progress">
<div class="progress-bar bg-info"
style="width:80%;">80%
</div>
</div>
</div>

<div class="mb-4">
<h5>Bootstrap</h5>
<div class="progress">
<div class="progress-bar bg-warning"
style="width:75%;">75%
</div>
</div>
</div>

<div class="mb-4">
<h5>JavaScript</h5>
<div class="progress">
<div class="progress-bar bg-danger"
style="width:65%;">65%
</div>
</div>
</div>
</section>

<!-- Projects -->
<section id="projects"
class="container mb-5">

<h2>Projects</h2>
<div class="row">
<div class="col-md-6">
<div class="card p-3">
<h4>Calculator</h4>
<p>Simple JS calculator.</p>
</div>
</div>

<div class="col-md-6">
<div class="card p-3">

<h4>School Website</h4>
<p>Responsive website using Bootstrap.</p>
</div>
</div>
</div>
</section>

<!-- Daily Quote -->
<section class="container text-center mb-5">
<h2>Quote Of The Moment</h2>
<div class="card p-4">
<h4 id="quote">Loading quote...</h4>
</div>
</section>

<!-- Contact -->
<section id="contact"class="contact">
<h2>Contact Me</h2>
<p>Feel free to send a message</p>
<form id="contactForm"
class="container">
<input type="text" id="name" placeholder="Your Name" class="form-control mb-3" required>
<input type="email" id="email" placeholder="Your Email" class="form-control mb-3" required>
<textarea id="message" placeholder="Your Message" rows="5" class="form-control mb-3" required>
</textarea>
<button type="submit" class="btn btn-warning">Send Message</button>
</form>

<p id="successMsg"></p>
</section>

<footer>
<p>© 2026 My Portfolio</p>
<div class="social-icons">
<a href="https://www.instagram.com/ft_.vixenjinx._/"><i class="bi bi-instagram"></i></a>
<a href="https://github.com/gianninaalwyn"><i class="bi bi-github"></i></a>
</div>
</footer>

<!-- Bootstrap JS -->

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

<!-- JavaScript -->
<script>
function welcome(){
    alert("Thanks for visiting my portfolio!");
}

function toggleMode(){
    document.body.classList.toggle("dark-mode");
}

function updateClock(){
let now =
new Date();
document.getElementById("clock")
.innerHTML =
now.toDateString()
+" | "+
now.toLocaleTimeString();
}

setInterval(updateClock,1000);
updateClock();
window.onscroll =
function(){
scrollButton();
};

function scrollButton(){
let button =
document.getElementById("topBtn");
if(document.body.scrollTop>100 ||
document.documentElement.scrollTop>100)
{
button.style.display =
"block";
}
else{
button.style.display =
"none";
}
}
function topFunction(){
window.scrollTo({
top:0,
behavior:"smooth"
});
}

const quotes = [
"Progress matters more than perfection.",
"Small steps still move you forward.",
"Learning is slow magic.",
"Discipline builds results.",
"Dreams need action.",
"Keep creating.",
"Your future self is watching.",
"Consistency beats motivation."
];
function randomQuote(){
let random = Math.floor(
Math.random() * quotes.length
);
document.getElementById("quote")
.innerHTML =
quotes[random];
}
randomQuote();
setInterval(
randomQuote,
300000
);

document.getElementById("contactForm").addEventListener("submit", function(event)
{
event.preventDefault();
let name =
document.getElementById("name").value;
document.getElementById("successMsg").innerHTML = "Thank you, "+ name +"! Your message was sent.";
this.reset();
}
);
</script>

<button id="topBtn"onclick="topFunction()">↑</button>

</body>
</html>
