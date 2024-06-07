<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jeward's Portfolio</title>
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <!-- Custom CSS -->
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Custom Styles */
        body {
            font-family: Arial, sans-serif;
        }

        /* Navbar */
        .navbar {
            background-color: #343a40;
            color: #fff;
            padding: 10px 0;
            position: sticky;
            top: 0;
            z-index: 1000;
    
        }

        .navbar-brand {
            font-weight: bold;
        }

        .nav-link {
            color: #fff !important;
            font-weight: bold;
        }

        /* Hero Section */
        #hero {
            background-color: #f8f9fa;
            color: #343a40;
            padding: 100px 0;
        }

        #hero h1 {
            font-size: 3.5rem;
            font-weight: bold;
        }

        /* Projects Section */
        #projects {
            background-color: #fff;
            padding: 100px 0;
        }

        .project-card {
            border: 0;
            transition: all 0.3s ease;
        }

        .project-card:hover {
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        /* About Section */
        #about {
            background-color: #343a40;
            color: #fff;
            padding: 100px 0;
        }

        #about h2 {
            font-size: 2.5rem;
            font-weight: bold;
        }

        /* Contact Section */
        #contact {
            background-color: #f8f9fa;
            padding: 100px 0;
        }

        /* Footer */
        footer {
            background-color: #343a40;
            color: #fff;
            padding: 20px 0;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>

    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Jeward's Portfolio</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#projects">Projects</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    
    <section id="hero">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-6">
                    <h1>Hello, I'm Jeward N. Mencede</h1>
                    <p>Welcome to my portfolio</p>
                    <a href="#projects" class="btn btn-primary btn-lg">View Portfolio</a>
                </div>
                <div class="col-md-6">
                    <img src="img/hero-bg.jpg" alt="Hero Background" class="img-fluid">
                </div>
            </div>
        </div>
    </section>
    
    <section id="projects">
        <div class="container">
            <h2 class="text-center mb-5">Projects</h2>
            <div class="row">
                <div class="col-md-4 mb-4">
                    <div class="card project-card">
                        <img src="img/project1.jpg" class="card-img-top" alt="Project 1">
                        <div class="card-body">
                            <h5 class="card-title">Project 1</h5>
                            <p class="card-text">Description of Project 1</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card project-card">
                        <img src="img/project2.jpg" class="card-img-top" alt="Project 2">
                        <div class="card-body">
                            <h5 class="card-title">Project 2</h5>
                            <p class="card-text">Description of Project 2</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card project-card">
                        <img src="img/project3.jpg" class="card-img-top" alt="Project 3">
                        <div class="card-body">
                            <h5 class="card-title">Project 3</h5>
                            <p class="card-text">Description of Project 3</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2 class="text-center mb-5">About Me</h2>
            <div class="row">
                <div class="col-md-6">
                    <img src="img/about-me.jpg" class="img-fluid rounded-circle mb-3" alt="About Me">
                </div>
                <div class="col-md-6">
                    <h3>Jeward N. Mencede</h3>
                    <p>Bachelor of Science in Computer Science</p>
                    <p>I am a passionate web developer with experience in creating user-friendly and visually appealing websites.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2 class="text-center mb-5">Contact</h2>
            <div class="row">
                <div class="col-md-4">
                    <div class="card">
                        <div class="card-body">
                            <h5 class="card-title">Phone</h5>
                            <p class="card-text">09123456789</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <div class="card-body">
                            <h5 class="card-title">Email</h5>
                            <p class="card-text">example@example.com</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <div class="card-body">
                            <h5 class="card-title">Address</h5>
                            <p class="card-text">123 Main St, City, Country</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container text-center">
            <p>&copy; 2024 Jeward's Portfolio. All rights reserved.</p>
        </div>
    </footer>

    <!-- Bootstrap JS, Popper.js, and jQuery -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
