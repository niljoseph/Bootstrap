<!DOCTYPE html>
<html lang="en">
<head>
       <title>Bootstrap Example</title>
       <link rel="stylesheet" href="asset/css/bootstrap.css">
       <link rel="stylesheet" href="asset/css/style.css">
       <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>



        
</head>
<body>
  <header>
     <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
    <!-- First half, 50% width -->
    <div class="navbar-collapse col-6 pd">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link font-weight-bold" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link font-weight-bold" href="#">About</a>
        </li>
      </ul>
    </div>
    
    <!-- Second half, 50% width -->
    <div class="navbar-collapse col-6 ">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link font-weight-bold" href="#">Services</a>
        </li>
        <li class="nav-item">
          <a class="nav-link font-weight-bold" href="#">Contact</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
   </header>    
 <div id="carouselExample" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="D:/ICT/Sample 2/Resource/shooter.jpg" class="d-block w-100" alt="First Slide">
      <div class="carousel-caption">
        <h1 class="height-6 text-warning">⚠️DANGER ZONE AHEAD⚠️</h1>
      </div>
      <div class="carousel-caption">
        <p class="text-center height-3 text-uppercase font-weight-bold font black"><br>
        Please proceed with caution! You are about to enter a section of our website where important and potentially irreversible actions can be taken. Make sure you are aware of the consequences before proceeding.</p>      
      </div>

    </div>
    <div class="carousel-item">
      <img src="D:/ICT/Sample 2/Resource/banner 2.jpg" class="d-block w-100" alt="Second Slide">
      <div class="carousel-caption">
        <p class="text-center w-50 height-4 text-uppercase font-weight-bold black">⚡️ Remember:<br>
          - Changes made here may affect your account settings.
          <br>- Deleting data or files cannot be undone.
          <br>- Be cautious with sensitive information.

          <br> If you are unsure or have any concerns, contact our support team before making any decisions. Your safety and security are our top priorities.

          <br> Proceed carefully or [return to the homepage].</p>
      </div>
    </div>
    <div class="carousel-item ">
      <img src="D:/ICT/Sample 2/Resource/banner-1.jpg" class="d-block w-100" alt="Third Slide">
      <div class="carousel-caption">
        <input class="input" type="text" name="Input">
        <br>
        <br>
        <input class="input" type="text" name="Input">
        <br>
        <p class=" btn text-center height-5 text-uppercase font-weight-bold black font-1" href="">Log in</p>
      </div>
        <div class="carousel-caption">
        <p class="text-center height-3 text-uppercase font-weight-bold font-1 black">By continuing, you acknowledge the risks involved.</p>
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
<footer class="bg-dark text-light py-3">
  <div class="container">
    <div class="width-5">
      <form>
  <div class="form-group row">
    <label for="inputEmail3" class="col-sm-2 col-form-label">Email</label>
    <div class="col-sm-10 ">
      <input type="email" class="form-control" id="inputEmail3" placeholder="Email">
    </div>
  </div>
  <div class="form-group row">
    <div class="col-sm-10 offset-sm-2 ">
      <button type="submit" class="btn btn-primary">Sign in</button>
    </div>
  </div>  
</form>
    </div>
   <!--  <div class="row align-items-center">
      <div class="col-lg-6 text-center text-lg-start ">
        <br>
        <br>
        <br>
        <br>
        <p class="alignment-1 pd-2">&copy; 2023 Group 6. All rights reserved.</p>
      </div> -->
      <div class="col align-items-center pd-3 pd-4">
      <div class="col-lg-6 text-center text-lg-end  ">
        <ul class="list-inline mb-0">
          <li class="list-inline-item me-3">
            <a href="https://www.facebook.com/" class="text-light">
              <img src="D:/ICT/Sample 2/Resource/facebook-1.webp" class="rounded" alt="Facebook" height="35">
            </a>
          </li>
          <li class="list-inline-item me-3">
            <a href="https://twitter.com/" class="text-light">
              <img src="D:/ICT/Sample 2/Resource/x.webp" class="rounded" alt="Twitter" height="35">
            </a>
          </li>
          <li class="list-inline-item">
            <a href="https://discord.com/" class="text-light">
              <img src="D:/ICT/Sample 2/Resource/discord.png" class="rounded" alt="discord" height="35">
            </a>
          </li>
          <!-- Add more app links with logos as needed -->
        </ul>
      </div>
      </div>
    </div>
  </div>
</footer>



</body>
</html>
