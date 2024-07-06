!DOCTYPE html>
<html>
<head>
    <style>
        body {
            background-image: url("GHANA_Image_2.jpg");
            background-size: cover;
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
