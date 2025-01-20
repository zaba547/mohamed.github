# mohamed.github
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Basic Website</h1>
    </header>
    <main>
        <p id="main-content">This is the main content of the website.</p>
        <button onclick="changeContent()">Change Content</button>
    </main>
    <footer>
        <p>&copy; 2025 My Basic Website</p>
    </footer>
    <script src="scripts.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 1rem;
    text-align: center;
}

main {
    padding: 1rem;
}

button {
    background-color: #4CAF50;
    color: white;
    border: none;
    padding: 0.5rem 1rem;
    cursor: pointer;
}

button:hover {
    background-color: #45a049;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 0.5rem;
    position: absolute;
    bottom: 0;
    width: 100%;
}
function changeContent() {
    document.getElementById('main-content').textContent = 'The content has been changed!';
}
