# Project Responsive Web Design using Bootstrap
# Date:
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>NextGen Creatives</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .hero {
      background: linear-gradient(to right, #0072ff, #00c6ff);
      color: white;
      text-align: center;
      padding: 100px 20px;
    }

    .features .card {
      border: none;
      background-color: #f9f9f9;
    }

    .footer {
      background-color: #222;
      color: white;
    }
  </style>
</head>

<body>
  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand" href="#">NextGen Creatives</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Services</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Team</a></li>
          <li class="nav-item"><a class="btn btn-primary text-white nav-link" href="#">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero">
    <h1 class="display-4">Empowering Creativity</h1>
    <p class="lead">Innovative designs and solutions for the next generation.</p>
    <a href="#" class="btn btn-outline-light btn-lg">Explore More</a>
  </section>

  <!-- What We Offer -->
  <section class="container text-center py-5">
    <h2 class="mb-4">What We Offer</h2>
    <p>Explore our services crafted to elevate your creative projects.</p>
    <div class="row mt-4">
      <div class="col-md-4">
        <div class="card p-4">
          <h5>Creative Branding</h5>
          <p>Transform your brand with stunning visuals and impactful messaging.</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card p-4">
          <h5>Web Development</h5>
          <p>Custom-built websites with a focus on functionality and design.</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card p-4">
          <h5>Content Creation</h5>
          <p>Engaging multimedia content to capture your audience's attention.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Success Stories -->
  <section class="container py-5">
    <h2 class="mb-4">Success Stories</h2>
    <div class="row g-4">
      <div class="col-md-4">
        <img src="1.png" class="img-fluid rounded" width="250" height="200">
        <h5 class="mt-3">Startup X</h5>
        <p>We helped Startup X launch their app, reaching 1 million users in just 3 months.</p>
      </div>
      <div class="col-md-4">
        <img src="2.png" class="img-fluid rounded" width="250" height="200">
        <h5 class="mt-3">Global NGO</h5>
        <p>Designed an impactful campaign that raised $5M in donations worldwide.</p>
      </div>
      <div class="col-md-4">
        <img src="3.png" class="img-fluid rounded"  width="300" height="150">
        <h5 class="mt-3">Tech Innovators</h5>
        <p>Developed a sleek website that doubled the client's online traffic.</p>
      </div>
    </div>
  </section>

  <!-- Meet the Team -->
  <section class="container text-center py-5">
    <h2>Meet Our Experts</h2>
    <div class="row mt-4">
      <div class="col-md-4">
        <img src="4.png" class="rounded-circle mb-3" width="300px" height="300px">
        <h5>Alex Carter</h5>
        <p>Creative Director</p>
      </div>
      <div class="col-md-4">
        <img src="5.png" class="rounded-circle mb-3" width="300px" height="300px">
        <h5>Morgan Taylor</h5>
        <p>Full Stack Developer</p>
      </div>
      <div class="col-md-4">
        <img src="6.png" class="rounded-circle mb-3" width="300px" height="300px">
        <h5>Jordan Lee</h5>
        <p>Marketing Strategist</p>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer text-center py-3">
    <p>Designed by Jisha Bossne SJ &copy; 2024</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>
```
# OUTPUT:
![Screenshot_23-12-2024_202335_](https://github.com/user-attachments/assets/29dd89ef-59a2-4a52-b021-b1e694f2a180)

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
