<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
  </head>
  <body>

   <nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">stickr.ly</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Items</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Dropdown
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>
        
      </ul>
      <form class="d-flex" role="search">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form>
    </div>
  </div>
</nav>

<!-- crousel strats  -->
<div id="carouselExample" class="carousel slide">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://v3img.voot.com/v3Storage/assets/harry_potter_16x91-1684074010341.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://upload.wikimedia.org/wikipedia/commons/3/38/Stranger_Things_logo.png" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://media.licdn.com/dms/image/C5112AQHzEL6X_ullvA/article-cover_image-shrink_600_2000/0/1520196017902?e=2147483647&v=beta&t=QFxOQsoI6TxgVwsEURU-5kP-wymAweCGRxm_Kq0QFaI" class="d-block w-100" alt="...">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>








<div class="container-fluid">
  <h1 class="m-auto text-center fs-1 fw-bolder">stickers</h1>
  <div class="maindiv d-flex justify-content-evenly mt-5">
    <div class="card" style="width: 18rem;">
      <img src="https://v3img.voot.com/v3Storage/assets/harry_potter_16x91-1684074010341.jpg" class="card-img-top" alt="harry potter ">
      <div class="card-body">
        <h5 class="card-title">Harry potter</h5>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
        <a href="#" class="btn btn-primary">Add to Cart</a>
      </div>
    </div>

    <div class="card" style="width: 18rem;">
      <img src="https://upload.wikimedia.org/wikipedia/commons/3/38/Stranger_Things_logo.png" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Stranger things</h5>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
        <a href="#" class="btn btn-primary">Add To Cart</a>
      </div>
    </div>

    <div class="card" style="width: 18rem;">
      <img src="https://media.licdn.com/dms/image/C5112AQHzEL6X_ullvA/article-cover_image-shrink_600_2000/0/1520196017902?e=2147483647&v=beta&t=QFxOQsoI6TxgVwsEURU-5kP-wymAweCGRxm_Kq0QFaI" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Tom And Jerry</h5>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
        <a href="#" class="btn btn-primary">Add To Cart</a>
      </div>
    </div>

  </div>
</div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
  </body>
</html>
  
