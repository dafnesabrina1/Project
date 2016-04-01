//You´ll need to download bootstrap
<!DOCTYPE html>
<html lang="en">

<head>

    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="">
    <meta name="author" content="">

    <title>Traveler Finder</title>>
    <link href="css/bootstrap.min.css" rel="stylesheet">
    <link href="css/half-slider.css" rel="stylesheet">
    <link rel="stylesheet" type="text/css" href="hello.css">

</head>

<body>

    <!-- Navigation -->
    <nav class="navbar navbar-inverse navbar-fixed-top" role="navigation">
        <div class="container">
            <!-- Brand and toggle get grouped for better mobile display -->
            <div class="navbar-header">
                <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1">
                    <span class="sr-only">Toggle navigation</span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
                <a class="navbar-brand" href="#">Traveler Finder</a>
                
            </div>
            <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
                <ul class="nav navbar-nav">
                    <li>
                        <a href="#">About us</a>
                    </li>
                    <li>
                        <a href="#">Services</a>
                    </li>
                    <li>
                        <a href="#">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <header id="myCarousel" class="carousel slide">
        <!-- Indicators -->
        <ol class="carousel-indicators">
            <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
            <li data-target="#myCarousel" data-slide-to="1"></li>
            <li data-target="#myCarousel" data-slide-to="2"></li>
        </ol>

        <!-- Wrapper for Slides -->
        <div class="carousel-inner">
            <div class="item active">
                <!-- Set the first background image using inline CSS below. -->
                <div class="fill" style="background-image:url('http://www.cleaningsupport.com.au/site/wp-content/uploads/2014/10/Career-1.jpg');"></div>
                <div class="carousel-caption">
                    <h2>Experiences</h2>
                </div>
            </div>
            <div class="item">
                <div class="fill" style="background-image:url('https://de.alten.com/wp-content/uploads/2014/04/alten_webheader_02_1900x200px.jpg');"></div>
                <div class="carousel-caption">
                    <h2>USA, Briar Nolet</h2>
                </div>
            </div>
            <div class="item">
                <div class="fill" style="background-image:url('http://www.tecorestoration.com/wp-content/themes/atahualpa351/images/header/4-Happy-Family.jpg');"></div>
                <div class="carousel-caption">
                    <h2>"I finally have my husband back"</h2>
                </div>
            </div>
        </div>

        <!-- Controls -->
        <a class="left carousel-control" href="#myCarousel" data-slide="prev">
            <span class="icon-prev"></span>
        </a>
        <a class="right carousel-control" href="#myCarousel" data-slide="next">
            <span class="icon-next"></span>
        </a>
    </header>
    <div class="container">

        <div class="row">
            <div class="col-lg-12">
                <h1 align="center">Traveler Finder</h1>
                <h2>What we do</h2><p>This is a company dedicated for people who travel a lot. There has been some cases where people get hurt while traveling. The problem is for the family that doesn´t know where their love one has been hurt. They don´t know in which hospital their love one is, what is his or her situation and what they could do to help them. With this webpage you will be able to know if your love one is at a hospital by by givin some information. The local police department will call you, if your love one is not answering, and let them investigate.The hospital could call you if the patient has been found.
 </p>
                <h2 align="center">Click here to initiate a search form</h2>
                <button class="button" align="center" >Search</button>
            </div>
        </div>
        <hr>
        <footer>
            <div class="row">
                <div class="col-lg-12">
                    <p>Copyright &copy; Traveler Finder 2016</p>
                </div>
            </div>
        </footer>

    </div>
    <script src="js/jquery.js"></script>
    <script src="js/bootstrap.min.js"></script>
    <script>
    $('.carousel').carousel({
        interval: 5000 //changes the speed
    })
    </script>

</body>

</html>
