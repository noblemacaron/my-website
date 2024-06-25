<!DOCTYPE html>
<html>
<head>
    プログラミング学習ゲーム
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <div id="game-container">
        <h1>プログラミング学習ゲーム</h1>
        <div id="game-area"></div>
        <button id="start-button">スタート</button>
    </div>
    <script src="app.js"></script>
</body>
</html>
/* styles.css */
body {
    font-family: Arial, sans-serif;
}

#game-container {
    text-align: center;
    margin-top: 50px;
}

#game-area {
    margin: 20px auto;
    width: 80%;
    height: 400px;
    border: 1px solid #000;
}
