<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dessai products</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #6ea1ba;
            color: #000000;
        }

        header {
            background-color: #ffffffe2;
            padding: 20px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2rem;
            background: linear-gradient(270deg, #ff6b6b, #feca57, #48dbfb, #1dd1a1, #ff6b6b);
            background-size: 800% 800%;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: gradientShift 10s ease infinite;
        }

        @keyframes gradientShift {
            0% {
                background-position: 0% 50%;
            }

            50% {
                background-position: 100% 50%;
            }

            100% {
                background-position: 0% 50%;
            }
        }

        header a {
            margin: 0 15px;
            text-decoration: none;
            color: #2980b9;
            font-weight: bold;
            transition: color 0.3s;
        }

        header a:hover {
            color: #1abc9c;
        }

        main {
            padding: 20px;
            max-width: 800px;
            margin: auto;
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.05);
        }

        h4 {
            margin: 0;
            line-height: 1.6;
        }

        footer {
            text-align: center;
            padding: 15px;
            background-color: #ecf0f1;
            color: #555;
            font-size: 0.95rem;
            margin-top: 40px;
        }
    </style>
</head>

<body>
    <header>
        <h1><div>Dessai products</div> </h1>
        <div><a href="3.jpg">Home</a>
        <a href="2.jpg"> About </a>
        <a href="1.jpg" target="_blank">Check</a></div>
    </header>
    <main>
        <pre> <h4>
        At Dessai Products,
        We take pride in offering a curated selection of high-quality items designed to meet your everyday needs.
        Whether you're looking for innovative home solutions, stylish accessories, or practical tools, our diverse 
        range ensures there's something for everyone.
        Every product is carefully tested for performance and durability, ensuring our customers receive only the 
        best.
        Experience reliability, affordability, and modern design — all in one place.
    </main>
    <footer>
        Thanks for visiting!
    </footer>
</body>
</html>

