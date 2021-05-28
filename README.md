<!DOCTYPE html>
<html>

<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width">
	<title>repl.it</title>
	<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet" type="text/css"
	/>
	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x"
	 crossorigin="anonymous">
</head>

<body>
	<!-- Navbar -->
	<nav class="navbar sticky-top navbar-expand-lg navbar-dark bg-primary">
		<div class="container-fluid">
			<a class="navbar-brand text-white" href="#">Navbar</a>
			<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#hero">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#Skills">MY SKILLS</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#works">MY WORK</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#contact">CONTACT ME</a>
        </li>
    </div>
  </div>
</nav>
<main class="container mt-3">
  <section class="d-flex justify-content-sm-center justify-content-md-evenly align-items-center flex-column-reverse gap-3 flex-md-row">
    <!-- Hero -->
    <div id="hero" class="d-flex justify-content-sm-center align-items-center flex-column flex-md-column-justify-contant-md-start align-items-md-start">
      <h5>Hiii..👋</h5>
      <h1>I'm Vedant shah </h1>
      <p>A Fullstack Web Developer!</p>
      <button class="btn btn-primary btn-sm"> My Cool Resume 😎 </button>
    </div>
    <div class=" d-md-none w-50 w-50">
      <img src="https://images.unsplash.com/photo-1535713875002-d1d0cf377fde?ixid=MnwxMjA3fDB8MHxzZWFyY2h8MXx8dXNlcnxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&w=1000&q=80" alt="vedant shah" class="w-100 h-100 rounded-circle shadow">
    </div>
    <div class="d-none d-md-block w-25 h-25">
       <img src="https://images.unsplash.com/photo-1535713875002-d1d0cf377fde?ixid=MnwxMjA3fDB8MHxzZWFyY2h8MXx8dXNlcnxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&w=1000&q=80" alt="vedant shah" class="w-100 h-100 rounded-circle shadow">

    </div>
  </section>
  <section id="Skills" class=" mt-5 p-4">
    <!-- My Skills -->
    <h1 class="text-primary text-center">My Skill Set</h1>
    <div class="mt-4 d-md-none d-flex justify-content-evenly">
   <i class="fab fa-html5 fa-3x" style="color:#f4470b"><h6 class="text-center">html</h6></i>
   <i class="fab fa-css3-alt fa-3x text-primary"><h6 class="text-center">CSS</h6></i>
   <i class="fab fa-bootstrap fa-3x" style="color:#730fef"><h6 class="text-center">Bootstap</h6></i>
    </div>
    <div class="mt-4 d-none d-md-flex justify-content-evenly">
   <i class="fab fa-html5 fa-7x" style="color:#f4470b"><h6 class="text-center">html</h6></i>
   <i class="fab fa-css3-alt fa-7x text-primary"><h6 class="text-center">CSS</h6></i>
   <i class="fab fa-bootstrap fa-7x" style="color:#730fef"><h6 class="text-center">Bootstap</h6></i>
    </div>
  </section>
  <section id="works" class="mt-4 p-4">
    <!-- My Wrok -->
    <h1 class="text-primary text-center">My Works</h1>
    <div class="d-flex flex-column flex-md-row justify-content-md-evenly gap-3">
    <div class="card  gap-2">
  <img src="https://images.unsplash.com/photo-1463171379579-3fdfb86d6285?ixid=MnwxMjA3fDB8MHxzZWFyY2h8NzZ8fHRlY2hub2xvZ3l8ZW58MHwwfDB8fA%3D%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60">
  <div class="card-body">
    <h5 class="card-title">Portfolio Website</h5>
    <p class="card-text">Bulid an amazing responsive Website with Bootstap.</p>
    <a href="#" class="btn btn-dark">view source <i class="fab fa-github"></i></a>
  </div>
</div>
<div class="card gap-2">
  <img src="https://images.unsplash.com/photo-1463171379579-3fdfb86d6285?ixid=MnwxMjA3fDB8MHxzZWFyY2h8NzZ8fHRlY2hub2xvZ3l8ZW58MHwwfDB8fA%3D%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60">
  <div class="card-body">
    <h5 class="card-title">Portfolio Website</h5>
    <p class="card-text">Bulid an amazing responsive Website with Bootstap.</p>
    <a href="#" class="btn btn-dark">view source <i class="fab fa-github"></i></a>
  </div>
</div>
<div class="card gap-2">
  <img src="https://images.unsplash.com/photo-1463171379579-3fdfb86d6285?ixid=MnwxMjA3fDB8MHxzZWFyY2h8NzZ8fHRlY2hub2xvZ3l8ZW58MHwwfDB8fA%3D%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60">
  <div class="card-body">
    <h5 class="card-title">Portfolio Website</h5>
    <p class="card-text">Bulid an amazing responsive Website with Bootstap.</p>
    <a href="#" class="btn btn-dark">view source <i class="fab fa-github"></i></a>
  </div>
</div>
    </div>
  </section>
  <section id="contact" class="mt-4 py-4">
    <!-- Contact Me -->
    <h1 class="text-primary text-center">Contact Form</h1>
   <div class="row">
     <div class="col-sm col-md-8">
    <form>
      <div class="mb-3">
  <label for="exampleFormControlInput1" class="form-label">Email address</label>
  <input type="email" required class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
</div>
<div class="mb-3">
  <label for="exampleFormControlTextarea1" class="form-label">Text Area</label>
  <textarea class="form-control" id="exampleFormControlTextarea1" placeholder="Enter your message" rows="3"></textarea>
</div>
<button type="submit" class="btn btn-primary">
Submit
</button>
    </form>
     </div>
     <div class=" col-sm col-md-4">
    <div class="mt-3">
    <h4><i class="fas fa-envelope-square text-primary"></i> vedanshah902@gmail.com</h4>
    <button type="button" class="btn btn-link"><a href="https://www.facebook.com/vedant.shah.1257"></a> <i class="fab fa-facebook"></i></button>
    </div>
  </section>
</main>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4" crossorigin="anonymous"></script>
  </body>
</html>
