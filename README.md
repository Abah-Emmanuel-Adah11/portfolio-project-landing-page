<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Maze Game</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #f8f8f8;
            color: #333;
        }

        header, footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        .btn {
            display: inline-block;
            padding: 10px 20px;
            background-color: #007bff;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 20px;
            transition: background-color 0.3s ease;
        }

        .btn:hover {
            background-color: #0056b3;
        }

        .feature {
            text-align: center;
            margin-bottom: 30px;
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .feature img {
            max-width: 100%;
            height: auto;
            margin-bottom: 10px;
        }

        .feature h2 {
            font-size: 24px;
            margin-bottom: 10px;
        }

        .feature p {
            font-size: 16px;
        }

        .team {
            list-style-type: none;
            padding: 0;
            text-align: center;
            margin-top: 20px;
        }

        .team li {
            display: inline;
            margin-right: 10px;
        }

       /* footer {
            position: fixed;
            bottom: 0;
            width: 100%;
            background-color: #333;
            padding: 10px 0;
        } */

        footer p {
            margin: 0;
        }

      /*  video {
            width: 100%;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        } */

        /* Add more styles as needed */
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Maze Game</h1>
            <p>A thrilling adventure through challenging mazes</p>
            <nav>
                <ul>
                    <li><a href="#features">Features</a></li>
                    <li><a href="#about">About</a></li>
                </ul>
            </nav>
            <a href="#" class="btn">Play Now</a>
        </div>
    </header>
    <section id="features">
        <div class="container">
            <div class="feature">
                <img src="feature1.jpg" alt="Feature 1">
                <h2>Feature 1</h2>
                <p>Description of feature 1.</p>
            </div>
            <div class="feature">
                <img src="feature2.jpg" alt="Feature 2">
                <h2>Feature 2</h2>
                <p>Description of feature 2.</p>
            </div>
            <div class="feature">
                <img src="feature3.jpg" alt="Feature 3">
                <h2>Feature 3</h2>
                <p>Description of feature 3.</p>
            </div>
        </div>
    </section>
    <section id="about">
        <div class="container">
            <h2>About</h2>
            <p>Description of what inspired the project...</p>
            <p>This project is a Portfolio Project for Holberton School. <a href="https://github.com/yourrepository">GitHub Repository</a></p>
            <ul class="team">
                <li><a href="https://linkedin.com/your-linkedin">LinkedIn</a></li>
                <li><a href="https://github.com/your-github">GitHub</a></li>
                <li><a href="https://twitter.com/your-twitter">Twitter</a></li>
            </ul>
        </div>
    </section>
    <section id="video">
        <div class="container">
            <div class="video-container">
                <video controls>
                    <source src="video.mp4" type="video/mp4">
                    Your browser does not support the video tag.
                </video>
            </div>
        </div>
    </section>
    <footer>
        <div class="container">
            <p>&copy; 2024 Your Name</p>
        </div>
    </footer>
</body>
</html>
