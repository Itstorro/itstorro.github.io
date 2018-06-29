<!DOCTYPE html>
<html>
  <title>It's Torro</title>
<html lang="en">
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="style.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<style>

body {
    font-family: Tahoma, sans-serif;
    background-color: #354036;
    letter-spacing: 2px;
    }

.navbar {
    font-family: Tahoma, sans-serif;
    color: #769309;
    margin-bottom: 0;
    background-color: #354036;
    border: 0px;
    font-size: 11px;
    letter-spacing: 2px;
    opacity: 90%;
    }

a:hover {
    text-decoration: none;
    color: #fff;
    }

.navbar li a, .navbar, .navbar-brand {
    color: #8A988A !important;
    }

.navbar-nav li a:hover {
    color: #FFF !important;
    }

.navbar-nav li.active a {
    background-color: #29342A !important;
    }

.open .dropdown-toggle {
    background-color: #354036 !important;
    }

.dropdown-menu li a {
    background-color: #354036;
    margin: -5px;
    }

.dropdown-menu li a:hover {
    background-color: #354036;
    color: #fff;
    }

.carousel-inner img {
    width: 100%;
    margin: auto;
    }
</style>

<body>
  <nav class="navbar navbar-default">
    <div class="container-fluid">
      <div class="navbar-header">
        <a class="navbar-brand" href="#">Torro</a>
      </div>
        <ul class="nav navbar-nav">
          <li><a href="#">About</a></li>
          <li class="dropdown"><a class="dropdown-toggle" data-toggle="dropdown" href="#">Recent Work<span class="caret"></span></a>
            <ul class="dropdown-menu">
              <li><a href="#">Deadclown Studios</a></li>
              <li><a href="#">TMRonin</a></li>
            </ul>
          <li class="dropdown"><a class="dropdown-toggle" data-toggle="dropdown" href="#">Published<span class="caret"></span>
            <ul class="dropdown-menu">
              <li><a href="#">Suicide Girls</a></li>
              <li><a href="#">24/7 Inked</a></li>
            </ul>
            <li><a href="#">Contact</a></li>
          </li>
        </ul>
    </div>
  </nav>

  <div id="myCarousel" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators">
      <li data-target="myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="myCarousel" data-slide-to="1"></li>
      <li data-target="myCarousel" data-slide-to="2"></li>
      <li data-target="myCarousel" data-slide-to="3"></li>
    </ol>

    <div class="carousel-inner" role="listbox">
      <div class="item active">
        <img src="./images/carmine1.jpg">
      </div>
      <div class="item">
        <img src="./images/caustix1.jpg">
      </div>
      <div class="item">
        <img src="./images/hazy1.jpg">
      </div>
      <div class="item">
        <img src="./images/ICE1.jpg">
      </div>
    </div>
    <a class="left carousel-control" href="#myCarousel" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right"></span>
      <span class="sr-only">Next</span>
    </a>

  </div>
</body>

</head>
</html>
