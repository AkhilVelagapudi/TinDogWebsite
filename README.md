# TinDogWebsite
Website for the fictional company "TinDog" using BootStrap
<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>TinDog</title>
  <!-- Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat&family=Staatliches&family=Titan+One&family=Ubuntu&display=swap" rel="stylesheet">
  <!-- CSS Stylsheets -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor" crossorigin="anonymous">
  <link rel="stylesheet" href="css/styles.css">
  <!-- FontAwesome -->
  <script src="https://kit.fontawesome.com/2f61c3e057.js" crossorigin="anonymous"></script>
  <!-- BootStrap -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.bundle.min.js" integrity="sha384-pprn3073KE6tl6bjs2QrFaJGz5/SUsLqktiwsUTF55Jfv3qYSDhgCecCxMW52nD2" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.5/dist/umd/popper.min.js" integrity="sha384-Xe+8cL9oJa6tN/veChSP7q+mnSPaj5Bcu9mPX5F5xIGE0DVittaqT5lorf0EI7Vk" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.min.js" integrity="sha384-kjU+l4N0Yf4ZOJErLsIcvOU2qSb74wXpOhqTvwVx3OElZRweTnQ6d31fXEoRD1Jy" crossorigin="anonymous"></script>
</head>

<body>

  <section id="title">

    <div class="container-fluid">

    <nav class="navbar navbar-expand-lg navbar-dark">

      <a class="navbar-brand" href="">tindog</a>

      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                  <a class="nav-link" href="#footer">Contact</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#pricing">Pricing</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#cta">Download</a>
                </li>
              </ul>
          </div>

    </nav>

    <div class= "row">

        <div class="col-lg-6">
          <h1>Meet new and interesting dogs nearby.</h1>
          <button type="button" class="btn btn-dark btn-lg download-button"><i class="fa-brands fa-apple"></i> Download</button>
          <button type="button" class="btn btn-light btn-lg download-button"><i class="fa-brands fa-google-play"></i> Download</button>
        </div>
        
        <div class="col-lg-6">
          <img src="images/iphone6.png" alt="iphone-mockup" class="title-image">
        </div>

    </div>

</div>
  </section>




  <!-- Features -->

  <section id="features">

  <div class="row">
    <div class= "feature-box col-lg-4">
      <i class="fa-solid fa-circle-check fa-4x icon"></i>
      <h3>Easy to use.</h3>
      <p>So easy to use, even your dog could do it.</p>
    </div>

    <div class= "feature-box col-lg-4">
      <i class="fa-solid fa-bullseye fa-4x icon"></i>
      <h3>Elite Clientele</h3>
      <p>We have all the dogs, the greatest dogs.</p>
    </div>

    <div class= "feature-box col-lg-4">
      <i class="fa-solid fa-heart fa-4x icon"></i>
      <h3>Guaranteed to work.</h3>
      <p>Find the love of your dog's life or your money back.</p>
    </div>
  </div>


  </section>


  <!-- Testimonials -->

  <section id="testimonials">

    <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <h2>I no longer have to sniff other dogs for love. I've found the hottest Corgi on TinDog. Woof.</h2>
      <img class="testimonial-image" src="images/dog-img.jpg" alt="dog-profile">
      <em>Pebbles, New York</em>
    </div>
    <div class="carousel-item">
      <h2 class="testimonial-text">My dog used to be so lonely, but with TinDog's help, they've found the love of their life. I think.</h2>
      <img class="testimonial-image" src="images/lady-img.jpg" alt="lady-profile">
      <em>Beverly, Illinois</em>
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



  </section>


  <!-- Press -->

  <section id="press">
    <img class="press-logo" src="images/techcrunch.png" alt="tc-logo">
    <img class="press-logo" src="images/tnw.png" alt="tnw-logo">
    <img class="press-logo" src="images/bizinsider.png" alt="biz-insider-logo">
    <img class="press-logo" src="images/mashable.png" alt="mashable-logo">

  </section>


  <!-- Pricing -->

  <section id="pricing">


    <h2>A Plan for Every Dog's Needs</h2>
    <p>Simple and affordable price plans for your and your dog.</p>

<div class="row text-center">
  <div class="pricing-column col-lg-4 col-md-6">
    <div class="card">
      <div class="card-header">
          <h3>Chihuahua</h3>
      </div>
      <div class="card-body">
        <h2>Free</h2>
        <p>5 Matches Per Day</p>
        <p>10 Messages Per Day</p>
        <p>Unlimited App Usage</p>
        <button class="btn btn-lg btn-block btn-outline-dark"type="button">Sign Up</button>
      </div>
    </div>
  </div>

<div class="pricing-column col-lg-4 col-md-6">
  <div class="card">
    <div class="card-header">
       <h3>Labrador</h3>
    </div>
    <div class="card-body">
      <h2>$49 / mo</h2>
      <p>Unlimited Matches</p>
      <p>Unlimited Messages</p>
      <p>Unlimited App Usage</p>
      <button class="btn btn-lg btn-block btn-dark" type="button">Sign Up</button>
    </div>
  </div>
</div>

<div class="pricing-column col-lg-4 ">
  <div class="card">
    <div class="card-header">
      <h3>Mastiff</h3>
    </div>
    <div class="card-body">
      <h2>$99 / mo</h2>
      <p>Pirority Listing</p>
      <p>Unlimited Matches</p>
      <p>Unlimited Messages</p>
      <p>Unlimited App Usage</p>
      <button class="btn btn-lg btn-block btn-dark" type="button">Sign Up</button>
    </div>
  </div>
</div>


</div>

  </section>


  <!-- Call to Action -->

  <section id="cta">

    <h3 class="cta-heading">Find the True Love of Your Dog's Life Today.</h3>
    <button class="download-button btn btn-lg btn-dark" type="button"><i class="fa-brands fa-apple"></i> Download</button>
    <button class="download-button btn btn-lg btn-light" type="button"><i class="fa-brands fa-google-play"></i> Download</button>

  </section>


  <!-- Footer -->

  <footer id="footer">

    <i class="social-icons fa-brands fa-facebook"></i>
    <i class="social-icons fa-brands fa-twitter"></i>
    <i class="social-icons fa-brands fa-instagram"></i>
    <i class="social-icons fa-solid fa-envelope"></i>
    <p>© Copyright TinDog</p>

  </footer>


</body>

</html>
