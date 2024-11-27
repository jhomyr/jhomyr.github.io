<!DOCTYPE html>
<html lang="en">
<head>
    <title>Add two numbers Version 1 - Using Prompts</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <style>
        body {
            font-family: "Lato", sans-serif;
            display: flex;
            margin: 0;
        }

        /* Style for the left navbar */
        .w3-bar {
            width: 250px;
            position: fixed;
            top: 0;
            left: 0;
            height: 100%;
            background-color: #111;
            padding-top: 20px;
            overflow: auto;
        }

        .w3-bar a {
            color: white;
            padding: 10px 15px;
            text-decoration: none;
            display: block;
        }

        .w3-bar a:hover {
            background-color: #575757;
        }

        /* Content area */
        .content {
            margin-left: 250px; /* To leave space for the navbar */
            padding: 20px;
            width: 100%;
        }

        /* For mobile devices (screen size < 600px) */
        @media screen and (max-width: 600px) {
            .w3-bar {
                width: 100%;
                height: auto;
                position: relative;
            }
            .w3-bar a {
                float: left;
            }
            .content {
                margin-left: 0;
            }
        }
    </style>
</head>
<body>

<!-- Left Navbar -->
<div class="w3-bar w3-black w3-card">
    <a href="index.html" class="w3-bar-item w3-button w3-padding-large">HOME</a>
    <a href="Add2numbersV1.html" class="w3-bar-item w3-button w3-padding-large">Conversion (Celsius to Fahrenheit, Fahrenheit to Celsius, Meters to Feet, Feet to Meters)</a>
    <a href="GradeComputationV1.html" class="w3-bar-item w3-button w3-padding-large">Income Tax Calculator</a>
    <a href="GradeComputationV2.html" class="w3-bar-item w3-button w3-padding-large">Factorial (While Loop), Sum (Do While Loop) and Average (For Loop) of First N Natural Numbers</a>
    <a href="Add2numbersV4.html" class="w3-bar-item w3-button w3-padding-large">Simple Payroll</a>
</div>

<!-- Main Content Section -->
<div class="content">
    <h1>Add two numbers Version 1 - Using Prompts</h1>
    <br>
    <p>
        <a href="index.html">Back to Home Page</a>
    </p>
    <br>

    <button onclick="clickbtn()">Compute the sum</button>

    <script>
    function clickbtn()
    {
        let a='', b='', x=0, y=0;

        a = prompt('The first number:');
        b = prompt('The second number:');

        x = parseInt(a);
        y = parseInt(b);

        let z = x + y;

        document.write('<h2>The sum is: ' + z + '</h2> <br>');
        document.write('<br><a href="Add2numbersV1.html">Add again</a>');
        document.write('<br><a href="index.html">Back to Home Page</a>');
    }
    </script>
</div>

</body>
</html>
