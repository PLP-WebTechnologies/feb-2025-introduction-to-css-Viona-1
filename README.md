<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to My Styled Page</h1>
    </header>

    <main>
        <section class="intro-section">
            <h2 id="section-title">A Little About Styling</h2>
            <p>This page demonstrates how to link an external CSS file and apply various styling techniques using different selectors.</p>
            <p>We'll explore colors, fonts, spacing, and more!</p>
        </section>

        <section>
            <h3>Styling an Image</h3>
            <img src="https://via.placeholder.com/300" alt="A placeholder image" class="styled-image">
            <p>This image is styled using a class selector, demonstrating borders, padding, and margins.</p>
        </section>

        <section>
            <h3>List of Features</h3>
            <ul>
                <li>External CSS linking</li>
                <li class="highlight">Three different selectors</li>
                <li>Improved readability and aesthetics</li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Basic Styling Example</p>
    </footer>
</body>
</html>



/* Universal selector for basic box-sizing */
* {
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 1rem 0;
    text-align: center;
    margin-bottom: 20px;
}

h1, h2, h3 {
    color: #333;
    font-family: 'Georgia', serif;
}

/* Class selector */
.intro-section {
    background-color: #e0f2f7;
    padding: 20px;
    margin: 0 20px 20px 20px; /* Top, Right, Bottom, Left */
    border: 1px solid #a7d9ee;
    border-radius: 8px;
}

/* ID selector */
#section-title {
    color: #007bff;
    text-align: center;
    margin-bottom: 15px;
}

/* Styling an image */
.styled-image {
    display: block; /* To apply margin auto for centering */
    margin: 20px auto; /* Top/Bottom 20px, Left/Right auto (centers) */
    padding: 10px;
    border: 3px solid #ff5722; /* Orange border */
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    max-width: 100%; /* Ensures image is responsive */
    height: auto;
}

/* Element selector combined with class selector */
ul li.highlight {
    background-color: #fff9c4; /* Light yellow background */
    font-weight: bold;
    padding: 5px;
    border-left: 5px solid #ffeb3b;
    margin-bottom: 5px;
}

/* Basic styling for readability */
main {
    max-width: 960px;
    margin: 20px auto;
    padding: 0 20px;
    background-color: white;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #333;
    color: white;
    margin-top: 30px;
}
