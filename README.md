<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="rida's web with stunning design and modern layout">
    <title>rida's web </title>
    <style>
        /* Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #6a11cb, #2575fc);
            color: #ffffff;
            line-height: 1.6;
        }

        header {
            background: rgba(196, 181, 181, 0.116);
            padding: 20px;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        header h1 {
            font-size: 3rem;
            letter-spacing: 2px;
        }

        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            margin: 10px 0 0;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: #00000000;
            text-decoration: none;
            font-size: 1.2rem;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #ffcc00;
        }

        .hero {
            text-align: center;
            padding: 100px 20px;
            background: rgba(0, 0, 0, 0.6);
            backdrop-filter: blur(5px);
            margin: 20px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgb(255, 0, 0);
        }

        .hero h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 1.2rem;
            max-width: 600px;
            margin: 0 auto;
        }

        .services {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
            margin: 40px 20px;
        }

        .service {
            background: rgb(0, 12, 186);
            border-radius: 15px;
            padding: 20px;
            flex: 1 1 300px;
            text-align: center;
            box-shadow: 0 4px 15px rgb(0, 255, 8);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .service:hover {
            transform: translateY(-10px);
            box-shadow: 0 8px 30px rgba(0, 0, 0, 0.4);
        }

        .service h3 {
            font-size: 1.8rem;
            margin-bottom: 10px;
        }

        .service p {
            font-size: 1rem;
        }

        footer {
            background: rgba(255, 3, 3, 0.9);
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
        }

        footer p {
            font-size: 0.9rem;
        }

        footer a {
            color: #ffcc00;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>rida's web </h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section class="hero">
        <h2>Welcome to my web </h2>
        <p>hello world to my page.</p>
    </section>
    <section id="services">
        <div class="services">
            <div class="service">
                <h3>1</h3>
                <p>....</p>
            </div>
            <div class="service">
                <h3>2</h3>
                <p>....</p>
            </div>
            <div class="service">
                <h3>3</h3>
                <p>....</p>
            </div>
        </div>
    </section>
</body>
</html>
