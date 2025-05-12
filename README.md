# Project Responsive Web Design using Bootstrap
## Date: 12-05-2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dribbble Clone</title>
  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
    rel="stylesheet"
  />
  <style>
    .hero {
      background-color: #f8f9fa;
      padding: 80px 20px;
      text-align: center;
    }
    .gallery img {
      width: 100%;
      border-radius: 8px;
    }
    .footer {
      background-color: #212529;
      color: white;
      text-align: center;
      padding: 20px 0;
      margin-top: 50px;
    }
  </style>
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light shadow-sm">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">Dribbble Clone</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link" href="#">Inspiration</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Find Work</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Learn Design</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Go Pro</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Sign In</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero">
    <div class="container">
      <h1 class="display-5 fw-bold">Discover the world’s top designers & creatives</h1>
      <p class="lead mt-3">Dribbble is the leading destination to find & showcase creative work.</p>
      <a href="#" class="btn btn-primary btn-lg mt-3">Sign up</a>
    </div>
  </section>

  <!-- Gallery Section -->
  <section class="container my-5">
    <h2 class="mb-4">Explore Design Shots</h2>
    <div class="row gallery">
      <div class="col-md-4 mb-4"><img src="https://img.freepik.com/free-photo/anime-moon-landscape_23-2151645896.jpg?uid=R199850407&ga=GA1.1.2088523299.1747059533&w=740" alt="Design 1" /></div>
      <div class="col-md-4 mb-4"><img src="https://img.freepik.com/free-photo/illustration-anime-city_23-2151779669.jpg?uid=R199850407&ga=GA1.1.2088523299.1747059533&w=740" alt="Design 2" /></div>
      <div class="col-md-4 mb-4"><img src="https://img.freepik.com/free-photo/sunset-silhouettes-trees-mountains-generative-ai_169016-29371.jpg?uid=R199850407&ga=GA1.1.2088523299.1747059533&w=740" alt="Design 3" /></div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <div class="container">
      <p class="mb-0">Jayadeep</p>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```
## OUTPUT:
![image](https://github.com/user-attachments/assets/81707b7e-e3c1-4578-a5f8-2b87400e50f0)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
