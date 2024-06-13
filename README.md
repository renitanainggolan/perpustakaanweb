<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <title>Reni - Homepage</title>
</head>
<body class="bg-light">
    <nav class="navbar navbar-expand-lg navbar-light bg-light text-dark sticky-top">
        <div class="container-fluid"> 
          <a class="navbar-brand">Czennie Library</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="/">Home</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Modul
                </a>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                  <li><a class="dropdown-item" href="/Modul 1">Modul 1</a></li>
                  <li><a class="dropdown-item" href="/Modul 2">Modul 2</a></li>
                  <li><a class="dropdown-item" href="/Modul 3">Modul 3</a></li>
                  <li><a class="dropdown-item" href="/Modul 4">Modul 4</a></li>
                  <li><a class="dropdown-item" href="/Modul 5">Modul 5</a></li>
                  <li><a class="dropdown-item" href="/Modul 6">Modul 6</a></li>
                  <li><a class="dropdown-item" href="/Modul 7">Modul 7</a></li>
                  <li><a class="dropdown-item" href="/Modul 8">Modul 8</a></li>
                </ul>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="/Contact">Contact</a>
              </li>
            </ul>
            <form class="d-flex">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-outline-dark" type="submit">Search</button>
            </form>
          </div>
        </div>
      </nav>

      <div class="container-fluid bg-light text-dark" style="height: 100vh">

        <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="assets/Carousel 1.jpg" class="d-block w-100" alt="library image 1" style="height: 400px">
            </div>
            <div class="carousel-item">
              <img src="assets/Carousel 2.jpg" class="d-block w-100" alt="library image 2" style="height: 400px">
            </div>
            <div class="carousel-item">
              <img src="assets/Carousel 3.jpg" class="d-block w-100" alt="library image 3" style="height: 400px">
            </div>
          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>

        <div class="row text-center align-items-center mt-4">
          <div class="col-12">
            <img src="assets/pic_1-removebg-preview.png" width="100" height="100"/>
            <h2 class="mt-2">Renita Sela Nainggolan</h2>
            <i>[210709021]</i>
          </div>
        </div>
        <div class="card text-center text-dark mt-4">
          <div class="card-header"></div>
          <div class="card-body">
            <h5 class="card-title">Selamat datang di Perpustakaan Czennie💚✨</h5>
            <p class="card-text">"Menjelajahi dunia melalui halaman-halaman buku, di perpustakaan Czennie temukan pengetahuan yang tak terbatas."</p>
          </div>
          <div class="card-footer text-center">
            <h1 class="h1-footer"></h1>
            <p>Copyright © Renita Sela Nainggolan - 210709021</p>
          </div>
        </div>
      </div>   

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
