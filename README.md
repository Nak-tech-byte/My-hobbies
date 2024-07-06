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
* General styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

/* Navigation menu styles */
    nav 
        body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
    
}

/* List styles inside the navigation */
nav ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
}

nav ul li {
    margin: 0;
    padding: 0;
}

nav ul li a {
    display: block;
    padding: 10px;
    color: inherit; /* Use inherited text color */
    text-decoration: none;
}

nav ul li a:hover {
    background-color: #f9f9f9; /* Light background on hover */
}

/* Dark theme styles */
.dark-theme {
    background-color: #333; /* Dark background */
    color: #fff; /* Light text */
}

.dark-theme h1, .dark-theme h2 {
    font-family: 'Times New Roman', serif;
    color: #ff8c00; /* Orange color for headers in dark theme */
}

.dark-theme nav ul li a {
    color: #fff; /* Light text for links in dark theme */
}

.dark-theme #name, .dark-theme #hobbies, .dark-theme #pics {
    background-color: #444; /* Darker background for sections in dark theme */
    border-color: #555; /* Darker border for sections in dark theme */
}

/* Profile card styles */
.profile-card {
    width: 300px;
    margin: 20px auto;
    border: 1px solid #ddd;
    padding: 20px;
    background-color: #f9f9f9;
    text-align: center;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

/* Profile picture styles */
.profile-card .profile-pic {
    width: 100px;
    height: 100px;
    border-radius: 50%; /* Circle image */
    margin: 0 auto;
}

/* Header styles */
h1 {
    margin-bottom: 20px;
    padding-bottom: 10px;
}

h2 {
    margin-bottom: 10px;
}

/* List styles */
ul {
    padding-left: 20px;
}

li {
    margin-bottom: 5px;
}

/* Section styles */
#name, #hobbies, #pics {
    margin: 20px;
    border: 1px solid #ddd; /* Light grey border */
    padding: 20px;
    background-color: #f9f9f9; /* Light background for each */
}
