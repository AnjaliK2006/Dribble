# Project Responsive Web Design using Bootstrap
## Date: 28.12.2024

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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone - Alternate</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        
        .hero-section {
            background: linear-gradient(to bottom right, #ff7eb3, #ff758c);
            color: white;
            text-align: center;
            padding: 60px 20px;
        }
        .card img {
            transition: transform 0.3s ease-in-out;
        }
        .card img:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    
    <nav class="navbar navbar-expand-lg navbar-light bg-light shadow-sm">
        <div class="container">
            <a class="navbar-brand" href="#">Dribble Clone</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Portfolio</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Blog</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    
    <section class="hero-section">
        <div class="container">
            <h1 class="display-4">Discover Stunning Designs</h1>
            <p class="lead">Join the community of creative designers showcasing their work.</p>
            <a href="#" class="btn btn-outline-light btn-lg">Explore More</a>
        </div>
    </section>

    
    <section class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Our Featured Designs</h2>
            <div class="row row-cols-1 row-cols-md-3 g-4">
        
                <div class="col">
                    <div class="card">
                        <img src="UI.png" class="card-img-top" alt="Work Example">
                        <div class="card-body">
                            <h5 class="card-title">Project Alpha</h5>
                            <p class="card-text">A minimal yet beautiful UI design for your inspiration.</p>
                        </div>
                    </div>
                </div>
                
                <div class="col">
                    <div class="card">
                        <img src="VR.png" class="card-img-top" alt="Work Example">
                        <div class="card-body">
                            <h5 class="card-title">Creative Wave</h5>
                            <p class="card-text">Explore this vibrant and colorful artwork.</p>
                        </div>
                    </div>
                </div>
                
                <div class="col">
                    <div class="card">
                        <img src="color.png" class="card-img-top" alt="Work Example">
                        <div class="card-body">
                            <h5 class="card-title">Digital Concept</h5>
                            <p class="card-text">A futuristic concept design for web apps.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>


    <footer class="text-center py-3 bg-dark text-white">
        <p>Designed and Developed by Anjali K.</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>


```

## OUTPUT:
![alt text](<Screenshot (41).png>)
![alt text](<Screenshot (42).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
