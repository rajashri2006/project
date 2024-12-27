# Project Responsive Web Design using Bootstrap
# Date: 16-12-2024
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
<html>
<head>
    <meta charset="UTF-8">
    <title>Dribble</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand fw-bold text-danger" href="#">Dribbble</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto">
                    <li class="nav-item"><a class="nav-link text-white" href="#">Shots</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Designers</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Teams</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Community</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Jobs</a></li>
                </ul>
            </div>
            <a class="btn btn-outline-light me-2" href="#">Sign in</a>
            <a class="btn btn-outline-light me-2" href="#">Sign Up</a>
            <input type="search" class="form-control w-auto" placeholder="Search" style="margin: 20px;">
        </div>
    </nav>

    <section id="home" class="bg-white py-5"  style="height: 45vh;" >
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-6 text-center text-md-middle">
                    <h1 class="display-4 fw-bold">What are you working on?</h1>
                    <p class="my-3">Dribbble is a show-and-tell platform for designers.</p>
                    <button class="btn btn-secondary me-2">Learn More</button>
                    <button class="btn btn-primary">Sign up</button>
                </div>
                <div class="col-md-6 text-center">
                    <img src="new.webp" class="img-fluid" alt="Design Work" style="height: 45vh;">
                </div>
            </div>
        </div>
    </section>

    <section class="py-5">
        <div class="container">
            <div class="row mb-4">
                <div class="col-md-4">
                    <h2 class="fw-bold">Popular</h2>
                </div>
                <div class="col-md-4 text-center">
                    <button class="btn btn-light btn-secondary btn-outline-dark">Now</button>
                    <button class="btn btn-light btn-secondary btn-outline-dark">Shots</button>
                </div>
            </div>
            <div class="row g-4">
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="img7.jpg" width="300" height="225">
                      
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Awe Design Studio</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="sk1.avif" width="300" height="225">
                        
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Russlan silz</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="sk2.jpg" width="300" height="225">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Alfrey Davilla</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="img1.jpg" class="card-img-top" alt="Shot 2">
                       
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 MakeReign</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="img4.jpg" class="card-img-top" alt="Shot 2">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Mattias Johannson</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="img2.jpg" width="300" height="225">
                        
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Jan Losert</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="sk3.avif"width="300" height="225">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Wkio</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="sk5.jpg"width="300" height="225">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Romain Tystramm</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white py-3">
        <div class="container text-center">
            <p class="mb-0">Designed and developed by PREETHI D (24007817)</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
# OUTPUT:
![Screenshot 2024-12-27 090607](https://github.com/user-attachments/assets/0a5d335b-2e4a-4dcc-bae3-9b4056fb0d27)

![Screenshot 2024-12-27 090634](https://github.com/user-attachments/assets/73d0c939-5b69-4f39-a4af-b757e3b2157d)



# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
