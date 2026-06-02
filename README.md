# Task12

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Task7</title>

    <style>
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        header{
            background-color: black;
            color: white;
        }

        ul{
            display: grid;
            grid-template-columns: repeat(3, auto);
            justify-content: start;
        }

        ul li{
            list-style: none;
            padding: 20px 30px;
        }

        .container{
            display: grid;
            grid-template-columns: 1fr 1fr; /* Two equal columns */
            gap: 20px;
            padding: 20px;
        }

        .left{
            background-color: aqua;
            min-height: 80vh;
            padding: 10px;
        }

        .right{
            background-color: rgb(40, 211, 40);
            min-height: 80vh;
            padding: 10px;
        }
          @media screen and (max-width: 1000px) {
            body{
                background-color: rgb(53, 14, 246);
            }
        }
          @media screen and (max-width: 800px) {
            body{
                background-color: rgb(225, 15, 15);
            }
        }
          @media screen and (max-width: 600px) {
            body{
                background-color: rgb(158, 207, 13);
            }
        }
    </style>
</head>

<body>

    <header>
        <nav>
            <ul>
                <li>Home</li>
                <li>About</li>
                <li>Contact</li>
            </ul>
        </nav>
    </header>

    <div class="container">

        <div class="left">
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
            Assumenda incidunt optio magnam aliquam placeat commodi
            inventore odit sapiente culpa aperiam.
        </div>

        <div class="right">
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
            Nobis sint veniam expedita quos, eaque laborum ad consequatur.
        </div>

    </div>

</body>
</html>
