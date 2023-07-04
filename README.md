<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./css/style.css">
    <link rel="shortcut icon" href="./images/favicon-portfolio.png" type="image/x-icon">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.1/font/bootstrap-icons.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <title>My Portfolio</title>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
        crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js"
        integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB"
        crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js"
        integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13"
        crossorigin="anonymous"></script>
    <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js"
        integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n"
        crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"
        integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo"
        crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"
        integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6"
        crossorigin="anonymous"></script>
    <script src="js/nav.js"></script>
</head>

<body>
    <!-- Navbar Start -->
    <nav id="navbar" class="black navbar navbar-expand-lg fixed-top">
        <!-- Brand -->
        <a id="nav-logo" class="navbar-brand" href="index.html">Manh</a>

        <!-- Button collapsable -->
        <button class="navbar-toggler" id="nav-btn" type="button" data-toggle="collapse"
            data-target="#collapsibleNavbar">
            <span class="navbar-btn"><i class="fa fa-bars" aria-hidden="true"></i></span>
        </button>
        <!-- Links -->
        <div class="collapse navbar-collapse justify-content-end" id="collapsibleNavbar">
            <ul id="nav-ul" class="navbar-nav">
                <li class="nav-item navigation-list">
                    <a class="nav-link nav-custom-link" href="index.html">Home</a>
                </li>
                <li class="nav-item navigation-list">
                    <a class="nav-link nav-custom-link" href="#about-me">About</a>
                </li>
                <li class="nav-item navigation-list">
                    <a class="nav-link nav-custom-link" href="#my-portfolio">Portfolio</a>
                </li>
                <li class="nav-item navigation-list">
                    <a class="nav-link nav-custom-link" href="#section-contact">Contact</a>
                </li>
            </ul>
        </div>
    </nav>
    <!-- Navbar End -->

    <main class="container-fluid main p-0">
        <!-- SECTION NO 1 -->
        <section class="container-fluid section-1">
            <div class="row section-1-inner">
                <div class="col section-1-inner-col">
                    <div class="image-frame mx-auto my-5">
                    </div>
                </div>
            </div>
        </section>


        <!-- SECTION NO 2 -->
        <section id="about-me" class="container-fluid section-2">
            <div class="row">
                <div class="col text-center">
                    <div class="primary-heading">
                        Data <span class="fw-bold primary-heading-bold">Portfolio</span>
                    </div>
                    <div class="paragraph mx-auto mt-2">
                        Hi, my name is Manh. And I am a Data Analyst. I love Nguyen Thi Quynh Giao
                    </div>
                </div>
            </div>
        </section>


        <!-- SECTION NO 3 -->
        <section class="container-fluid section-3">
            <div class="row section-3-inner">
                <div class="col-lg-6 section-3-inner-col-left text-center">
                    <div class="primary-heading section-3-heading text-lg-end">
                        I Am <span class="fw-bold"> Data Analyst </span>
                    </div>
                    <div class="section-3-image-left text-lg-end">
                        <img src="./images/data analyst 2.jpeg" class="img-fluid sec3-images sec3-img-left" alt="">
                    </div>
                </div>
                <div class="col-lg-6 section-3-inner-col-right text-center mt-5 mt-lg-0">
                    <div class="section-3-image-right text-lg-start">
                        <img src="./images/data analyst.png" class="img-fluid sec3-images sec3-img-right" alt="">
                    </div>
                    <div class="section-3-button-right text-lg-start">
                        <button class="sec3-btn-right text-uppercase fw-bold" onclick="location.href='#'">
                            Read More
                        </button>
                    </div>
                </div>
            </div>
            <div class="background-section-3"></div>
        </section>


        <!-- SECTION NO 4 -->
        <section class="container-fluid section-4">
            <div class="row">
                <div class="col-lg-6">
                    <div class="section-4-left text-center text-lg-end pe-0 pe-lg-5">
                        <span class="section-4-heading text__light">We Make</span>
                        <span class="section-4-heading text__light">Data-Driven</span>
                        <span class="section-4-heading-bold fw-bolder">Decisions</span>
                    </div>
                </div>
                <div class="col-lg-6">
                    <div class="section-4-right text-center text-lg-start">
                        <div class="sec4-blank"></div>
                        <div class="sec4-text">
                            hello this is a section to talk about some more info about data driven decisions
                        </div>
                        <div class="section-4-button">
                            <button class="sec4-btn text-uppercase fw-bold" onclick="location.href='#'">Read
                                More</button>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Divider -->
        <div class="bold-line"></div>


        <!-- SECTION NO 5 -->
        <section id="my-portfolio" class="container-fluid section-5">
            <div class="row">
                <div class="col">
                    <div class="section-5-text text-center mx-auto">
                        We make data driven decisions. 
                    </div>
                    <div class="section-5-icon text-center">
                        <i class="bi bi-chevron-double-down sec5-icon"></i>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col text-center">
                    <div class="sec5-portfolio-head">
                        View Portfolio
                    </div>
                </div>
            </div>

            <div class="row mt-4 mt-md-5 work-gallery-row">
                <div class="masonry">
                    <!-- Work 1 -->
                    <div class="grid">
                        <img src="./images/work-1.jpg" class="img-fluid image-work">
                        <div class="grid__body">
                            <div class="relative">
                                <a class="grid__link" target="_blank" href="#"></a>
                                <p class="grid__author">BY Mubeen Ahmad</p>
                            </div>
                            <div class="mt-auto">
                                <span class="grid__tag">#Work 1</span>
                            </div>
                        </div>
                    </div>
        </section>

        <!-- SECTION CONTACT -->
        <section id="section-contact" class="container-fluid">
            <div class="row">
                <div class="col-12 text-center">
                    <div class="contact-heading">
                        Contact Me
                    </div>
                    <div class="contact-para">
                        Let's get connected
                    </div>
                </div>
            </div>
            <div class="row card-row-1">
                <div class="col-lg-3 col-md-6">
                    <div class="card text-center custom-card">
                        <!-- <div class="card-header"></div> -->
                        <div class="card-body">
                            <div class="card-circle">
                                <div class="card-circle-icon"><i class="fa fa-map-signs" aria-hidden="true"></i></div>
                            </div>
                            <div class="card-heading">Address</div>
                            <div class="card-para">Street No ...</div>
                        </div>
                        <!-- <div class="card-footer"></div> -->
                    </div>
                </div>
                <div class="col-lg-3 col-md-6">
                    <div class="card text-center custom-card mt-5 mt-md-0">
                        <!-- <div class="card-header"></div> -->
                        <div class="card-body">
                            <div class="card-circle">
                                <div class="card-circle-icon"><i class="fa fa-phone" aria-hidden="true"></i></div>
                            </div>
                            <div class="card-heading">Contact Number</div>
                            <div class="card-para"><a class="card-link" href="https://wa.me/+92xxxxxxxxxx">+92xxx
                                    xxxxxxx</div></a>
                        </div>
                        <!-- <div class="card-footer"></div> -->
                    </div>
                </div>
                <div class="col-lg-3 col-md-6">
                    <div class="card text-center custom-card mt-5 mt-lg-0">
                        <!-- <div class="card-header"></div> -->
                        <div class="card-body">
                            <div class="card-circle">
                                <div class="card-circle-icon"><i class="fa fa-paper-plane" aria-hidden="true"></i></div>
                            </div>
                            <div class="card-heading">Email Address</div>
                            <div class="card-para"><a class="card-link"
                                    href="mailto:email@example.com">email@example.com</div></a>
                        </div>
                        <!-- <div class="card-footer"></div> -->
                    </div>
                </div>
                <div class="col-lg-3 col-md-6">
                    <div class="card text-center custom-card mt-5 mt-lg-0">
                        <!-- <div class="card-header"></div> -->
                        <div class="card-body">
                            <div class="card-circle">
                                <div class="card-circle-icon"><i class="fa fa-globe" aria-hidden="true"></i></div>
                            </div>
                            <div class="card-heading">Website</div>
                            <div class="card-para"><a class="card-link" href="#">yoursite.com</a></div>
                        </div>
                        <!-- <div class="card-footer"></div> -->
                    </div>
                </div>
            </div>
        </section>


        <!-- SECTION NO 7 -->
        <section class="container-fluid section-7">
            <div class="row section-7-inner mx-auto text-center">
                <div class="col">
                    <div class="section-7-text">
                        We want to stay in touch with you! Please follow us on social media so we can keep in touch.
                    </div>
                    <div class="section-7-icons">
                        <a href="#" class="social-icons"><i class="bi bi-facebook icons"></i></a>
                        <a href="#" class="social-icons"><i class="bi bi-twitter icons"></i></a>
                        <a href="#" class="social-icons"><i class="bi bi-instagram icons"></i></a>
                        <a href="#" class="social-icons"><i class="bi bi-linkedin icons"></i></a>
                        <a href="#" class="social-icons"><i class="bi bi-pinterest icons"></i></a>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION NO 8 -->
        <footer class="container-fluid footer">
            <div class="row section-footer-inner mx-auto">
                <div class="col-sm-4">
                    <div class="footer-headline">
                        Headline
                    </div>
                    <div class="footer-text">
                        Sample text
                    </div>
                </div>
                <div class="col-sm-4 mt-5 mt-sm-0">
                    <div class="footer-headline">
                        Headline
                    </div>
                    <div class="footer-text">
                        Sample text
                    </div>
                </div>
                <div class="col-sm-4 mt-5 mt-sm-0">
                    <div class="footer-headline">
                        Headline
                    </div>
                    <div class="footer-text">
                        Sample text
                    </div>
                </div>
            </div>

            <!-- Divider -->
            <hr style="border-bottom: 1px solid #FFFFFF;">

            <div class="row section-footer-inner">
                <div class="col">
                    <div class="footer-copyright text-center mt-2">
                        Footer Text
                    </div>
                </div>
            </div>
        </footer>
    </main>
</body>

</html>
