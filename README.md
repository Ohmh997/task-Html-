



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jordan Store</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #50b3a2;
            color: #ffffff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #2980b9 3px solid;
        }
        header a {
            color: #ffffff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            float: left;
            display: inline;
            padding: 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        header .highlight, header .current a {
            color: #e9ff70;
        }
        header a:hover {
            color: #cccccc;
            font-weight: bold;
        }
        #showcase {
            min-height: 400px;
            background: #35424a;
            color: #ffffff;
            text-align: center;
            padding-top: 100px;
        }
        #showcase h1 {
            margin-top: 0;
            font-size: 55px;
            margin-bottom: 10px;
        }
        #showcase p {
            font-size: 20px;
        }
        .box {
            float: left;
            width: 45%;
            padding: 10px;
            margin: 10px;
            background: #ffffff;
            box-shadow: 0 0 5px rgba(0,0,0,0.1);
            text-align: center;
        }
        .box img {
            max-width: 100%;
        }
        .box h3 {
            margin: 20px 0;
        }
        .box p {
            font-size: 14px;
            color: #666666;
        }
        footer {
            background: #333333;
            color: #ffffff;
            text-align: center;
            padding: 30px 0;
        }
        footer p {
            margin: 0;
        }
        .clearfix::after {
            content: "";
            display: table;
            clear: both;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1><span class="highlight">Jordan</span> Store</h1>
            </div>
            <nav>
                <ul>
                    <li class="current"><a href="#">Home</a></li>
                    <li><a href="#">Products</a></li>
                    <li><a href="#">Company</a></li>
                    <li><a href="#">More</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="showcase">
        <div class="container">
            <h1>"Explore Our Exclusive Range of Tech Gadgets"</h1>
            <p>Welcome to our store! We offer a wide range of products to meet all your needs.</p>
        </div>
    </section>

    <div class="container clearfix">
        <div class="box">
            <img src="https://static.vecteezy.com/system/resources/previews/007/642/395/non_2x/laptop-electronic-portable-computer-notebook-line-pop-art-potrait-logo-colorful-design-illustration-vector.jpg" alt="Laptop Logo">
            <h3>Laptops</h3>
            <p>Everything for laptops</p>
            <a href="#">Enter</a>
        </div>

        <div class="box">
            <img src="https://logos-world.net/wp-content/uploads/2022/01/iPhone-Emblem.png" alt="iPhone Logo">
            <h3>Mobile Phones</h3>
            <p>Everything for iPhones</p>
            <a href="#">Enter</a>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Jordan Store. All Rights Reserved.</p>
    </footer>
</body>
</html>
