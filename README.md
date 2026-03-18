<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Caricare Group LLC | Roofing Experts</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css" rel="stylesheet">
  

  <style>
    body { font-family: 'Segoe UI', sans-serif; }

    /* HERO */
    .hero {
      background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),
      url('images/hero-roof.jpg') center/cover no-repeat;
      color: white;
      padding: 140px 0;
      text-align: center;
    }

    .btn-warning {
      background-color: #f5a000;
      border: none;
    }

    .btn-warning:hover {
      background-color: #d98c00;
    }

    .section { padding: 80px 0; }

    .card {
      border: none;
      border-radius: 15px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.05);
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-8px);
    }

    .cta {
      background: #111;
      color: white;
    }

    .logo {
      height: 45px;
    }

    .gallery img {
      border-radius: 10px;
      width: 100%;
      height: 250px;
      object-fit: cover;
    }

    .trust-badge {
      font-size: 14px;
      opacity: 0.9;
    }

    footer { background:#000; color:#aaa; padding:50px 0; }

    .sticky-cta {
      position: fixed;
      bottom: 20px;
      right: 20px;
      z-index: 999;
    }
  </style>
</head>
<body>

<!-- NAVBAR -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
  <div class="container">
    <a class="navbar-brand d-flex align-items-center" href="#">
      <img src="images/logo.png" class="logo me-2">
      Caricare Group LLC
    </a>

    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#nav">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="nav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
        <li class="nav-item"><a class="nav-link" href="#process">Process</a></li>
        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
      </ul>
      <a href="tel:+14072059411" class="btn btn-warning ms-3">Call Now</a>
    </div>
  </div>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="container">
    <h1 class="display-4 fw-bold">Florida’s Most Reliable Roofing Company</h1>
    <p class="lead mb-4">Fast Estimates • 5-Star Service • Residential & Commercial</p>

    <div class="mb-3">
      <a href="#contact" class="btn btn-warning btn-lg me-2">Get Free Estimate</a>
      <a href="tel:+14072059411" class="btn btn-outline-light btn-lg">Call Now</a>
    </div>

    <div class="trust-badge">
      ⭐ 5.0 Google Rating • Licensed & Insured • Serving Florida
    </div>
  </div>
</section>

<!-- SERVICES -->
<section id="services" class="section text-center">
  <div class="container">
    <h2 class="mb-5">Our Roofing Services</h2>
    <div class="row g-4">

      <!-- 🔴 PUEDES AGREGAR IMAGEN DENTRO DE CADA CARD -->
      <div class="col-md-4">
        <div class="card p-4">
          <img src="images/repair.jpg" class="mb-3"> <!-- OPCIONAL -->
          <h5>Roof Repair</h5>
          <p>Quick leak fixes and damage restoration.</p>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card p-4">
          <img src="images/replacement.jpg" class="mb-3">
          <h5>Roof Replacement</h5>
          <p>Full roof upgrades with premium materials.</p>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card p-4">
          <img src="images/inspection.jpg" class="mb-3">
          <h5>Roof Inspection</h5>
          <p>Detailed inspections to prevent costly issues.</p>
        </div>
      </div>

    </div>
  </div>
</section>

<!-- REVIEWS -->
<section class="section bg-light">
  <div class="container">
    <h2 class="text-center mb-5">What Our Customers Say</h2>

    <!-- ELFSIGHT GOOGLE REVIEWS -->
    <div class="elfsight-app-a557b3c8-86c2-4b72-a651-91aa8f84d26a" data-elfsight-app-lazy></div>

  </div>
</section>

<!-- PROCESS (IMPROVED FLOW) -->
<section id="process" class="section bg-light text-center">
  <div class="container">
    <h2 class="mb-3">Our Process</h2>
    <p class="mb-5 text-muted">
      Simple, fast, and transparent — starting with a <strong>FREE inspection visit</strong>.
    </p>

    <div class="row align-items-center g-4 justify-content-center">

      <!-- STEP 1 -->
      <div class="col-md-2">
        <div class="p-4 bg-white rounded shadow-sm h-100">
          <div class="mb-3 fs-1 text-warning">
            <i class="bi bi-search"></i>
          </div>
          <h6>Free Inspection</h6>
          <p class="small text-muted">We visit your property at no cost.</p>
        </div>
      </div>

      <!-- ARROW -->
      <div class="col-md-1 d-none d-md-block">
        <i class="bi bi-arrow-right fs-3 text-warning"></i>
      </div>

      <!-- STEP 2 -->
      <div class="col-md-2">
        <div class="p-4 bg-white rounded shadow-sm h-100">
          <div class="mb-3 fs-1 text-warning">
            <i class="bi bi-file-earmark-text"></i>
          </div>
          <h6>Estimate</h6>
          <p class="small text-muted">Clear and honest pricing.</p>
        </div>
      </div>

      <!-- ARROW -->
      <div class="col-md-1 d-none d-md-block">
        <i class="bi bi-arrow-right fs-3 text-warning"></i>
      </div>

      <!-- STEP 3 -->
      <div class="col-md-2">
        <div class="p-4 bg-white rounded shadow-sm h-100">
          <div class="mb-3 fs-1 text-warning">
            <i class="bi bi-house-gear"></i>
          </div>
          <h6>Installation</h6>
          <p class="small text-muted">Fast and professional work.</p>
        </div>
      </div>

      <!-- ARROW -->
      <div class="col-md-1 d-none d-md-block">
        <i class="bi bi-arrow-right fs-3 text-warning"></i>
      </div>

      <!-- STEP 4 -->
      <div class="col-md-2">
        <div class="p-4 bg-white rounded shadow-sm h-100">
          <div class="mb-3 fs-1 text-warning">
            <i class="bi bi-check-circle"></i>
          </div>
          <h6>Final Check</h6>
          <p class="small text-muted">We ensure top quality.</p>
        </div>
      </div>

    </div>

    <!-- CTA -->
    <div class="mt-5">
      <a href="#contact" class="btn btn-warning btn-lg">
        Schedule Your Free Inspection
      </a>
    </div>

  </div>
</section>

<!-- GALLERY GRID -->
<section id="gallery" class="section bg-light">
  <div class="container">
    <h2 class="text-center mb-5">Project Gallery</h2>

    <div class="row g-4 gallery">
      <!-- 🔴 AQUI SUBES TUS FOTOS REALES -->
      <div class="col-md-4"><img src="images/gallery1.jpg"></div>
      <div class="col-md-4"><img src="images/gallery2.jpg"></div>
      <div class="col-md-4"><img src="images/gallery3.jpg"></div>
      <div class="col-md-4"><img src="images/gallery4.jpg"></div>
      <div class="col-md-4"><img src="images/gallery5.jpg"></div>
      <div class="col-md-4"><img src="images/gallery6.jpg"></div>
    </div>
  </div>
</section>

<!-- CTA -->
<section class="section cta text-center">
  <div class="container">
    <h2>Need Roofing Help? Call Us Now</h2>
    <p>Fast response. Free estimates. No pressure.</p>
    <a href="tel:+14072059411" class="btn btn-warning btn-lg">Call Now</a>
  </div>
</section>

<!-- CONTACT -->
<section id="contact" class="section">
  <div class="container">
    <h2 class="text-center mb-4">Request a Free Estimate</h2>
    <div class="row">

      <div class="col-md-6">
        <form>
          <input class="form-control mb-3" placeholder="Full Name">
          <input class="form-control mb-3" placeholder="Phone Number">
          <input class="form-control mb-3" placeholder="Email">
          <textarea class="form-control mb-3" placeholder="Tell us about your project"></textarea>
          <button class="btn btn-warning w-100">Get My Free Estimate</button>
        </form>
      </div>

      <div class="col-md-6">
        <h5>Contact Info</h5>
        <p><i class="bi bi-telephone"></i> +1 407-205-9411</p>
        <p><i class="bi bi-geo-alt"></i> Serving all Florida</p>
        <p><i class="bi bi-clock"></i> Mon-Sat: 8AM - 8:30PM</p>
      </div>

    </div>
  </div>
</section>

<!-- FLOATING CALL BUTTON -->
<a href="tel:+14072059411" class="btn btn-warning sticky-cta">
  <i class="bi bi-telephone-fill"></i>
</a>

<!-- FOOTER -->
<footer>
  <div class="container text-center">
    <p>© 2026 Caricare Group LLC. All rights reserved.</p>
  </div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
<!-- ELFSIGHT SCRIPT -->
<script src="https://static.elfsight.com/platform/platform.js" async></script>
</body>
</html>
