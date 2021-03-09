<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>TinDog</title>
  <!-- Font Awesome -->
  <script src="https://kit.fontawesome.com/de860acf1a.js" crossorigin="anonymous"></script>
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@100;900&family=Ubuntu:wght@300&display=swap" rel="stylesheet"></head>
  <!-- /BootStrap -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-BmbxuPwQa2lc/FVzBcNJ7UAyJxM6wuqIj61tLrc4wSX0szH/Ev+nYRRuWlolflfl" crossorigin="anonymous">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/js/bootstrap.bundle.min.js" integrity="sha384-b5kHyXgcpbZJO/tY9Ul7kGkf1S0CWuKcCD38l8YkeH8z8QjE0GmW1gYU5S9FOnJ0" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.6.0/dist/umd/popper.min.js" integrity="sha384-KsvD1yqQ1/1+IA7gi3P0tyJcT3vR+NdBTt13hSJ2lnve8agRGXTTyNaBYmCR/Nwi" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/js/bootstrap.min.js" integrity="sha384-nsg8ua9HAw1y0W1btsyWgBklPnCUAFLuTMS2G72MMONqmOymq585AcH49TLBQObG" crossorigin="anonymous"></script>
  <!-- CSS Stylesheets -->
  <link rel="stylesheet" href="css/styles.css"></script>
<body>

  <section id="title">
    <div class="container-fluid">
    <!-- Nav Bar -->

    <nav class="navbar navbar-expand-lg navbar-dark">
        <a class="navbar-brand ps-3 ubuntuFont" href="">tindog</a>
         <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto">
            <li class="nav-item">
                <a class="nav-link headFont" href="">Contact</a>
            </li>
            <li class="nav-item">
                <a class="nav-link headFont" href="">Pricing</a>
            </li>
            <li class="nav-item">
                <a class="nav-link headFont" href="">Download</a>
            </li>
        </ul>
     </div>
    </nav>

    <br>
    <br>
    <br>
    <!-- Title -->
      <div class="row">
        <div class="col-lg-6">
          <h1>Meet new and interesting dogs nearby.</h1>
          <br>
          <br>
          <button class="btn btn-dark btn-lg" type="button"><i class="fab fa-apple"></i> Download</button>
          <button class="btn btn-outline-light btn-lg ms-3" type="button"><i class="fab fa-google-play"></i> Download</button>
          <br>
          <br>
        </div>
        <div class="col-lg-6">
          <img class="imgTitle" src="images/iphone6.png" alt="iphone-mockup">
        </div>
      </div>
  </section>
  <!-- Features -->

  <section id="features">
    <div class="row">
      <div class="col-lg-4 feature-box">
        <i class="fas fa-check-circle homeIcon"></i>
        <h3 class="">Easy to use.</h3>
        <p class="homePg">So easy to use, even your dog could do it.</p>
      </div>
      <div class="col-lg-4 feature-box">
        <i class="fas fa-bullseye homeIcon"></i>
        <h3 class="">Elite Clientele</h3>
        <p class="homePg">We have all the dogs, the greatest dogs.</p>
      </div>
      <div class="col-lg-4 feature-box">
        <i class="fas fa-heart homeIcon"></i>
        <h3 class="">Guaranteed to work.</h3>
        <p class="homePg">Find the love of your dog's life or your money back.</p>
      </div>
    </div>
  </section>


  <!-- Testimonials -->

  <section id="testimonials">

    <div id="testimonial-carousel" class="carousel slide" data-bs-pause="hover" data-bs-interval="3000" data-bs-ride="carousel">
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
      <a class="carousel-control-prev" role="button" data-bs-target="#testimonial-carousel"  data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </a>
      <a class="carousel-control-next" role="button" data-bs-target="#testimonial-carousel"  data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </a>
    </div>
  </section>


  <!-- Press -->

  <section id="press">
    <img class="press-logo" src="images/TechCrunch.png" alt="tc-logo">
    <img class="press-logo" src="images/tnw.png" alt="tnw-logo">
    <img class="press-logo" src="images/bizinsider.png" alt="biz-insider-logo">
    <img class="press-logo" src="images/mashable.png" alt="mashable-logo">

  </section>


  <!-- Pricing -->

  <section id="pricing">

    <h2>A Plan for Every Dog's Needs</h2>
    <p>Simple and affordable price plans for your and your dog.</p>

    <div class="row">
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
      <div class="pricing-column col-lg-4">
        <div class="card">
          <div class="card-header">
              <h3>Mastiff</h3>
          </div>
          <div class="card-body">
            <<h2>$99 / mo</h2>
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

    <div class="cta-container">
      <h3 class="cta-font py-3">Find the True Love of Your Dog's Life Today.</h3>
      <button class="btn btn-lg btn-block btn-dark me-3" type="button"><i class="fab fa-apple"></i> Download</button>
      <button class="btn btn-lg btn-block btn-outline-light ms-3" type="button"><i class="fab fa-google-play"></i> Download</button>
    </div>

  </section>


  <!-- Footer -->

  <footer id="footer">
    <div class="footer-container">
      <i class="fab fa-twitter me-4"></i>
      <i class="fab fa-facebook-f me-4"></i>
      <i class="fab fa-instagram me-2"></i>
      <i class="fas fa-envelope ms-2"></i>
      <p class="pt-3 text-black-50">© Copyright 2018 TinDog</p>
    </div>


  </footer>


</body>

</html>
