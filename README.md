<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.3.0/font/bootstrap-icons.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">

    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js"></script>

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick-theme.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.css">
    <script src="jquery-3.5.1.min.js"></script>
    <script src="https://code.jquery.com/jquery-2.2.0.min.js" type="text/javascript"></script>
    <script src="./slick/slick.js" type="text/javascript" charset="utf-8"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.js"></script>
</head>

<body>
    <!-- header -->
    <div class="container">
        <header class="blog-header py-3">
            <div class="row flex-nowrap justify-content-between align-items-center">
                <div class="col-4 pt-1">
                    <a class="link-secondary" href="#"><img src="images/phone.png" alt="" width="50px"
                            height="50px"></a>
                    <span id="head-one">HOT LINE<br> <strong>+91 7550697083</strong></span>

                </div>
                <div class="col-4 text-center">
                    <a class="blog-header-logo text-dark" href="#"><img src="images/logo_transparent.png" alt=""
                            width="150px" height="150px"></a>
                </div>
                <div class="col-4 d-flex justify-content-end align-items-center">
                    <a class="link-secondary" href="#" aria-label="Search">
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="none" stroke="currentColor"
                            stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="mx-3" role="img"
                            viewBox="0 0 24 24">
                            <title>Search</title>
                            <circle cx="10.5" cy="10.5" r="7.5" />
                            <path d="M21 21l-5.2-5.2" />
                        </svg>
                    </a>

                </div>
            </div>
            <hr>
        </header>

        <!-- navigation bar -->
        <div class="nav-scroller py-1 mb-2">
            <nav class="nav d-flex justify-content-between">


                <li> <a class="p-2 link-secondary " href="#">SITTING</a></li>
                <li> <a class="p-2 link-secondary " href="#">CONFERNCE</a></li>
                <li><a class="p-2 link-secondary" href="#">CONFERNCE</a></li>
                <li><a class="p-2 link-secondary" href="#">CONFERNCE</a></li>
                <li> <a class="p-2 link-secondary" href="#">CONFERNCE</a></li>
                <li> <a class="p-2 link-secondary" href="#">LABS</a></li>
                <li><a class="p-2 link-secondary" href="#">CONTACT US</a></li>

            </nav>
        </div>


    </div>

    <!-- carousel -->
    <div style="margin-top: 20px;">
        <div class="container">
            <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img src="images/bannner.jpg" class="d-block w-100" alt="">
                    </div>
                    <div class="carousel-item">
                        <img src="images/Jain-Shikanji_Banner1_1349x510px_V04.jpg" class="d-block w-100" alt="">
                    </div>
                    <div class="carousel-item">
                        <img src="images/bannner.jpg" class="d-block w-100" alt="">
                    </div>
                </div>
                <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls"
                    data-bs-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Previous</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls"
                    data-bs-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Next</span>
                </button>
            </div>
        </div>
    </div>
    <!-- card section -->
    <div style="margin-top: 30px;">
        <div class="container">

            <div class="row row-cols-1 row-cols-md-3 g-4">
                <div class="col" id="one">
                    <div class="card">
                        <img src="images/chair.png" class="card-img-top" alt="...">
                        <h4 class="card-name">Furniture</h4>
                    </div>
                </div>
                <div class="col">
                    <div class="card" id="two">
                        <img src="images/chair.png" class="card-img-top" alt="...">
                        <h4 class="card-name">Lighting</h4>

                    </div>
                </div>
                <div class="col">
                    <div class="card" id="three">
                        <img src="images/chair.png" class="card-img-top" alt="...">
                        <h4 class="card-name">Indoor</h4>

                    </div>
                </div>

            </div>

        </div>
    </div>

    <!-- Product section -->
    <div style="margin-top: 108px;">
        <div class="container">
            <div class="card-heading">
                <h1>Top Product Headings</h1>
                &nbsp;
                <p>Way is there to get you're sure to love than by making it your know</p>
            </div>
            <div class="row row-cols-1 row-cols-md-4 g-4">
                <div class="col">
                    <div class="card h-100">
                        <img src="images/chair.png" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Wooden Dinning Chair</h5>
                            <p class="card-text" style="text-decoration: line-through;">$67.00</p><span>$60.00</span>

                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card h-100">
                        <img src="images/chair.png" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Wild Geyma High Sideboard</h5>
                            <p class="card-text">$1,200</p>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card h-100">
                        <img src="images/chair.png" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Virka Low Sideboard</h5>
                            <p class="card-text">$890.00</p>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card h-100">
                        <img src="images/chair.png" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Wild Skirt Coffee <Table></Table>
                            </h5>
                            <p class="card-text">$500.00</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </div>

    <!-- Testimonials -->
    <div style="margin-top: 60px;">
        <div class="container">


            <section class="testimonial text-center">
                <div class="container">

                    <div class="heading white-heading">
                        Testimonial
                    </div>
                    <div id="testimonial4"
                        class="carousel slide testimonial4_indicators testimonial4_control_button thumb_scroll_x swipe_x"
                        data-ride="carousel" data-pause="hover" data-interval="5000" data-duration="2000">

                        <div class="carousel-inner" role="listbox">
                            <div class="carousel-item active">
                                <div class="testimonial4_slide">
                                    <img src="https://i.ibb.co/8x9xK4H/team.jpg" class="img-circle img-responsive" />
                                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem
                                        Ipsum has been the industry's standard dummy text ever since the 1500s, when an
                                        unknown printer took a galley of type and scrambled it to make a type specimen
                                        book. </p>
                                    <h4>Client 1</h4>
                                </div>
                            </div>
                            <div class="carousel-item">
                                <div class="testimonial4_slide">
                                    <img src="https://i.ibb.co/8x9xK4H/team.jpg" class="img-circle img-responsive" />
                                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem
                                        Ipsum has been the industry's standard dummy text ever since the 1500s, when an
                                        unknown printer took a galley of type and scrambled it to make a type specimen
                                        book. </p>
                                    <h4>Client 2</h4>
                                </div>
                            </div>
                            <div class="carousel-item">
                                <div class="testimonial4_slide">
                                    <img src="https://i.ibb.co/8x9xK4H/team.jpg" class="img-circle img-responsive" />
                                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem
                                        Ipsum has been the industry's standard dummy text ever since the 1500s, when an
                                        unknown printer took a galley of type and scrambled it to make a type specimen
                                        book. </p>
                                    <h4>Client 3</h4>
                                </div>
                            </div>
                        </div>
                        <a class="carousel-control-prev" href="#testimonial4" data-slide="prev">
                            <span class="carousel-control-prev-icon"></span>
                        </a>
                        <a class="carousel-control-next" href="#testimonial4" data-slide="next">
                            <span class="carousel-control-next-icon"></span>
                        </a>
                    </div>
                </div>
            </section>

        </div>
    </div>

    <!-- images section -->
    <div style="margin-top: 60px;">
        <div class="container">
            <div class="row align-items-start slider">
                <div class="col">
                    <img src="images/g1.png" alt="">
                </div>
                <div class="col">
                    <img src="images/g2.png" alt="">
                </div>
                <div class="col">
                    <img src="images/g4.png" alt="">
                </div>
                <div class="col">
                    <img src="images/g3.png" alt="">
                </div>
                <div class="col">
                    <img src="images/g5.png" alt="">
                </div>
                <div class="col">
                    <img src="images/g6.png" alt="">
                </div>
            </div>
            <br>
            <hr>
        </div>

        <!-- 
        Photo Gallery -->
        <div style="margin-top: 60px;">
            <div class="container">
                <div class="card-heading">
                    <h1>Follow Us On Instagram</h1>
                    &nbsp;
                    <p>@thehouselogists</p>
                </div>
                <br>
                <div class="row" id="gallery">
                    <div class="col">
                        <img src="images/grid.jpeg" alt="" height="250px" width="300px">
                    </div>
                    <div class="col" id="g1">
                        <img src="images/grid.jpeg" alt="" height="250px" width="300px">
                    </div>
                    <div class="col" id="g2">
                        <img src="images/grid.jpeg" alt="" height="250px" width="300px">
                    </div>
                    <div class="col" id="g3">
                        <img src="images/grid.jpeg" alt="" height="250px" width="300px">
                    </div>
                </div>
                <br>
                <div class="row">
                    <div class="col">
                        <img src="images/grid.jpeg" alt="" height="250px" width="300px">
                    </div>
                    <div class="col" id="g4">
                        <img src="images/grid.jpeg" alt="" height="250px" width="300px">
                    </div>
                    <div class="col" id="g5">
                        <img src="images/grid.jpeg" alt="" height="250px" width="300px">
                    </div>
                    <div class="col" id="g6">
                        <img src="images/grid.jpeg" alt="" height="250px" width="300px">
                    </div>
                </div>

            </div>
        </div>

        <!-- footer section -->
        <div style="margin-top: 60px;">

            <!-- <div class="container-fluid" style="background-color: #f9f1bf; height: 40%;">
                <div class="container" style="margin: top 40px;">
                    <div class="row">
                        <div class="col">
                            <img src="images/logo_transparent.png" alt="" height="200px" width="200px">
                        </div>
                        <div class="col">
                            <ul class="">
                                <li class="">Site Map</li>
                                <li class="">Store Location</li>
                                <li class="">My Account</li>
                                <li class="">Orders Tracking</li>
                                <li class="">Size Guide</li>
                              </ul>
                        </div>
                        <div class="col">
                            <ul class="">
                                <li class="-item">Privacy Policy</li>
                                <li class="-item">Returns</li>
                                <li class="-item">Promotions</li>
                                <li class="-item">FAQs</li>
                                
                              </ul>
                        </div>
                        <div class="col">
                            <img src="" alt="">
                        </div>
                    </div>
                </div>
            </div> -->
            <!-- Footer -->
            <footer class="text-center text-lg-start bg-light text-muted" style="background-color: #f9f1bf !important;">
                <!-- Section: Social media -->
                <section class="d-flex justify-content-center justify-content-lg-between p-4 border-bottom">
                    <!-- Left -->

                    <!-- Left -->

                    <!-- Right -->
                    <div>
                        <a href="" class="me-4 text-reset">
                            <i class="fab fa-facebook-f"></i>
                        </a>
                        <a href="" class="me-4 text-reset">
                            <i class="fab fa-twitter"></i>
                        </a>
                        <a href="" class="me-4 text-reset">
                            <i class="fab fa-google"></i>
                        </a>
                        <a href="" class="me-4 text-reset">
                            <i class="fab fa-instagram"></i>
                        </a>
                        <a href="" class="me-4 text-reset">
                            <i class="fab fa-linkedin"></i>
                        </a>
                        <a href="" class="me-4 text-reset">
                            <i class="fab fa-github"></i>
                        </a>
                    </div>
                    <!-- Right -->
                </section>
                <!-- Section: Social media -->

                <!-- Section: Links  -->
                <section class="">
                    <div class="container text-center text-md-start mt-5">
                        <!-- Grid row -->
                        <div class="row mt-3">
                            <!-- Grid column -->
                            <div class="col-md-3 col-lg-4 col-xl-3 mx-auto mb-4">
                                <!-- Content -->

                                <img src="images/logo_transparent.png" alt="" height="200px" width="200px">
                            </div>
                            <!-- Grid column -->

                            <!-- Grid column -->
                            <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mb-4">
                                <!-- Links -->

                                <p>
                                    <a href="#!" class="text-reset">Site Map</a>
                                </p>
                                <p>
                                    <a href="#!" class="text-reset">Store Location</a>
                                </p>
                                <p>
                                    <a href="#!" class="text-reset">My Account</a>
                                </p>
                                <p>
                                    <a href="#!" class="text-reset">Orders Tracking</a>
                                </p>
                                <p>
                                    <a href="#!" class="text-reset">Size Guide</a>
                                </p>
                            </div>
                            <!-- Grid column -->
                            <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mb-4">
                                <!-- Links -->

                                <p>
                                    <a href="#!" class="text-reset">Privacy Policy</a>
                                </p>
                                <p>
                                    <a href="#!" class="text-reset">Returns</a>
                                </p>
                                <p>
                                    <a href="#!" class="text-reset">Promotions</a>
                                </p>
                                <p>
                                    <a href="#!" class="text-reset">FAQs</a>
                                </p>
                            </div>
                            <!-- Grid column -->
                            <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mb-4">
                                <!-- Links -->
                                <h6 class="text-uppercase fw-bold mb-4">
                                    Instagram
                                </h6>
                                <img src="images/product.jpg" alt="" height="100px" width="100px">
                                <img src="images/product.jpg" alt="" height="100px" width="100px">
                            </div>
                            <!-- Grid column -->

                            <!-- Grid column -->
                            <div class="col-md-4 col-lg-3 col-xl-3 mx-auto mb-md-0 mb-4">
                                <!-- Links -->
                                <h6 class="text-uppercase fw-bold mb-4">
                                    Follow Us On Social
                                </h6>
                                <a href="" class="me-4 text-reset">
                                    <i class="bi bi-facebook"></i>
                                </a>
                                <a href="" class="me-4 text-reset">
                                    <i class="bi bi-twitter"></i>
                                </a>
                                <a href="" class="me-4 text-reset">
                                    <i class="bi bi-instagram"></i>
                                </a>
                                <a href="" class="me-4 text-reset">
                                    <i class="bi bi-google"></i>
                                </a>
                                <a href="" class="me-4 text-reset">
                                    <i class="bi bi-linkedin"></i>
                                </a>
                                <a href="" class="me-4 text-reset">
                                    <i class="bi bi-github"></i>
                                </a>
                            </div>
                            <!-- Grid column -->
                        </div>
                        <!-- Grid row -->
                    </div>
                </section>
                <!-- Section: Links  -->
                <script src="https://code.jquery.com/jquery-2.2.0.min.js" type="text/javascript"></script>
                <script src="./slick/slick.js" type="text/javascript" charset="utf-8"></script>
                <script type="text/javascript">
                    $(document).on('ready', function () {
                        $(".vertical-center").slick({
                            dots: true,
                            vertical: true,
                            centerMode: true,
                        });
                        $(".vertical").slick({
                            dots: true,
                            vertical: true,
                            slidesToShow: 3,
                            slidesToScroll: 3
                        });
                        $(".regular").slick({
                            dots: true,
                            infinite: true,
                            slidesToShow: 3,
                            slidesToScroll: 3
                        });
                        $(".center").slick({
                            dots: true,
                            infinite: true,
                            centerMode: true,
                            slidesToShow: 5,
                            slidesToScroll: 3
                        });
                        $(".variable").slick({
                            dots: true,
                            infinite: true,
                            variableWidth: true
                        });

                    });
                </script>


                <!-- <script>
                    $(document).ready(function () {
                        $(".slider").click(function(){
                        $(".slider").slick({
                            slidesToShow: 6,
                            slidesToScroll: 1,
                            autoplay: true,
                            autoplaySpeed: 2000,
                        })
                    })
}); -->
                <!-- </script> -->
</body>

</html>
