# hmtl-js-css-git
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        body {
            background-color: #000000;
            color: white;
        }
        
        .header {
            background-color: #474747;
            color: white;  
            padding: 10px 20px;
            position: fixed;
            width: 100%;
            z-index: 1000;
        }
        .hero {
            background-image: url('https://your-image-url-here.jpg');
            background-size: cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
        }
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 20px;
        }
        .section-title {
            margin-top: 40px;
            margin-bottom: 20px;
        }
        .card {
            background-color: #222;
            border: none;
        }
        .card img {
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <div class="header">
        <nav class="navbar navbar-expand-lg">
            <div class="container-fluid">
                <a class="navbar-brand" href="#">Benvenuti Su Netflix</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav">
                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="#">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Serie TV</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Film</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">La mia lista</a>
                        </li>
                    </ul>
                    <div class="ms-auto">
                        <button class="btn btn-outline-light">Profilo</button>
                    </div>
                </div>
            </div>
        </nav>
    </div>

    <div class="hero">
        <img src="netflix.png" alt="1000" width="1000">
    </div>

    <div style="display: flex; justify-content: center; align-items: center; height: 100vh;">
    <button type="button" class="btn btn-danger btn-lg">Guarda ora</button>
</div>


    <div class="container mt-5 pt-5">
        <h2 class="section-title">Popolari su Netflix</h2>
        <div class="row">
            <div class="col-6 col-md-4 col-lg-3 mb-4">
                <div class="card">
                    <img src="breaking_bad.jpeg" alt="400" width="400" class="card-img-top">
                </div>
            </div>
            <div class="col-6 col-md-4 col-lg-3 mb-4">
                <div class="card">
                    <img src="squid.jpeg" alt="400" width="400" class="card-img-top">
                </div>
            </div>
            <div class="col-6 col-md-4 col-lg-3 mb-4">
                <div class="card">
                    <img src="carta.jpeg" alt="400" width="400" class="card-img-top">
                </div>
            </div>
            <div class="col-6 col-md-4 col-lg-3 mb-4">
                <div class="card">
                    <img src="squalo.jpeg" class="card-img-top">
                </div>
            </div>
        </div>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>
</html>