# conFusion
 
<!DOCTYPE html>
<html lang="en">

<head>
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
<link rel="stylesheet" href="node_modules/font-awesome/css/font-awesome.min.css">
    <link rel="stylesheet" href="node_modules/bootstrap-social/bootstrap-social.css">
	<meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta https-equiv="x-ua-compatible" content="ie=edge">
    <link rel="stylesheet" href="node_modules/bootstrap/dist/css/bootstrap.min.css">
    <link href="node_modules/bootstrap/dist/css/styles.css" rel="stylesheet">
        <link rel="stylesheet" href="node_modules/bootstrap/dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="node_modules/font-awesome/css/font-awesome.min.css">
    <link rel="stylesheet" href="node_modules/bootstrap-social/bootstrap-social.css">
    <link href="css/styles.css" rel="stylesheet">
    <title>Ristorante Con Fusion</title>
     <!-- Required meta tags always come first -->

</head>

<body>
        <nav class="navbar navbar-dark navbar-expand-sm  fixed-top">
        <div class="container">
                        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#Navbar">
                <span class="navbar-toggler-icon"></span>
            </button>
                       <a class="navbar-brand mr-auto" href="./index.html"><img src="img/logo.png" height="30" width="41"></a><b class="r1">Ristorante Con Fusion</b></a>
                                  <div class="collapse navbar-collapse" id="Navbar">
                
                <ul class="navbar-nav mr-auto">
             
                    <li class="nav-item active"><a class="nav-link" href="./index.html"><span class="fa fa-home fa-lg"></span> Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="./aboutus.html"><span class="fa fa-info fa-lg"></span> About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#"><span class="fa fa-list fa-lg"></span> Menu</a></li>
                    <li class="nav-item"><a class="nav-link" href="./contactus.html"><span class="fa fa-address-card fa-lg"></span> Contact</a></li>
                </ul>
                                <span class="navbar-text">
                    <a target="#myModal">
                            <button type="button" class="btn btn-default btn-md" id="myBtn"> <span class="fa fa-sign-in"></span> Login</a></button>
                     </span>            
        </div>
    </nav>

<div>
  <div>
    <div>
<div>
  <div>
    <div>
<div class="container">

  <!-- Trigger the modal with a button -->
  

  <!-- Modal -->
  <div class="modal fade" id="myModal" role="dialog">
    <div class="modal-dialog modal-lg">
    
      <!-- Modal content-->

                  <div class="modal-content">
                <div class="modal-header">
                    <h4 class="modal-title">Login </h4>
                    <button type="button" class="close" data-dismiss="modal">&times;</button>
                </div>
                <div class="modal-body">
                    <form>
                        <div class="form-row">
                            <div class="form-group col-sm-4">
                                    <label class="sr-only" for="exampleInputEmail3">Email address</label>
                                    <input type="email" class="form-control form-control-sm mr-1" id="exampleInputEmail3" placeholder="Enter email">
                            </div>
                            <div class="form-group col-sm-4">
                                <label class="sr-only" for="exampleInputPassword3">Password</label>
                                <input type="password" class="form-control form-control-sm mr-1" id="exampleInputPassword3" placeholder="Password">
                            </div>
                            <div class="col-sm-auto">
                                <div class="form-check">
                                    <input class="form-check-input" type="checkbox">
                                    <label class="form-check-label"> Remember me
                                    </label>
                                </div>
                            </div>
                        </div>
                        <div class="form-row">
                            <button type="button" class="btn btn-secondary btn-sm ml-auto" data-dismiss="modal">Cancel</button>
                            <button type="submit" class="btn btn-primary btn-sm ml-1">Sign in</button>        
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </div>
  </div> 
</div>

    </div>
  </div>
</div>
    <header class="jumbotron" >
        <div class="container">
            <div class="row row-header ">
                <div class="col-12 col-sm-6">
                    <h1>Ristorante con Fusion</h1>
                    <p>We take inspiration from the World's best cuisines, and create a unique fusion experience. Our lipsmacking creations will tickle your culinary senses!</p>
                </div>

                
                <div class="col-12 col-sm-3 align-self-center">
                    <img src="img/logo.png" class="img-fluid">
                
                </div>

<div>
  <div>
    <div >
<div class="container">

  <!-- Trigger the modal with a button -->
  <button type="button" class="btn btn-lg nav-link btn-warning" id="resBtn">  Reserve a Table</a></button>

  <div id="resModal" class="modal fade" role="dialog">
        <div class="modal-dialog modal-lg" role="content">
            <!-- Modal content-->
            <div class="modal-content" style="color:black">
                <div class="modal-header" >
                    <h4 class="modal-title">Reserve a Table </h4>
                    <button type="button" class="close" data-dismiss="modal">&times;</button>
                </div>
                                    

    <div id="scroll-target " >

        <div class=" position-static col-sm-12"  >

Number of Guests
<div  class="form-check form-check-inline offset-2">
  <input class="form-check-input" type="radio" name="inlineRadioOptions" id="inlineRadio1" value="option1">
  <label class="form-check-label" for="inlineRadio1">1</label>
</div>
<div class="form-check form-check-inline">
  <input class="form-check-input" type="radio" name="inlineRadioOptions" id="inlineRadio2" value="option2">
  <label class="form-check-label" for="inlineRadio2">2</label>
</div>
<div class="form-check form-check-inline">
  <input class="form-check-input" type="radio" name="inlineRadioOptions" id="inlineRadio3" value="option3">
  <label class="form-check-label" for="inlineRadio3">3 </label>
</div>
<div class="form-check form-check-inline">
  <input class="form-check-input" type="radio" name="inlineRadioOptions" id="inlineRadio3" value="option3">
  <label class="form-check-label" for="inlineRadio4">4 </label>
</div>
<div class="form-check form-check-inline">
  <input class="form-check-input" type="radio" name="inlineRadioOptions" id="inlineRadio3" value="option3">
  <label class="form-check-label" for="inlineRadio5">5 </label>
</div>
<div class="form-check form-check-inline">
  <input class="form-check-input" type="radio" name="inlineRadioOptions" id="inlineRadio3" value="option3">
  <label class="form-check-label" for="inlineRadio6">6 </label>
</div>

</div>
</div>


<br>





<form>
  <br>
<p id="tt">Section</p>
  <div class="form-row " id="dd">


     <button type="button" class="btn btn-danger ">Smoking</button>
    
    
      <button type="button" class="btn btn-success">Non-Smoking</button>
   
  </div>
</form>



<form>
  <br><p id="tt">Date and <br>Time</p>
  <div class="form-row justify-content-center">
  
    <div class="col-sm-4 ">
      <input type="text" class="form-control" placeholder="Date">
    </div>
    <div class="col-sm-4 ">
      <input type="text" class="form-control" placeholder="Time">
    </div>
  </div>
</form>
<br><br>
<div class="col-sm-16 offset-3 ">
<button type="button" class="btn btn-primary btn-sm">Reserve</button>
<br><br>
</div>


    </div>      </div>
            </div>
        
    </div>
                 
        </div>
    </div>
  </div> 
</div>

    </div>
  </div>
</div>

            </div>
        </div>
    </header>

    <div class="container">


       <div class="row row-content">
            <div class="col">
            
            <div id="mycarousel" class="carousel slide" data-ride="carousel">
                    <div class="carousel-inner" role="listbox">
                        <div class="carousel-item active">


                            <img class="d-block img-fluid"
                                src="img/uthappizza.png" alt="Uthappizza">
                            <div class="carousel-caption d-none d-md-block">
                                <h2 >Uthappizza <span class="badge badge-danger">HOT</span> <span class="badge badge-pill badge-secondary">$4.99</span></h2>
                        <p class="d-none d-sm-block" f>A unique combination of Indian Uthappam (pancake) and
                            Italian pizza, topped with Cerignola olives, ripe vine
                            cherry tomatoes, Vidalia onion, Guntur chillies and
                            Buffalo Paneer.</p>
                            </div>
                        </div>



                        <div class="carousel-item">

                            <img class="d-block img-fluid"
                                src="img/buffet.png" alt="Grand Buffet">
                            <div class="carousel-caption d-none d-md-block">
                                <h2>Weekend Grand Buffet  <span class="badge badge-danger">NEW</span><span class="badge badge-pill badge-secondary">$4.99</span></h2>
                        
                        <p class="d-none d-sm-block" f>Featuring mouthwatering combinations with a choice of five different salads, six enticing appetizers, six main entrees and five choicest desserts. Free flowing bubbly and soft drinks. All for just $19.99 per person </p>
                            </div>
                        </div>



                        <div class="carousel-item">

                            <img class="d-block img-fluid"
                                src="img/alberto.png" alt="Alberto Somayya">
                            <div class="carousel-caption d-none d-md-block">
                                <h2 >Alberto Somayya</h2>
                        
                        <p class="d-none d-sm-block" f>A unique combination of Indian Uthappam (pancake) and
                            Italian pizza, topped with Cerignola olives, ripe vine
                            cherry tomatoes, Vidalia onion, Guntur chillies and
                            Buffalo Paneer. </p>

                        </div>



                    </div>
                                        <a class="carousel-control-prev" href="#mycarousel" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon"></span>
                    </a>
                    <a class="carousel-control-next" href="#mycarousel" role="button" data-slide="next">
                        <span class="carousel-control-next-icon"></span>
                    </a>
                        <button class="btn btn-danger btn-sm" id="carouselButton">
                        <span id="carousel-button-icon" class="fa fa-pause"></span>
                    </button>
            </div>


            </div>
        </div>



        <div class="row row-content align-items-center">
            <div class="col-12 col-sm-4 order-sm-first col-md-3">
                <h3>Our Lipsmacking Culinary Creations</h3>
            </div>
            <div class="col col-sm order-sm-last col-md">
                
                                <div class="media">
                    <img class="d-flex mr-3 img-thumbnail align-self-center"
                            src="img/uthappizza.png" alt="Uthappizza">
                    <div class="media-body">
                        <h2 class="mt-0">Uthappizza <span class="badge badge-danger">HOT</span> <span class="badge badge-pill badge-secondary">$4.99</span></h2>
                        <p class="d-none d-sm-block">Award winning three-star Michelin chef with wide
                            International experience having worked closely with
                            whos-who in the culinary world, he specializes in
                            creating mouthwatering Indo-Italian fusion experiences.</p>
                    </div>
                </div>
            </div>
        </div>


        <div class="row row-content align-items-center">
            <div class="col-12 col-sm-4 order-sm-last col-md-3">
                <h3>This Month's Promotions</h3>
            </div>
            <div class="col col-sm order-sm-first col-md">
                
					<div class="media">
                    <img class="d-flex mr-3 img-thumbnail align-self-center"
                            src="img/buffet.png" alt="Grand Buffet">
                    <div class="media-body">
                        <h2 class="mt-0">Weekend Grand Buffet  <span class="badge badge-danger">NEW</span></h2>
                        
                        <p class="d-none d-sm-block">Featuring mouthwatering combinations with a choice of five different salads, six enticing appetizers, six main entrees and five choicest desserts. Free flowing bubbly and soft drinks. All for just $19.99 per person </p>
          
                    </div>
                </div>



            </div>
        </div>


 </div>
				

  

    <footer class="footer">
        <div class="container">
            <div class="row ">             
                <div class="col-4 offset-1 col-sm-2">
                    <h5>Links</h5>
                    <ul class="list-unstyled">
                        <li><a href="#">Home</a></li>
                        <li><a href="./aboutus.html">About</a></li>
                        <li><a href="#">Menu</a></li>
                        <li><a href="#">Contact</a></li>
                    </ul>
                </div>
                <div  class="col-7 col-sm-5">
                    <h5>Our Address</h5>
                    <address>
		              121, Clear Water Bay Road<br>
		              Clear Water Bay, Kowloon<br>
		              HONG KONG<br>
                      <i class="fa fa-phone fa-lg"></i>: +852 1234 5678<br>
                      <i class="fa fa-fax fa-lg"></i>: +852 8765 4321<br>
                      <i class="fa fa-envelope fa-lg"></i>: 
                      <a href="mailto:confusion@food.net">confusion@food.net</a>
		           </address>

                    </div>
                                        <div class="text-center">
                        <a class="btn btn-social-icon btn-google" href="https://google.com/+"><i class="fa fa-google-plus"></i></a>
                        <a class="btn btn-social-icon btn-facebook" href="https://www.facebook.com/profile.php?id="><i class="fa fa-facebook"></i></a>
                        <a class="btn btn-social-icon btn-linkedin" href="https://www.linkedin.com/in/"><i class="fa fa-linkedin"></i></a>
                        <a class="btn btn-social-icon btn-twitter" href="https://twitter.com/"><i class="fa fa-twitter"></i></a>
                        <a class="btn btn-social-icon btn-google" href="https://youtube.com/"><i class="fa fa-youtube"></i></a>
                        <a class="btn btn-social-icon" href="mailto:"><i class="fa fa-envelope-o"></i></a>
                    </div>
                </div>
           </div>
           <div class="col-auto ">             
                <div class="row justify-content-center">
                    <p>© Copyright 2018 Ristorante Con Fusion</p>
                </div>
           </div>
        </div>
    </footer>
    <script src="node_modules/jquery/dist/jquery.slim.min.js"></script>
    <script src="node_modules/popper.js/dist/umd/popper.min.js"></script>
    <script src="node_modules/bootstrap/dist/js/bootstrap.min.js"></script>
        <script>
        $(document).ready(function(){
            $('[data-toggle="tooltip"]').tooltip();
        });
    </script>  <script>
                  $("#carouselButton").click(function(){
                if ($("#carouselButton").children("span").hasClass('fa-pause')) {
                    $("#mycarousel").carousel('pause');
                    $("#carouselButton").children("span").removeClass('fa-pause');
                    $("#carouselButton").children("span").addClass('fa-play');
                }
                else if ($("#carouselButton").children("span").hasClass('fa-play')){
                    $("#mycarousel").carousel('cycle');
                    $("#carouselButton").children("span").removeClass('fa-play');
                    $("#carouselButton").children("span").addClass('fa-pause');                    
                }
            });
    </script>
    <script>
$(document).ready(function(){
  $("#myBtn").click(function(){
    $("#myModal").modal();
  });
});
</script>
<script>
$(document).ready(function(){
  $("#resBtn").click(function(){
    $("#resModal").modal();
  });
});
</script>
    <script src="js/scripts.js"></script>
       <script src="node_modules/jquery/dist/jquery.slim.min.js"></script>
    <script src="node_modules/popper.js/dist/umd/popper.min.js"></script>
    <script src="node_modules/bootstrap/dist/js/bootstrap.min.js"></script>
    <script src="js/scripts.js"></script>
</body>

</html>
