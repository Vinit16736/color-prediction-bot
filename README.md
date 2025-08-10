# color-prediction-bot
touch index.html style.css script.js
code index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Color Prediction Bot</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>🎨 Color Prediction Bot</h1>
    <div id="game">
        <button onclick="predictColor()">Predict Next Color</button>
        <p id="result">Waiting for prediction...</p>
    </div>
    <script src="script.js"></script>
</body>
</html>
function predictColor() {
    const colors = ["Red", "Green", "Blue"];
    const randomColor = colors[Math.floor(Math.random() * colors.length)];
    document.getElementById("result").textContent = `Predicted Color: ${randomColor}`;
}
git add .
git commit -m "Added HTML, CSS, and JS client"
git push
