<!DOCTYPE html>
<html>
<head>
    <!-- Required meta tags always come first -->
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

     <!-- build:css css/main.css -->
     <link rel="stylesheet" href="node_modules/bootstrap/dist/css/bootstrap.min.css" />
     <link rel="stylesheet" href="node_modules/font-awesome/css/font-awesome.min.css" />
     <link rel="stylesheet" href="node_modules/bootstrap-social/bootstrap-social.css" />
     <link rel="stylesheet" href="css/NGB.css"/>
     <!-- endbuild -->
     <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lobster|Open+Sans" />
    
    <title>Naturally Glow'n Beauty</title>
</head>
<body>
    <header class="jumbotron jumbotron-fluid">
        <div class="container">
            <div class="row">
                <div class="col-4 col-sm-3 col-md-2 align-self-center">
                 <img src="img/ngb.jpg" class="img-fluid"/>   
                </div>
                <div class="col">
                    <h1>Naturally Glow'n Beauty</h1>
                    <h2>Natural Love, Natural Beauty</h2>
                </div>
            </div>
        </div>
    </header>

    <nav class="navbar navbar-expand-sm navbar-dark sticky-top">
        <div class="container">
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#naturallyNavbar">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="naturallyNavbar">
                <ul class="navbar-nav">
                    <li class="nav-item active"><a class="nav-link" href="#"><i class="fa fa-home fa-lg"></i>Home</a></li>
                    <li class="nav-item"><a  class="nav-link" href="Naturally_Glow'n_Beauty_Products.html"><i class="fa fa-product-hunt"></i>Products</a></li>
                    <li class="nav-item"><a  class="nav-link" href="Naturally_Glow'n_Beauty_Aboutus.html"><i class="fa fa-info fa-lg"></i>About Us</a></li>
                    <li class="nav-item"><a  class="nav-link" href="Naturally_Glow'n_Beauty_Contactus.html"><i class="fa fa-address-card fa-lg"></i>Contact Us</a></li>
                </ul>
                <span class="navbar-text ml-auto">
                    <a role="button" data-toggle="modal" data-target="#shoppingModal">
                        <i class="fa fa-shopping-cart"></i>
                    </a>
                </span>
                </div>
         </div>
    </nav>

<div class="container">
    <div class="col-md8 mx-auto">
        <div id="homeCarousel" class="carousel slide" data-ride="carousel">
            <ol class="carousel-indicators">
                <li data-target="#homeCarousel" data-slide-to="0" class="active"></li>
                <li data-target="#homeCarousel" data-slide-to="1"></li>
                <li data-target="#homeCarousel" data-slide-to="2"></li>
                <li data-target="#homeCarousel" data-slide-to="3"></li>
            </ol>
           <div class="carousel-inner">
               <div class="carousel-item active">
                   <img class="d-block w-100" src="img/feeling-beautiful2.jpg" alt="Beautiful Black Woman">
                    <div class="carousel-caption">
                        <h3>Go Back To Being Natural</h3>
                        <p class="d-none d-sm-block">All natural ingredents hand picked by the owner to give your skin a new, healthy glow</p>

                    </div>
               </div>
               <div class="carousel-item">
                 <img class="d-block w-100" src="img/citris-bath.jpg" alt="Lady in a bath of oranges">
                 <div class="carousel-caption">
                    <h3>Know what is in your Products</h3>
                    <p class="d-none d-sm-block">Everything on this site is handmade, with ingredents you can read </p>

                </div>
            </div>
            <div class="carousel-item">
                  <img class="d-block w-100" src="img/flower-crown.jpg" alt="Woman with crown made of flowers">
                  <div class="carousel-caption">
                    <h3>Feel Beautiful</h3>
                    <p class="d-none d-sm-block">Treat your skin to our healthy, cruelty free products. Suitable for everyone in the family </p>

                </div>
            </div>
            <div class="carousel-item">
                   <img class="d-block w-100" src="img/woodentable.jpg" alt="wooden table with ingredents on it">
                   <div class="carousel-caption">
                    <h3>Go Back To Being Natural</h3>
                    <p class="d-none d-sm-block">All natural ingredents hand picked by the owner to give your skin a new, healthy glow</p>

                </div>
            </div>
           </div> 
        </div>
    </div>
</div>

    <footer>
        <div class="container">
            <div class="row">
                <div class="col-4 col-sm-2 offset-1">
                    <h5>Links</h5>
                    <ul class="list-unstyled">
                        <li><a href="Naturally_Glow'n_Beauty.html">Home</a></li>
                        <li><a href="Naturally_Glow'n_Beauty_Products.html">Products</a></li>
                        <li><a href="Naturally_Glow'n_Beauty_Aboutus.html">About us</a></li>
                        <li><a href="Naturally_Glow'n_Beauty_Contactus.html">Contact us</a></li>
                    </ul>
                  </div>
                 <div class="col-6 col-sm-5 text-center">
                     <h5>Social</h5>
                     <a href="http://instagram.com/"><i class="fa fa-instagram"></i></a>
                </div>
                <div class="col-sm-4 text-center">
                    <i class="fa fa-phone fa-lg text-primary"></i> 1-206-555-1234<br />
                      <i class="fa fa-envelope fa-lg text-primary"></i> campsites@nucamp.co
                 </div>
            </div>
        </div>
    </footer>
    <!-- build:js js/main.js -->
    <script src="node_modules/jquery/dist/jquery.slim.min.js"></script>
    <script src="node_modules/popper.js/dist/umd/popper.min.js"></script>
    <script src="node_modules/bootstrap/dist/js/bootstrap.min.js"></script>
    <script src="js/scripts.js"></script>
    <!-- endbuild -->
 </body>
</html>
