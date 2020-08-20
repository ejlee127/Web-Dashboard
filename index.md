<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Visualization</title>
    <style>
        h1 {
            text-align: center;
        }
        h3 {
            text-align: center;
            color: rgb(17, 143, 160);
        }
        img {
            width: 100%;
            height: 80%;
        }
        .container {
            margin-top: 30px;
            font-family: Georgia, 'Times New Roman', Times, serif;
        }
    </style>
    <!-- Bring in our bootstrap stylesheet -->
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

</head>
<body style="background: rgb(235, 232, 231)">
    <nav class="navbar navbar-dark bg-dark p-8">
        <h1 class="navbar-brand"> Project: Web-Design-Challenge</h1> 
    </nav>
    <div class="container">
        <div class="row">
            <div class="col-12">
            <p> This project creates visualization 
                dashboard websites using the charts from cities/soccer datasets.</p>
            </div>
        </div>
        <div class="row">
            <div class="col-12 col-sm-6 col-md-6">
                <a href="WebVisualizations/landing.html"> <h3>Latitude vs. X</h3> 
                <img src="WebVisualizations/assets/images/Fig1.png" alt='Lattitude chart'/>
                </a>
                <p> Cities dataset</p>
            </div>
            <div class="col-12 col-sm-6 col-md-6">
                <a href="SoccerVisualizations/soccer.html"> <h3>Scores vs. X</h3> 
                <img src="SoccerVisualizations/assets/images/Fig0.png" alt='Lattitude chart'/>
                </a>
                <p> Soccer dataset</p>
            </div>
        </div>
    </div>

    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
     
</body>
</html>