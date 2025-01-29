<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MTB Bikes and Brands</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        .container {
            max-width: 1100px;
            margin: auto;
            overflow: hidden;
            padding: 20px;
            background: #fff;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background: #333;
            color: #fff;
            margin-top: 20px;
        }
        .brand {
            margin-bottom: 20px;
        }
        .brand h2 {
            color: #333;
        }
        .header-image {
            width: 100%;
            max-height: 400px;
            object-fit: cover;
        }
    </style>
</head>
<body>
    <header>
        <h1>MTB Bikes and Top Brands</h1>
        <img src="A_dynamic_action_shot_of_a_mountain_biker_riding_d.png" alt="Mountain Biker" class="header-image">
        <nav>
            <ul>
                <li><a href="#fox">Fox</a></li>
                <li><a href="#rockshox">RockShox</a></li>
                <li><a href="#scott">Scott</a></li>
            </ul>
        </nav>
    </header>

    <div class="container">
        <section id="fox" class="brand">
            <h2>Fox</h2>
            <p>Fox is renowned for its high-performance suspension systems that provide unparalleled control and comfort for mountain biking enthusiasts. Their innovative designs and technology have set the standard in the industry.</p>
        </section>

        <section id="rockshox" class="brand">
            <h2>RockShox</h2>
            <p>RockShox is a leader in the development of mountain bike suspension. Known for their durability and precision, RockShox products cater to both professional riders and recreational enthusiasts alike.</p>
        </section>

        <section id="scott" class="brand">
            <h2>Scott</h2>
            <p>Scott is a top-tier brand that delivers a wide range of high-quality mountain bikes. From cross-country to downhill, Scott bikes are engineered for performance and reliability in the toughest terrains.</p>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 MTB Enthusiasts. All Rights Reserved.</p>
    </footer>
</body>
</html>
