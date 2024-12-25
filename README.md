# Project Responsive Web Design using Bootstrap
## Date:25.12.24

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
<html>
<head>
    <title>Dribble</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

    <nav class="navbar navbar-expand-lg navbar-light bg-info">
        <div class="container">
            <a class="navbar-brand fw-bold text-dark" href="#">Dribbble</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto">
                    <li class="nav-item"><a class="nav-link text-light" href="#">Products</a></li>
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

    <section id="home" class="bg-white py-5"  style="height: 35vh;" >
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-6 text-center text-md-middle">
                    <h1 class="text-blue fw-bold text-center text-uppercase display-3 lh-sm">What are you working on?</h1>
                    <p class="my-3">An online platform and community where designers, artists, and creatives share their work and connect with potential collaborators.</p>
                    <button class="btn btn-warning me-2">Learn More</button>
                    <button class="btn btn-warning">Sign up</button>
                </div>
                <div class="col-md-6 text-center">
                    <img src="home.png" class="img-fluid" alt="Design Work" style="height: 40vh;">
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
                    <button class="btn btn-light btn-danger btn-outline-dark">Now</button>
                    <button class="btn btn-light btn-danger btn-outline-dark">Products</button>
                </div>
            </div>
            <div class="row g-4">
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="img.jpeg" width="260" height="225">
                      
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Zhenya Rynzhuk</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="imga.jpeg" width="260" height="225">
                        
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Mike | Creative Mints</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="imgb.jpeg" width="260" height="225">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Yoga Perdana</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="img0.jpeg" width="260" height="225" >
                       
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Slava Kornilov</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="img1.jpeg" width="260" height="225">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Hrvoje Grubisic</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="img2.jpeg" width="260" height="225">
                        
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Shawna X</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="img3.jpeg"width="260" height="225">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Abu Hena Rasel</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="img4.jpeg"width="260" height="225">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Alex Tass</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        </div>
    </section>


    <footer class="bg-dark text-white py-3">
        <div class="container text-center">
            <p class="mb-0">Designed and developed by SRINITHI MUTHUKUMAR (24010166)</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

## OUTPUT:
![alt text](<../Screenshot 2024-12-25 193942.png>)
![alt text](<../Screenshot 2024-12-25 193954.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
