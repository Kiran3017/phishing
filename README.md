<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>
    phishing Detector
  </title>
  <link rel="icon" href="static/assets/favicon.ico">
  <link rel= "stylesheet" type= "text/css" href= "static/css/style.css">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KK94CHFLLe+nY2dmCWGMq91rCGa5gtU4mk92HdvYe+M/SXH301p5ILy+dN9+nJOZ" crossorigin="anonymous">
  <script src="https://kit.fontawesome.com/4e1316e6bd.js" crossorigin="anonymous"></script>
</head>

<body>
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.12.9/dist/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>

    <section id="navbar">
        <nav class="navbar navbar-expand-lg navbar-light" style="background-color: #F1F6F9;">
          <a class="navbar-brand" href="#">
            <img src="static/assets/AA.png" width="30" height="30" class="d-inline-block align-top" alt="">
            Assemble
          </a>
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>

          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ml-auto">
              <li class="nav-item">
                <a class="nav-link" href="#Home">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#Model">Model</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#Contact">Contact</a>
              </li>

          </div>
        </nav>
      </section>


  <!-- Title -->
  <section id="Home" class="gradient-background">
    <div class="container col-xxl-8 px-4 py-5">
    <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
      <div class="col-10 col-sm-8 col-lg-6">
        <img src="static/assets/goal images/phishing_img.png" class="d-block mx-lg-auto img-fluid" alt="Bootstrap Themes" width="700" height="500" loading="lazy">
      </div>
      <div class="col-lg-6">
        <h1 class="display-5 fw-bold lh-1 mb-3">What are phishing attacks?</h1>
        <p class="lead">Phishing attacks are fraudulent emails, text messages, phone calls or websites designed  to manipulate people into downloading malware,
          sharing sensitive information (e.g., Social Security and credit card numbers, bank account numbers,
          login credentials), or taking other actions that expose themselves or their organizations to cybercrime. To know more about phishing attack follow this link <a href="https://www.youtube.com/watch?v=XBkzBrXlle0">phishing</a>
        </p>
        
      </div>
    </div>
  </div>
  </section>


  <!-- Features -->
  <section id="Model">
    <div class="container col-xl-10 col-xxl-8 px-4 py-5">
    <div class="row align-items-center g-lg-5 py-5">
      <div class="col-lg-7 text-center text-lg-start">
        <h1 class="display-4 fw-bold lh-1 mb-3">Which one is a phishing site?</h1>
        <p class="col-lg-10 fs-4">To check that the URL you have got is safe or not, you can use our machine learning model to check whether the URL is safe or not.</p>
      </div>
      <div class="col-md-10 mx-auto col-lg-5">
        <form class="p-4 p-md-5 border rounded-3 bg-light" action="/#Model" method="post">
          <div class="form-floating mb-3">
            <input type="text" class="form-control" name="url" placeholder="www.hello.com">
            <label for="url">URL</label>
          </div>
          <div class="checkbox mb-3">
            <label>
              <input type="checkbox" value="remember-me"> Remember me
            </label>
          </div>
          <button class="w-100 btn btn-lg btn-primary" type="submit">Check</button>
          <hr class="my-4">
          <small class="text-muted">Check the URL by clicking</small>
        </form>
      </div>
    </div>
  </div>
  </section>



  <!-- Footer -->
  <section id="Contact" class="gradient-background">
    <footer class="pt-4 mt-md-5 pt-md-5 border-top">
    <div class="row">
      <div class="col-12 col-md">
        <img class="mb-2" src="static/assets/AA.png" alt="" width="24" height="19">
        <small class="d-block mb-3 text-muted">© kotla kiran</small>
      </div>
      <div class="col-6 col-md">
        <h5>Contact us</h5>
        <ul class="list-unstyled text-small">
          <li class="mb-1">
            <i class="fa-brands fa-instagram" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="https://www.instagram.com/chimatashyam/">Instagram</a>
          </li>
          <li class="mb-1">
            <i class="fa-brands fa-linkedin" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="https://www.linkedin.com/in/chimata-shyam-5b6077270/">linkedin</a>
          </li>
          <li class="mb-1">
            <i class="fa-brands fa-twitter" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="https://twitter.com/chimatashyam123">Twitter</a></li>
        </ul>
      </div>
      <div class="col-6 col-md">
        <h5>Resources</h5>
        <ul class="list-unstyled text-small">
          <li class="mb-1"><i class="fa-solid fa-database" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="#">Kaggle dataset</a>
          </li>
          <li class="mb-1"><i class="fa-brands fa-youtube" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="#">Tarun tiwary</a>
          </li>
          <li class="mb-1"><i class="fa-brands fa-python" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="#">Python ML</a>
          </li>
        </ul>
      </div>
      <div class="col-6 col-md">
        <h5>Our Team</h5>
        <ul class="list-unstyled text-small">
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Rajkumar</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Kiran</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Rashmitha</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Harshitha</a></li>

        </ul>
      </div>
    </div>
  </footer>
  </section>
</body>

</html>


<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel= "stylesheet" type= "text/css" href= "static/css/style.css">
    <title>What site it is?</title><link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KK94CHFLLe+nY2dmCWGMq91rCGa5gtU4mk92HdvYe+M/SXH301p5ILy+dN9+nJOZ" crossorigin="anonymous">
    <script src="https://kit.fontawesome.com/4e1316e6bd.js" crossorigin="anonymous"></script>
  </head>
  <body>

  <section class="gradient-background">
       <div class="container col-xxl-8 px-4 py-5">
        <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
          <div class="col-10 col-sm-8 col-lg-6">
            <img src="static/assets/safe.png" class="d-block mx-lg-auto img-fluid" alt="Bootstrap Themes" width="700" height="500" loading="lazy">
          </div>
          <div class="col-lg-6">
            <h1 class="display-5 fw-bold lh-1 mb-3">It is a safe and secured website</h1>
            <p class="lead">It is a safe and secured website, you proceed to it. If you want to know more details about this website
            or the redirect links of it, please contact us on kirankotla2002@gmail.com</p>
          </div>
        </div>
      </div>
  </section>

    <section id="Contact">
    <footer class="pt-4 mt-md-5 pt-md-5 border-top">
    <div class="row">
      <div class="col-12 col-md">
        <img class="mb-2" src="static/assets/AA.png" alt="" width="24" height="19">
        <small class="d-block mb-3 text-muted">© Raj Kumar</small>
      </div>
      <div class="col-6 col-md">
        <h5>Contact us</h5>
        <ul class="list-unstyled text-small">
          <li class="mb-1">
            <i class="fa-brands fa-instagram" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="https://www.instagram.com/chimatashyam/">Instagram</a>
          </li>
          <li class="mb-1">
            <i class="fa-brands fa-linkedin" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="https://www.linkedin.com/in/chimata-shyam-5b6077270/">linkedin</a>
          </li>
          <li class="mb-1">
            <i class="fa-brands fa-twitter" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="https://twitter.com/chimatashyam123">Twitter</a></li>
        </ul>
      </div>
      <div class="col-6 col-md">
        <h5>Resources</h5>
        <ul class="list-unstyled text-small">
          <li class="mb-1"><i class="fa-solid fa-database" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="#">Kaggle dataset</a>
          </li>
          <li class="mb-1"><i class="fa-brands fa-youtube" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="#">Tarun tiwary</a>
          </li>
          <li class="mb-1"><i class="fa-brands fa-python" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="#">Python ML</a>
          </li>
        </ul>
      </div>
      <div class="col-6 col-md">
        <h5>Our Team</h5>
        <ul class="list-unstyled text-small">
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Rajkumar</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Kiran</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Rashmitha</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Harshitha</a></li>

        </ul>
      </div>
    </div>
  </footer>
  </section>

  </body>
</html>



<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel= "stylesheet" type= "text/css" href= "static/css/style.css">
    <title>What site it is?</title><link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KK94CHFLLe+nY2dmCWGMq91rCGa5gtU4mk92HdvYe+M/SXH301p5ILy+dN9+nJOZ" crossorigin="anonymous">
    <script src="https://kit.fontawesome.com/4e1316e6bd.js" crossorigin="anonymous"></script>
  </head>
  <body>

  <section class="gradient-background">
       <div class="container col-xxl-8 px-4 py-5">
        <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
          <div class="col-10 col-sm-8 col-lg-6">
            <img src="static/assets/bad.jpeg" class="d-block mx-lg-auto img-fluid" alt="Bootstrap Themes" width="700" height="500" loading="lazy">
          </div>
          <div class="col-lg-6">
            <h1 class="display-5 fw-bold lh-1 mb-3">It is not safe to browse</h1>
            <p class="lead">It is not a safe website, please avoid it. if you still want to browse through it go a head but, remember that you are not safe here.
                If you want to know more details about this website
            or the redirect links of it, please contact us on chimatashyam123@gmail.com</p>
          </div>
        </div>
      </div>
  </section>

    <section id="Contact">
    <footer class="pt-4 mt-md-5 pt-md-5 border-top">
    <div class="row">
      <div class="col-12 col-md">
        <img class="mb-2" src="static/assets/AA.png" alt="" width="24" height="19">
        <small class="d-block mb-3 text-muted">© chimata shyam</small>
      </div>
      <div class="col-6 col-md">
        <h5>Contact us</h5>
        <ul class="list-unstyled text-small">
          <li class="mb-1">
            <i class="fa-brands fa-instagram" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="https://www.instagram.com/chimatashyam/">Instagram</a>
          </li>
          <li class="mb-1">
            <i class="fa-brands fa-linkedin" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="https://www.linkedin.com/in/chimata-shyam-5b6077270/">linkedin</a>
          </li>
          <li class="mb-1">
            <i class="fa-brands fa-twitter" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="https://twitter.com/chimatashyam123">Twitter</a></li>
        </ul>
      </div>
      <div class="col-6 col-md">
        <h5>Resources</h5>
        <ul class="list-unstyled text-small">
          <li class="mb-1"><i class="fa-solid fa-database" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="#">Kaggle dataset</a>
          </li>
          <li class="mb-1"><i class="fa-brands fa-youtube" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="#">Tarun tiwary</a>
          </li>
          <li class="mb-1"><i class="fa-brands fa-python" style="color: #fcfcfc;"></i>
            <a class="link-secondary text-decoration-none" href="#">Python ML</a>
          </li>
        </ul>
      </div>
      <div class="col-6 col-md">
        <h5>Our Team</h5>
        <ul class="list-unstyled text-small">
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Shyam</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Rupendra</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Ramesh</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Yashwanth</a></li>

        </ul>
      </div>
    </div>
  </footer>
  </section>

  </body>
</html>
