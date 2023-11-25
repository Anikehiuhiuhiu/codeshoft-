# codeshoft-
landing page 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Landing Page</title>
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
            background: #ffffff;
            box-shadow: 0 1px 5px rgba(0, 0, 0, 0.1);
            overflow: hidden;
        }

        header a.logo {
            font-size: 1.5em;
            line-height: 70px;
            padding: 0 20px;
            color: #333;
            text-decoration: none;
            font-weight: bold;
            float: left;
        }

        header ul {
            padding: 0;
            margin: 0;
            float: right;
            list-style: none;
            position: relative;
        }

        header li {
            float: left;
            display: inline;
            margin-left: 20px;
            position: relative;
        }

        header a {
            line-height: 70px;
            padding: 0 5px;
            color: #333;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 14px;
            font-weight: bold;
        }

        header a.cta {
            background: #f2184f;
            padding: 8px 15px;
            border-radius: 5px;
            margin-top: 5px;
            color: #ffffff;
            font-weight: bold;
        }

        header #menu-icon {
            display: hidden;
            width: 40px;
            height: 40px;
            background: #fff;
            float: right;
            cursor: pointer;
            display: none;
        }

        header #menu-icon img {
            width: 20px;
            margin-top: 16px;
        }

        header a:hover {
            color: #f2184f;
        }

        header #menu-icon:hover {
            background: none;
        }

        header ul ul {
            display: none;
            position: absolute;
            top: 60px;
        }

        header ul li:hover > ul {
            display: inherit;
        }

        header ul ul li {
            width: 200px;
            float: none;
            display: list-item;
            position: relative;
        }

        header ul ul ul li {
            position: relative;
            top: -60px;
            left: 200px;
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <a href="#" class="logo">Your Logo</a>
            <div id="menu-icon">
                <img src="menu-icon.png" alt="Menu icon">
            </div>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Features</a></li>
                    <li><a href="#">About Us</a></li>
                    <li><a href="#">Contact</a></li>
                    <li><a href="#" class="cta">Get Started</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <div class="container">
        <section id="main">
            <h1>Welcome to Your Website</h1>
            <p>This is a simple and clean landing page. You can customize it to suit your needs.</p>
            <a href="#" class="cta">Learn More</a>
        </section>
    </div>

</body>
</html>

