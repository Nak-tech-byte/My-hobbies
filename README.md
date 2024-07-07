
<html>
<head>
    <style>
        /* General styles */
        body {
            background-image: url("GHANA_Image_2.jpg");
            background-size:  8; 
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 3;
            transition: background-color 0.5s, color 0.5s;
        }

        body.dark-theme {
            background-color: #1aabe4;
            color: #e0e0e0;
        }

        /* Navigation menu styles */
        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
            background-color: rgba(106, 9, 126, 0.5);
        }

        nav ul li {
            margin: 0;
            padding: 3;
        }

        nav ul li a {
            display: block;
            padding: 10px;
            color: inherit;
            text-decoration: none;
            background-color: #333;
            transition: background-color 0.3s, color 0.3s;
        }

        nav ul li a:hover {
            background-color: #555;
            color: beige;
        }

        /* Styles for elements in the dark theme */
        body.dark-theme nav ul {
            background-color: rgba(255, 255, 255, 0.1);
        }

        body.dark-theme nav ul li a {
            background-color: #444;
            color: #fff;
        }

        body.dark-theme nav ul li a:hover {
            background-color: #666;
            color: beige;
        }
    </style>
    <link rel="stylesheet" href="style2.css">
    <title>Personal Bio</title>
</head>
<body>
    <nav>
        <ul>
            <li><a href="#themeButton">Theme Button</a></li>
            <li><a href="#name">Name</a></li>
            <li><a href="#hobbies">Hobbies</a></li>
            <li><a href="#pics">Pictures</a></li>
        </ul>
    </nav>

    <button id="themeButton">Change Theme Color</button>

    <div id="name">
        <h1>Nana Antwi</h1>
        <p>Nana Antwi is an interactive design major passionate about creating engaging digital experiences. In her free time, she enjoys dancing, singing, cooking, and listening to music, bringing creativity and joy to all her pursuits.</p>
    </div>

    <div class="profile-card">
        <h3>Nana Antwi</h3>
        <p>Interactive Design Student</p>
        <p>Interests: Dancing, Singing, Cooking, Listening to Music</p>
    </div>

    <div id="hobbies">
        <h2>Hobbies & Interests</h2>
        <p>Nana Antwi is an enthusiastic individual who loves dancing, singing, cooking, and listening to music. Her hobbies reflect her vibrant and creative personality, bringing energy and joy to everything she does.</p>
        <ul>
            <li>Dancing</li>
            <li>Singing</li>
            <li>Cooking</li>
            <li>Listening to Music</li>
        </ul>
    </div>

    <div id="pics">
        <h2>Pictures</h2>
        <img src="cooking.jpeg" alt="Cooking" width="500">
        <img src="dancing.jpeg" alt="Dancing" width="500">
        <img src="singing.jpeg" alt="Singing" width="500">
    </div>

    <script>
        document.getElementById('themeButton').addEventListener('click', function() {
            document.body.classList.toggle('dark-theme');
        });
    </script>
</body>
</html>

