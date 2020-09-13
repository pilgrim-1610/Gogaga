<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
<title>Go Gaga</title>
<link rel="stylesheet" href="styles.css">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">
<script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/animejs/2.0.2/anime.min.js"></script>

</head>
<body>
  <nav class=" nav-menu float-right navbar navbar-dark navbar-expand-md fixed-top  ">
                          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#Navbar">
                 <span class="navbar-toggler-icon"></span>
             </button>
               <!--a class="navbar-brand" href="#"> <img src="logo.png" class="img-fluid" height="30"width="40">
               </a-->
               <div class="collapse navbar-collapse" id="Navbar">
                      <ul class="navbar-nav mr-auto nav nav-pills nav-stacked  " id="accordion" data-spy="affix" data-offset-top="605">
                        <li class="nav-item active btn"><a class="nav-link" href="#">Home</a></li>

                        <li class="nav-item  btn" >
                          <a class="nav-link" href="javascript:;" data-toggle="collapse" data-target="#demo1" data-parent="#accordion" style="margin-left: 0px; margin-top:">
                             Categories
                            <i class="fa fa-angle-down"></i>
                          </a>

                          <ul id="demo1" class="collapse">

                            <div class="dropdown">
    <li class="btn" type="button" id="dropdownMenuButton" data-toggle="dropdown"><a class="nav-link" href="#">
      Bags</a>
    </li>
                            <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
                              <a class="dropdown-item" href="Mosaic_clutches.html"style="color:black;">Mosaic Clutches</a>
                              <a class="dropdown-item" href="wooden_clutches.html"style="color:black;">Wooden Clutches</a>
                              <!--a class="dropdown-item" href="#">Wallet</a>
                              <a class="dropdown-item" href="#">Laptop</a>
                              <a class="dropdown-item" href="#">Pouches</a>
                              <a class="dropdown-item" href="#">Duffel</a>
                              <a class="dropdown-item" href="#">Clutches</a-->
                            </div>
                            </div>
                            <!--div class="dropdown">
                            <li class="btn nav-link " type="button" id="dropdownMenuButton" data-toggle="dropdown" ><a class="nav-link" href="#">Ethnic</a></li>
                            <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
                              <a class="dropdown-item" href="#">Kurtis</a>
                              <a class="dropdown-item" href="#">Crop tops</a>
                              <a class="dropdown-item" href="#">Skirts</a>
                              <a class="dropdown-item" href="#">Lucknowi gharana</a>
                              <a class="dropdown-item" href="#">Punjabi phulkaris</a>
                            </div>
                            </div>
                            <div class="dropdown">
                            <li class="btn nav-link " type="button" id="dropdownMenuButton" data-toggle="dropdown"><a class="nav-link" href="#">Jewellery</a></li>
                            <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
                              <a class="dropdown-item" href="#">Oxidised</a>
                              <a class="dropdown-item" href="#">Silver Lookalike</a>
                              <a class="dropdown-item" href="#">German Silver</a>
                              <a class="dropdown-item" href="#">Brass/Copper</a>
                              <a class="dropdown-item" href="#">Handmade Wonders</a>
                            </div>
                            </div>
                            <div class="dropdown">
                            <li class="btn nav-link " type="button" id="dropdownMenuButton" data-toggle="dropdown"><a class="nav-link" href="#"><a class="nav-link" href="#">Saree</a></li>
                            <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
                              <a class="dropdown-item" href="#">Handloom</a>
                              </div>
                            </div-->
                            <div class="dropdown">
                            <li class="btn  " type="button" id="dropdownMenuButton" data-toggle="dropdown"><a class="nav-link" href="#">Home Decor</a></li>
                            <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
                              <!--a class="dropdown-item" href="#">Quil Art</a-->
                              <a class="dropdown-item" href="Dokhra.html"style="color:black;">Dokra Artifacts</a>

                              </div>
                            </div>

                          </ul>
                        </li>


                        <li class="nav-item btn"><a class="nav-link" data-toggle="modal"data-target="#custom">Customize</a></li>

                        <li class="nav-item btn"><a class="nav-link" href="#contact">Contact</a></li>
                        <li class="nav-item btn"><a class="nav-link" href="#"><span class="fa fa-shopping-cart fa-lg"></span>
                        <!--li class="nav-item btn"><a class="nav-link" data-toggle="modal"data-target="#loginModal">Login<i class="fa fa-user"></i></a></li-->
                </ul>
            </div>
        </nav>
        <div id="custom" class="modal fade" role="dialog">
          <div class="modal-dialog modal-lg" role="content">
            <div class="modal-content">
              <div class="modal-header">
                <div class="modal-title">
                  <button type="button" class="close" data-dismiss="modal" aria-label="Close">
  <span aria-hidden="true">&times;</span>
  </button></div>
            </div>
              <div class="modal-body">
                <h4>COMING SOON</h4>
              </div>
            </div>
          </div>
        </div>
        <div id="loginModal" class="modal fade" role="dialog">
      <div class="modal-dialog modal-lg" role="content">
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
                        <a href="#">  <button type="submit" class="btn btn-primary btn-sm ml-1">Register</button></a>
                      </div>
                  </form>
              </div>
          </div>
      </div>
  </div>



<div  id="particles-js">
  <!--canvas class="particle-js-canvas-el"style="width:100%; height:100%;" width="428"height="778">

  <!--logo-->
<div id="home" class="intro route bg-image " style="background-image: url(logo.jpg); width:auto;">
</div>
</div>
<div class="container">
  <div class="row">
      <div style="text-align:center;"class="col-12"><h1 class="ml15">
  <span class="word">Categories</span>
</h1>
</div>
</div>


  <br>
  <div class="row">
    <div class="col-xs-12 col-sm-6 col-md-4">
    <div class="image-flip" >
        <div class="mainflip flip-0">
            <div class="frontside">
                <div class="card">
                    <div class="card-body text-center">
                        <p><img class=" img-fluid"style="border-radius:50%;" src="bags.jpg" alt="card image"></p>
                        <h4 class="card-title">Bags</h4>
                        <p class="card-text"></p>

                    </div>
                </div>
            </div>
            <div class="backside">
                <div class="card">
                    <div class="card-body text-center mt-4">
                        <h4 class="card-title">Bags</h4>
                        <p class="card-text"><strong>Browse through varieties of bags from our collection.</strong></p>
                        <ul class="list-inline">
                                <!--a href="#" class="btn btn-primary btn-sm"><i class="fa fa-shopping-cart"></i></a>
                                <li class="list-inline-item">
                            </li-->
                            <li class="list-inline-item">
                              <a href="#" class="btn btn-danger btn-lg">Visit</a>
                            </li>
                    </div>
                </div>
            </div>
        </div>
    </div>
    </div>
    <div class="col-xs-12 col-sm-6 col-md-4">
    <div class="image-flip" >
        <div class="mainflip flip-0">
            <div class="frontside">
                <div class="card">
                    <div class="card-body text-center">
                        <p><img class=" img-fluid"style="border-radius:50%;" src="img6.jpg" alt="card image"></p>
                        <h4 class="card-title">Home Decor</h4>
                        <p class="card-text"></p>

                    </div>
                </div>
            </div>
            <div class="backside">
                <div class="card">
                    <div class="card-body text-center mt-4">
                        <h4 class="card-title">Home decor</h4>
                        <p class="card-text"><strong>Browse through our  list of home decor items.</strong></p>
                        <ul class="list-inline">
                                <!--a href="#" class="btn btn-primary btn-sm"><i class="fa fa-shopping-cart"></i></a>
                                <li class="list-inline-item">
                            </li-->
                            <li class="list-inline-item">
                              <a href="#" class="btn btn-danger btn-lg">Visit</a>
                            </li>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

    <div class="col-xs-12 col-sm-6 col-md-4">
    <div class="image-flip" >
        <div class="mainflip flip-0">
            <div class="frontside">
                <div class="card">
                    <div class="card-body text-center">
                        <p><img class=" img-fluid" style="border-radius:50%;" src="ques.png" alt="card image"></p>
                        <h4 class="card-title">Coming soon
                      </h4>
                        <p class="card-text">Sit tight we are going gaga over introducing you to our new items.</p>

                    </div>
                </div>
            </div>
            <div class="backside">
                <div class="card">
                    <div class="card-body text-center mt-4">
                        <h4 class="card-title">Coming soon</h4>
                        <p class="card-text">Sit tight we are going gaga over introducing you to our new items.</p>
                        <ul class="list-inline">
                                <!--a href="#" class="btn btn-primary btn-sm"><i class="fa fa-shopping-cart"></i></a>
                                <li class="list-inline-item">
                            </li-->
                            <li class="list-inline-item">
                              <!--a href="#" class="btn btn-danger btn-lg">Visit</a-->
                            </li>
                    </div>
                </div>
            </div>
        </div>
    </div>
    </div>
    <div class="col-xs-12 col-sm-6 col-md-4">
    <div class="image-flip" >
        <div class="mainflip flip-0">
            <div class="frontside">
                <div class="card">
                    <div class="card-body text-center">
                        <p><img class=" img-fluid" style="border-radius:50%;" src="ques.png" alt="card image"></p>
                        <h4 class="card-title">Coming soon
                      </h4>
                        <p class="card-text">Sit tight we are going gaga over introducing you to our new items.</p>

                    </div>
                </div>
            </div>
            <div class="backside">
                <div class="card">
                    <div class="card-body text-center mt-4">
                        <h4 class="card-title">Coming soon</h4>
                        <p class="card-text">Sit tight we are going gaga over introducing you to our new items.</p>
                        <ul class="list-inline">
                                <!--a href="#" class="btn btn-primary btn-sm"><i class="fa fa-shopping-cart"></i></a>
                                <li class="list-inline-item">
                            </li-->
                            <li class="list-inline-item">
                            <!--a href="#" class="btn btn-danger btn-lg">Visit</a-->
                            </li>
                    </div>
                </div>
            </div>
        </div>
    </div>
    </div>
<div class="col-xs-12 col-sm-6 col-md-4">
<div class="image-flip" >
    <div class="mainflip flip-0">
        <div class="frontside">
            <div class="card">
                <div class="card-body text-center">
                    <p><img class=" img-fluid" style="border-radius:50%;" src="ques.png" alt="card image"></p>
                    <h4 class="card-title">Coming soon
                  </h4>
                    <p class="card-text">Sit tight we are going gaga over introducing you to our new items.</p>

                </div>
            </div>
        </div>
        <div class="backside">
            <div class="card">
                <div class="card-body text-center mt-4">
                    <h4 class="card-title">Coming soon</h4>
                    <p class="card-text">Sit tight we are going gaga over introducing you to our new items.</p>
                    <ul class="list-inline">
                            <!--a href="#" class="btn btn-primary btn-sm"><i class="fa fa-shopping-cart"></i></a>
                            <li class="list-inline-item">
                        </li-->
                        <li class="list-inline-item">
                          <!--a href="#" class="btn btn-danger btn-lg">Visit</a-->
                        </li>
                </div>
            </div>
        </div>
    </div>
</div>
</div>
<div class="col-xs-12 col-sm-6 col-md-4">
<div class="image-flip" >
  <div class="mainflip flip-0">
      <div class="frontside">
          <div class="card">
              <div class="card-body text-center">
                  <p><img class=" img-fluid" style="border-radius:50%;" src="ques.png" alt="card image"></p>
                  <h4 class="card-title">Coming soon
                </h4>
                  <p class="card-text">Sit tight we are going gaga over introducing you to our new items.</p>

              </div>
          </div>
      </div>
      <div class="backside">
          <div class="card">
              <div class="card-body text-center mt-4">
                  <h4 class="card-title">Coming soon</h4>
                  <p class="card-text">Sit tight we are going gaga over introducing you to our new items.</p>
                  <ul class="list-inline">
                          <!--a href="#" class="btn btn-primary btn-sm"><i class="fa fa-shopping-cart"></i></a>
                          <li class="list-inline-item">
                      </li-->
                      <li class="list-inline-item">
                        <!--a href="#" class="btn btn-danger btn-lg">Visit</a-->
                      </li>
              </div>
          </div>
      </div>
  </div>
</div>
</div>
</div>
</div>



<div class="d-flex">
<a href="#" class="mr-auto ml-1 mb-1 p-2 btn btn-danger btn-circle back-to-top"style="border-radius:50%;"><i class="fa fa-chevron-up"></i></a>
<button type="button" class=" p-2 mr-1 mb-1 btn btn-danger btn-circle "data-toggle="dropdown"style="border-radius:50%;"><i class="fa fa-share"></i>
</button>
<div class="dropdown-menu">
<ul>
  <li>
<a href="http://www.facebook.com/sharer.php?u=https://ggws-1d29a.web.app/" target="_blank">
    <div class="btn fa fa-facebook" alt="facebook" /></div>
</a>
</li>


<li>
 <input type="text" value="https://ggws-1d29a.web.app/" id="myInput">

<!-- The button used to copy the text -->
<i  class="fa fa-clipboard btn"onclick="myFunction()"></i>

</li>
</div>
</div>
<footer class="footer"id="contact">
  <div class="container ">
    <div class="row">
    <ul class="self-align-center col-xs-4">
      <li class=""><a class="foot" href="#"><i class="fa fa-facebook"></i></a></li>
        <li class=""><a href="#"><i class="fa fa-instagram"></i></a></li>
          <li class=""><a href="#"><i class="fa fa-twitter"></i></a></li>
        </ul>
        <ul class="self-align-center col-xs-4">
          <li><a href="#"><i class="fa fa-envelope"><span class="ml-1">d.biswas21@yahoo.com</span></i></a></li>
          <li><a href="#"><i class="fa fa-phone"><span class="ml-1">9433503128</span></i></a></li>
          <li><a href="#"><i class="fa fa-question-circle"><span class="ml-1">Help</span></i></a></li>
        </ul>
        <ul class="self-align-center offset-7 col-xs-4">
          <li><a href="#"><i class="fa fa-map-marker"><span class="ml-1">Raigarh</span></i></a></li>

        </ul>
      </div>
      <div style="text-align:center;">
          <a href=#><i class="fa fa-copyright">Gogaga</i></li>
        </div>
      </div>

<!--/ Section Contact-footer End /-->
</body>
<script>
$('a').on('click', function(e) {
$(this).find('[class*="angle"]').toggleClass('fa-angle-down fa-angle-up')
});

$('.go').on('click', function(e) {
$(this).css({
  transform: 'translateX(-195px)',
  transition: 'transform .5s'
});
});
function myFunction() {
/* Get the text field */
var copyText = document.getElementById("myInput");

/* Select the text field */
copyText.select();
copyText.setSelectionRange(0, 99999); /*For mobile devices*/

/* Copy the text inside the text field */
document.execCommand("copy");

/* Alert the copied text */
alert("Copied the text: " + copyText.value);
}
const preloader = document.querySelector('.preloader');

const fadeEffect = setInterval(() => {
// if we don't set opacity 1 in CSS, then   //it will be equaled to "", that's why we   // check it
if (!preloader.style.opacity) {
  preloader.style.opacity = 1;
}
if (preloader.style.opacity > 0) {
  preloader.style.opacity -= 0.1;
} else {
  clearInterval(fadeEffect);
}
}, 200);


anime.timeline({loop: true})
  .add({
    targets: '.ml15 .word',
    scale: [14,1],
    opacity: [0,1],
    easing: "easeOutCirc",
    duration: 800,
    delay: (el, i) => 800 * i
  }).add({
    targets: '.ml15',
    opacity: 1,
    duration: 1000,
    easing: "easeOutExpo",
    delay: 1000
  });

</script>

<script type="text/javascript" src="particles.js"></script>
<script type="text/javascript" src="app.js"></script>
</body>
</html>
