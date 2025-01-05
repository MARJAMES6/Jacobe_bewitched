<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bewitched - Shop the Best Sets</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link href='https://fonts.googleapis.com/css?family=Arsenal SC' rel='stylesheet'>
    <style>
        body {
            background-color: #f8f9fa;
        }

        .heading {
            font-family: 'Arsenal SC', sans-serif;
            font-size: 30px;
            text-align: center;
        }

        .navbar-brand {
            font-family: 'Arsenal SC', sans-serif;
            font-size: 24px;
        }

        .navbar-nav .nav-link:hover {
            color: #343a40;
        }

        .card {
            border: none;
            border-radius: 10px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        }

        .card-body {
            background-color: #ffffff;
            padding: 20px;
        }

        .card-title {
            font-family: 'Arsenal SC', sans-serif;
            font-size: 22px;
        }

        .card-text {
            font-size: 14px;
            color: #666;
            line-height: 1.6;
        }

        .btn-primary {
            background-color: #6f42c1;
            border: none;
        }

        .btn-primary:hover {
            background-color: #5a32a3;
        }

        .carousel-item img {
            height: 500px;
            object-fit: cover;
        }

        .carousel-control-prev-icon, .carousel-control-next-icon {
            background-color: #000;
        }

        .carousel-caption-custom {
            position: absolute;
            top: 20px;
            left: 20px;
            color: white;
            font-family: 'Arsenal SC', sans-serif;
            z-index: 10;
        }

        .carousel-caption-custom h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        .carousel-caption-custom p {
            font-size: 0.9rem; 
            font-family: Arial, sans-serif; 
            max-width: 400px;
        }

        .card-columns {
            column-count: 3;
            column-gap: 30px;
        }

        @media (max-width: 768px) {
            .card-columns {
                column-count: 1;
            }

            .carousel-item img {
                height: 300px;
            }
        }
    </style>
</head>
<body>

<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Bewitched</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">More</a>
        </li>
      </ul>
    </div>
  </div>
</nav>


<div id="carouselExample" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://flowerknows.co/cdn/shop/files/4961836a8d44152d2dc59597c61c3e56.jpg?v=1733644395&width=1800" class="d-block w-100" alt="...">
      <div class="carousel-caption-custom">
        <h1>Bewitched</h1>
        <p>is a joint brand of 'FlowerKnows.' We sell makeup that is not only beautifully packaged but also reasonably priced and long-lasting, making it ideal for students to purchase. It is essentially less expensive than FlowerKnows.</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="https://flowerknows.co/cdn/shop/files/20241210-100044_412493d6-f0ad-41db-be2f-166bb87148d6.jpg?v=1733881397&width=3840" class="d-block w-100" alt="...">
      <div class="carousel-caption-custom">
        <h1>Bewitched</h1>
        <p>is a collaborative brand of 'FlowerKnows.' We offer makeup with not only attractive packaging, but also affordable and long-lasting, making it perfect for students to buy.</p>
        <button class="btn btn-primary" onclick="window.open('https://www.youtube.com/watch?v=uxSDGrXJ9Nk', '_blank')">Watch Video</button>
      </div>
     
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
<div class="container my-5">
    <div class="card-columns">
        <div class="card">
            <img src="https://flowerknows.co/cdn/shop/files/1_401f4b83-3e4d-4791-975b-7d2df01f320a.jpg?v=1735282116&width=416" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">Strawberries & sunshine palette</h5>
                <p class="card-text">Pigmented, fitted to every skintone, most importantly, strawberry scented.</p>
                <button class="btn btn-primary" onclick="showToast('Bought!')">Buy for $25</button>
            </div>
        </div>
        <div class="card">
            <img src="https://flowerknows.co/cdn/shop/files/01_83bc679e-dcfd-4f8a-9a4f-f79c9c9c73e7.jpg?v=1735280410&width=1100" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">Strawberries & sunshine lip gloss</h5>
                <p class="card-text">Kissable and fragnant lips. Stay hydrated with this lip gloss.</p>
                <button class="btn btn-primary" onclick="showToast('Bought!')">Buy for $15</button>
            </div>
        </div>
        <div class="card">
            <img src="https://flowerknows.co/cdn/shop/products/01_cc3d9407-584c-479b-9fca-d24ef8bf9246.jpg?v=1668506648&width=1500" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">Strawberries & Sunshine Powder Blush</h5>
                <p class="card-text">A glossy finish you can shine with.</p>
                <button class="btn btn-primary" onclick="showToast('Bought!')">Buy for $20</button>
            </div>
        </div>
    </div>
</div>

<div class="container my-5">
    <div class="card-columns">
        <div class="card">
            <img src="https://flowerknows.co/cdn/shop/files/01_f23607ec-f505-47df-83f6-0fb9db9ef0e9.jpg?v=1723463588&width=1100" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">Lily of the valley concealer</h5>
                <p class="card-text">Medium to light coverage and unscented.</p>
                <button class="btn btn-primary" onclick="showToast('Bought!')">Buy for $30</button>
            </div>
        </div>
        <div class="card">
            <img src="https://flowerknows.co/cdn/shop/files/95f0459d796b07dd7f90887e71fb1d3c.jpg?v=1723464200&width=1100" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">Chocolate wonderland contour + highlighter palette</h5>
                <p class="card-text">Non-ashy and easy to blend</p>
                <button class="btn btn-primary" onclick="showToast('Bought!')">Buy for $35</button>
            </div>
        </div>
        <div class="card">
            <img src="https://flowerknows.co/cdn/shop/files/1_991e400b-46e4-420b-a6be-eabf4555417f.jpg?v=1717051285&width=1100" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">White Swan loose powder</h5>
                <p class="card-text">Keep your makeup matte and last for 24 hrs.</p>
                <button class="btn btn-primary" onclick="showToast('Bought!')">Buy for $20</button>
            </div>
        </div>
    </div>
</div>

<div class="container my-5">
    <div class="card-columns">
        <div class="card">
            <img src="https://flowerknows.co/cdn/shop/files/1_364af6f5-e318-47be-a6a7-3ede4ed12535.jpg?v=1722858083&width=535" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">Ribbon Princess Lipstick</h5>
                <p class="card-text">Glossy finish and transferproof.</p>
                <button class="btn btn-primary" onclick="showToast('Bought!')">Buy for $12</button>
            </div>
        </div>
        <div class="card">
            <img src="https://flowerknows.co/cdn/shop/files/1c192ebd3ba04255fa71c7a8dc360984_6b9b89d7-f904-4cc5-90ad-61c54353aeff.jpg?v=1717644950&width=535" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">Bewitched's special primer</h5>
                <p class="card-text">Sticky and makes makeup long-lasting.</p>
                <button class="btn btn-primary" onclick="showToast('Bought!')">Buy for $35</button>
            </div>
        </div>
        <div class="card">
            <img src="https://flowerknows.co/cdn/shop/files/01_f510b89a-b71e-4b98-bd84-c601145e436b.jpg?v=1735279054&width=535" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">Sweetheart's liquid blush</h5>
                <p class="card-text">Edible, easy to blend with glowy finish.</p>
                <button class="btn btn-primary" onclick="showToast('Bought!')">Buy for $20</button>
            </div>
        </div>
    </div>
</div>


<div class="toast-container position-fixed top-0 end-0 p-3">
  <div id="toast" class="toast" role="alert" aria-live="assertive" aria-atomic="true">
    <div class="toast-header">
      <strong class="me-auto">Bewitched</strong>
      <button type="button" class="btn-close" data-bs-dismiss="toast" aria-label="Close"></button>
    </div>
    <div class="toast-body">
      Bought!
    </div>
  </div>
</div>

<script>
 function showToast(message) {
    const toastElement = document.getElementById('toast');
    const toastBody = toastElement.querySelector('.toast-body');
    toastBody.innerHTML = message;
    const toast = new bootstrap.Toast(toastElement);
    toast.show();
}

</script>




<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>

</body>
</html>
