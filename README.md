so this is my code which things should i include say perfectly 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Martial Arts Academy</title>

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

<style>

body{
scroll-behavior:smooth;
}

/* HERO */
.hero{
background:linear-gradient(rgba(0,0,0,.7),rgba(0,0,0,.7)),
url("https://images.unsplash.com/photo-1517649763962-0c623066013b");
background-size:cover;
background-position:center;
color:white;
padding:150px 20px;
text-align:center;
}

.section{
padding:80px 20px;
}

.feature-box{
background:white;
padding:25px;
border-radius:10px;
box-shadow:0 5px 15px rgba(0,0,0,.1);
height:100%;
}

.gallery img{
border-radius:10px;
width:100%;
height:220px;
object-fit:cover;
}

footer{
background:#111;
color:white;
padding:30px;
}

</style>
</head>

<body>

<!-- NAVBAR -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
<div class="container">
<a class="navbar-brand">Martial Academy</a>

<button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#nav">
<span class="navbar-toggler-icon"></span>
</button>

<div class="collapse navbar-collapse" id="nav">
<ul class="navbar-nav ms-auto">
<li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
<li class="nav-item"><a class="nav-link" href="#about">About</a></li>
<li class="nav-item"><a class="nav-link" href="#classes">Classes</a></li>
<li class="nav-item"><a class="nav-link" href="#schedule">Schedule</a></li>
<li class="nav-item"><a class="nav-link" href="#gallery">Gallery</a></li>
<li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
<li class="nav-item"><a class="nav-link" href="#login">Login</a></li>
</ul>
</div>
</div>
</nav>

<!-- HOME -->
<section id="home" class="hero">
<h1 class="display-4 fw-bold">Train Like a Warrior</h1>
<p class="lead">Build strength, discipline, and confidence with expert coaching</p>
<p class="mt-3">Join a supportive community focused on personal growth, self-defense, fitness, and competitive martial arts training for all age groups.</p>
<a href="#classes" class="btn btn-danger btn-lg mt-3">Start Training</a> 
</section>

<!-- ABOUT -->
<section id="about" class="section bg-light">
<div class="container">

<h2 class="text-center mb-5">Why Choose Our Academy</h2>

<div class="row g-4">

<div class="col-md-4">
<div class="feature-box">
<h5>Professional Instructors</h5>
<p>Certified trainers with years of competition and teaching experience guide students through structured programs that focus on safety, discipline, and skill mastery.</p>
</div>
</div>

<div class="col-md-4">
<div class="feature-box">
<h5>Modern Training Facility</h5>
<p>Our academy is equipped with professional mats, fitness equipment, and safe training zones to ensure effective learning in a comfortable environment.</p>
</div>
</div>

<div class="col-md-4">
<div class="feature-box">
<h5>All Ages Welcome</h5>
<p>From kids’ beginner programs to adult competitive training, we provide structured pathways that support every student’s goals and fitness level.</p>
</div>
</div>

</div>
</div>
</section>

<!-- CLASSES -->
<section id="classes" class="section text-center">
<div class="container">

<h2 class="mb-4">Training Programs</h2>
<p class="mb-5">Each program is designed to improve strength, flexibility, discipline, and mental focus while building real-world self-defense skills.</p>

<div class="row g-4">

<div class="col-md-4">
<div class="card p-4 h-100">
<h5>Karate</h5>
<p>Traditional striking techniques focusing on discipline, balance, and precision. Ideal for beginners and advanced martial artists.</p>
</div>
</div>

<div class="col-md-4">
<div class="card p-4 h-100">
<h5>Taekwondo</h5>
<p>Dynamic kicking techniques, agility training, and competitive sparring designed to build speed, flexibility, and confidence.</p>
</div>
</div>

<div class="col-md-4">
<div class="card p-4 h-100">
<h5>Jiu‑Jitsu</h5>
<p>Ground fighting and submission techniques emphasizing strategy, leverage, and control for real-life self-defense situations.</p>
</div>
</div>

</div>
</div>
</section>

<!-- SCHEDULE -->
<section id="schedule" class="section bg-light">
<div class="container">
<h2 class="text-center mb-4">Weekly Training Schedule</h2>
<p class="text-center mb-4">Flexible class timings allow students to train consistently while balancing school, work, and personal commitments.</p>

<div class="table-responsive">

<table class="table table-bordered text-center">

<thead class="table-dark">
<tr>
<th>Day</th>
<th>6 PM</th>
<th>7 PM</th>
<th>8 PM</th>
</tr>
</thead>

<tbody>
<tr><td>Monday</td><td>Karate</td><td>Taekwondo</td><td>Jiu‑Jitsu</td></tr>
<tr><td>Tuesday</td><td>Fitness</td><td>Karate</td><td>Sparring</td></tr>
<tr><td>Wednesday</td><td>Taekwondo</td><td>Jiu‑Jitsu</td><td>Conditioning</td></tr>
<tr><td>Thursday</td><td>Karate</td><td>Technique Drills</td><td>Sparring</td></tr>
<tr><td>Friday</td><td>Jiu‑Jitsu</td><td>Fitness</td><td>Open Mat</td></tr>
</tbody>

</table>

</div>
</div>
</section>

<!-- GALLERY -->
<section id="gallery" class="section">
<div class="container">

<h2 class="text-center mb-5">Training Gallery</h2>

<div class="row g-4 gallery">

<div class="col-md-4"><img src="https://images.unsplash.com/photo-1549719386-74dfcbf7dbed"></div>
<div class="col-md-4"><img src="https://images.unsplash.com/photo-1579758629938-03607ccdbaba"></div>
<div class="col-md-4"><img src="https://images.unsplash.com/photo-1599058917765-a780eda07a3e"></div>

</div>

</div>
</section>

<!-- CONTACT -->
<section id="contact" class="section bg-light text-center">
<div class="container">
<h2>Contact & Enrollment</h2>
<p>Visit our academy for a free trial session and consultation.</p>
<p>Email: martialacademy@email.com</p>
<p>Phone: +971 123 4567</p>
<p>Location: Dubai Training Street</p>
</div>
</section>

<!-- LOGIN -->
<section id="login" class="section text-center">
<div class="container">

<h2>Member Login</h2>
<p class="mb-3">Log in to track attendance and training progress.</p>

<input id="username" class="form-control w-50 mx-auto mb-2" placeholder="Username">
<input type="password" id="password" class="form-control w-50 mx-auto mb-3" placeholder="Password">

<button onclick="login()" class="btn btn-dark">Login</button>

<p id="message" class="mt-3 fw-bold text-success"></p>

<h4 class="mt-5">Saved Login Records</h4>

<div class="table-responsive">

<table class="table table-bordered w-75 mx-auto">
<thead class="table-dark">
<tr>
<th>Username</th>
<th>Password</th>
</tr>
</thead>
<tbody id="records"></tbody>
</table>

</div>

</div>
</section>

<footer class="text-center">
© Martial Arts Academy 2026 — Train with discipline, grow with confidence
</footer>

<script>

function login(){

let user = document.getElementById("username").value;
let pass = document.getElementById("password").value;

if(user=="" || pass==""){
alert("Enter details first!");
return;
}

let data = JSON.parse(localStorage.getItem("academyUsers")) || [];

data.push({username:user,password:pass});

localStorage.setItem("academyUsers", JSON.stringify(data));

message.innerHTML = "✅ Welcome — you have logged in!";

showRecords();

username.value="";
password.value="";
}

function showRecords(){

let data = JSON.parse(localStorage.getItem("academyUsers")) || [];
let table = document.getElementById("records");

table.innerHTML="";

data.forEach(item=>{
table.innerHTML += `<tr><td>${item.username}</td><td>${item.password}</td></tr>`;
});
}

showRecords();

</script>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
