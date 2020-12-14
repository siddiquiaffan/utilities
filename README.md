# utilites
Collection of simple utilities


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <script src="app.js"></script>
    <script src="https://kit.fontawesome.com/95931f8504.js" crossorigin="anonymous"></script>
    <title>CGPA TO PERCENTAGE</title>
</head>
<body>
    <div class="main">
        <div class="center">
            <h2>CGPA TO PERCENTAGE</h2>
            <form method="POST" name="calculator" class="calculator">
                <input type="text" readonly class="result" id="result" name="result" >
                <span class="sem">
                    <label class="label" for="sem_input">SEM 1</label> <br>
                    <i class="fas fa-book"></i>
                    <input type="text" class="input sem_input" id="sem1" name="array" autocomplete="off">
                </span>
                <span class="sem">
                    <label class="label" for="sem_input">SEM 2</label> <br>
                    <i class="fas fa-book"></i>
                    <input type="text" class="input sem_input" id="sem2" name="array" autocomplete="off">
                </span>
                <span class="sem">
                    <label class="label" for="sem_input">SEM 3</label> <br>
                    <i class="fas fa-book"></i>
                    <input type="text" class="input sem_input" id="sem3" name="array" autocomplete="off">
                </span>
                <span class="sem">
                    <label class="label" for="sem_input">SEM 4</label> <br>
                    <i class="fas fa-book"></i>
                    <input type="text" class="input sem_input" id="sem4" name="array" autocomplete="off">
                </span>
                <span class="sem">
                    <label class="label" for="sem_input">SEM 5</label> <br>
                    <i class="fas fa-book"></i>
                    <input type="text" class="input sem_input" id="sem5" name="array" autocomplete="off">
                </span>
                <span class="sem">
                    <label class="label" for="sem_input">SEM 6</label> <br>
                    <i class="fas fa-book"></i>
                    <input type="text" class="input sem_input" id="sem6" name="array" autocomplete="off">
                </span>
                <span class="sem">
                    <label class="label" for="sem_input">SEM 7</label> <br>
                    <i class="fas fa-book"></i>
                    <input type="text" class="input sem_input" id="sem7" name="array" autocomplete="off">
                </span>
                <span class="sem">
                    <label class="label" for="sem_input">SEM 8</label> <br>
                    <i class="fas fa-book"></i>
                    <input type="text" class="input sem_input" id="sem8" name="array" autocomplete="off">
                </span>
            </form>
            <div class="calculate">
                <button onclick="calculate()">Calculate</button>
            </div>
        </div>
        <h3 class="cred"> Made by <u><a href="https://github.com/AffanTheBest/utilities/cgpa-to-percentage" target="_blank"> Affan</a></u></h3>
    </div>
   
</body>
</html>
