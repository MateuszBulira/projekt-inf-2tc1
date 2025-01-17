Mateusz Bulira 2tc
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Podobna Strona</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            line-height: 1.6;
        }
        header {
            background-color: #a5ce39;
            color: white;
            padding: 10px 20px;
        }
        header .top-bar {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #fff;
            padding: 10px 0;
            box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.1);
        }
        nav a {
            text-decoration: none;
            color: black;
            margin: 0 15px;
            font-weight: bold;
        }
        .banner {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: #000;
            color: white;
            padding: 50px 20px;
        }
        .banner .content {
            max-width: 50%;
        }
        .banner h1 {
            font-size: 36px;
            margin-bottom: 10px;
        }
        .banner p {
            margin-bottom: 20px;
        }
        .banner .cta {
            background-color: #a5ce39;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
        }
        .banner img {
            max-width: 40%;
            height: auto;
        }
        .features {
            display: flex;
            justify-content: space-around;
            padding: 20px;
            background-color: #f9f9f9;
        }
        .feature {
            text-align: center;
            max-width: 200px;
        }
        .feature img {
            max-width: 50px;
            margin-bottom: 10px;
        }
        .footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <div class="top-bar">
            <span>Orci: +48 500 11 22 33</span>
            <span>example@example.store</span>
        </div>
    </header>
    <nav>
        <a href="#">Donec pulvinar</a>
        <a href="#">Proin eget massa</a>
        <a href="#">Fusce dapibus</a>
        <a href="#">Donec urna justo</a>
        <a href="#">Donec mauris</a>
    </nav>
    <div class="banner">
        <div class="content">
            <h1>Quisque facilisis semper hendrerit</h1>
            <p>Nam in sollicitudin</p>
            <a href="#" class="cta">Praesent vel erat</a>
        </div>
        <img src="https://via.placeholder.com/300" alt="Graffiti Image">
    </div>
    <section class="features">
        <div class="feature">
            <img src="https://via.placeholder.com/50" alt="Icon 1">
            <h3>Phasellus iaculis</h3>
            <p>Phasellus ut tincidunt arcu</p>
        </div>
        <div class="feature">
            <img src="https://via.placeholder.com/50" alt="Icon 2">
            <h3>Donec cursus</h3>
            <p>Donec hendrerit nisl eget</p>
        </div>
        <div class="feature">
            <img src="https://via.placeholder.com/50" alt="Icon 3">
            <h3>Nam quis libero tortor</h3>
            <p>Donec nec odio pretium</p>
        </div>
        <div class="feature">
            <img src="https://via.placeholder.com/50" alt="Icon 4">
            <h3>Morbi blandit sit amet</h3>
            <p>Morbi et neque sit amet augue</p>
        </div>
    </section>
    <footer class="footer">
        &copy; 2025 - All rights reserved
    </footer>
</body>
</html>
