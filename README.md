<!DOCTYPE html>
<html lang="en">
<head>
    <title>Introduction to Computing Website</title>
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

        /* Dropdown menu styles */
        .w3-dropdown-content {
            min-width: 200px;
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
    <a href="#" class="w3-bar-item w3-button w3-padding-large">HOME</a>

    <div class="w3-dropdown-hover">
        <button class="w3-padding-large w3-button" title="More">Javascript Adding 2 Numbers Examples <i class="fa fa-caret-down"></i></button>
        <div class="w3-dropdown-content w3-bar-block w3-card-4">
            <a href="Add2numbersV1.html" class="w3-bar-item w3-button">Add 2 Numbers version #1 - Using Prompts</a>
            <a href="Add2numbersV2.html" class="w3-bar-item w3-button">Add 2 Numbers version #2 - Using HTML Inputs and Labels</a>
            <a href="Add2numbersV3.html" class="w3-bar-item w3-button">Add 2 Numbers version #3 - Using Automatic Sum Computation</a>
        </div>
    </div>

    <div class="w3-dropdown-hover">
        <button class="w3-padding-large w3-button" title="More">Javascript Grade Computation Examples<i class="fa fa-caret-down"></i></button>
        <div class="w3-dropdown-content w3-bar-block w3-card-4">
            <a href="GradeComputationV1.html" class="w3-bar-item w3-button">Grade Computation version #1 - Using if else statements</a>
            <a href="GradeComputationV2.html" class="w3-bar-item w3-button">Grade Computation version #2 - Classifying letter grade using switch statement</a>
        </div>
    </div>

    <div class="w3-dropdown-hover">
        <button class="w3-padding-large w3-button" title="More">Javascript EventListeners<i class="fa fa-caret-down"></i></button>
        <div class="w3-dropdown-content w3-bar-block w3-card-4">
            <a href="Add2numbersV4.html" class="w3-bar-item w3-button">Add 2 Numbers with Button Event Listener</a>
            <a href="Add2numbersV5.html" class="w3-bar-item w3-button">Add 2 Numbers with Input Event Listener</a>
            <a href="GradeComputationV3.html" class="w3-bar-item w3-button">Grade Computation with Input Listener (NEW SYNTAX)</a>
        </div>
    </div>

    <div class="w3-dropdown-hover">
        <button class="w3-padding-large w3-button" title="More">Natural Numbers and Loops<i class="fa fa-caret-down"></i></button>
        <div class="w3-dropdown-content w3-bar-block w3-card-4">
            <a href="LOOPWhile.html" class="w3-bar-item w3-button">Printing Natural Numbers with While Loop</a>
            <a href="LOOPDoWhile.html" class="w3-bar-item w3-button">Printing Natural Numbers with Do While Loop</a>
            <a href="LOOPFor.html" class="w3-bar-item w3-button">Printing Natural Numbers with For Loop</a>
            <a href="RandomNumbersandSorting.html" class="w3-bar-item w3-button">Using Arrays, Generating & Sorting Random Numbers</a>
        </div>
    </div>

    <div class="w3-dropdown-hover">
        <button class="w3-padding-large w3-button" title="More">Shopping Carts<i class="fa fa-caret-down"></i></button>
        <div class="w3-dropdown-content w3-bar-block w3-card-4">
            <a href="htmltable.html" class="w3-bar-item w3-button">HTML Table</a>
            <a href="ShoppingCart1.html" class="w3-bar-item w3-button">Version #1 - Simple Shopping Cart</a>
            <a href="ShoppingCart2.html" class="w3-bar-item w3-button">Version #2 - Using and Formatting HTML Tables</a>
            <a href="ShoppingCart3.html" class="w3-bar-item w3-button">Version #3 - Styling the Shopping Cart</a>
            <a href="ShoppingCart4.html" class="w3-bar-item w3-button">Version #4 - Shopping Cart with Layout and Styles</a>
            <a href="ShoppingCart5.html" class="w3-bar-item w3-button">Version #5 - Improved Javascript</a>
        </div>
    </div>

    <div class="w3-dropdown-hover">
        <button class="w3-padding-large w3-button" title="More">Other Javascript Examples<i class="fa fa-caret-down"></i></button>
        <div class="w3-dropdown-content w3-bar-block w3-card-4">
            <a href="LocalandSessionStorage.html" class="w3-bar-item w3-button">Local and Session Storage</a>
            <a href="ShoppingCart6.html" class="w3-bar-item w3-button">Shopping Cart with Separate Styles and Javascript</a>
            <a href="ShoppingCart7.html" class="w3-bar-item w3-button">Using Session Variables to Generate Modal Responses</a>
        </div>
    </div>

</div>

<!-- Main Content Section -->
<div class="content">
    <h1>Welcome to My Website</h1>
    <p>This is the introduction to the website.</p>
</div>

</body>
</html>
