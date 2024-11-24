<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Streaming Site</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>My Streaming Site</h1>
    </header>
    <main>
        <video controls>
            <source src="your-video.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
        <p>Enjoy this amazing video!</p>
    </main>
    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    text-align: center;
    background-color: #f0f0f0;
    margin: 0;
}

header {
    background-color: #333;
    color: white;
    padding: 1rem;
}

video {
    width: 80%;
    margin-top: 2rem;
}
console.log("Streaming site is running!");
