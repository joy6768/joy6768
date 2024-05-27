<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #004d40;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #00695c;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #004d40;
        }
        .container {
            padding: 20px;
        }
        .section {
            margin-bottom: 40px;
        }
        .section h2 {
            border-bottom: 2px solid #004d40;
            padding-bottom: 10px;
        }
        footer {
            background-color: #004d40;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Personal Webpage</h1>
    </header>
    <nav>
        <a href="#about">About Me</a>
        <a href="#journey">Travel Journey</a>
        <a href="#career">Career Achievements</a>
        <a href="#contact">Contact Me</a>
    </nav>
    <div class="container">
        <div id="about" class="section">
            <h2>About Me</h2>
            <p>I am a professional full-time model from China who gave up a privileged life to study in the United States and earned a degree in Marine Biology. During my studies, I lived through the COVID pandemic and decided to move into a van to travel for my graduation without paying for hotels.</p>
        </div>
        <div id="journey" class="section">
            <h2>Travel Journey</h2>
            <p>I flew to Florida and bought a second-hand Mercedes Sprinter, which I converted into a camper during the summer while attending classes. I then completed a road trip around the United States. In Alaska, I worked as a Marine Biologist for NOAA. When I ran out of money during my travels, I returned to Los Angeles to work as a lab scientist and part-time surf instructor. In my free time, I enjoy spearfishing, surfing, hiking, and teaching children to paint.</p>
        </div>
        <div id="career" class="section">
            <h2>Career Achievements</h2>
            <p>While in the U.S., I completed my degree in Marine Biology and worked for NOAA in Alaska. Later, I worked as a lab scientist in Los Angeles and taught surfing part-time. My journey showcases my professional skills and my determination to pursue my dreams courageously.</p>
        </div>
        <div id="contact" class="section">
            <h2>Contact Me</h2>
            <p>If you are interested in my journey or want to learn more, please contact me through the following:</p>
            <ul>
                <li>Email: example@example.com</li>
                <li>Phone: 123-456-7890</li>
                <li>Social Media: 
                    <a href="#">Weibo</a>, 
                    <a href="#">WeChat</a>, 
                    <a href="#">Instagram</a>
                </li>
            </ul>
        </div>
    </div>
    <footer>
        &copy; 2024 My Personal Webpage. All rights reserved.
    </footer>
</body>
</html>
