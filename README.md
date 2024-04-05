
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document Menu</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
            background-color: #f1f1f1;
        }
        nav ul li {
            display: inline-block;
            position: relative;
        }
        nav ul li a {
            display: block;
            padding: 10px 20px;
            color: #333;
            text-decoration: none;
        }
        nav ul li:hover {
            background-color: #ddd;
        }
        nav ul ul {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            background-color: #fff;
            border: 1px solid #ccc;
        }
        nav ul li:hover > ul {
            display: inherit;
        }
        nav ul ul li {
            display: block;
        }
    </style>
</head>
<body>

<header>
    <h1>Document Menu</h1>
</header>

<nav>
    <ul>
        <li><a href="#">Unit 1</a>
            <ul>
                <li><a href="#">Assignment 1</a></li>
                <li><a href="#">Assignment 2</a></li>
                <li><a href="#">Assignment 3</a></li>
            </ul>
        </li>
        <li><a href="#">Unit 2</a>
            <ul>
                <li><a href="#">Assignment 1</a></li>
                <li><a href="#">Assignment 2</a></li>
                <li><a href="#">Assignment 3</a></li>
            </ul>
        </li>
        <li><a href="#">Unit 3</a>
            <ul>
                <li><a href="#">Assignment 1</a></li>
                <li><a href="#">Assignment 2</a></li>
                <li><a href="#">Assignment 3</a></li>
            </ul>
        </li>
        
    </ul>
</nav>

</body>
</html>

