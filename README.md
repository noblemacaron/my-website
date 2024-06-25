<!DOCTYPE html>
<html>
<head>
    プログラミング修正ゲーム
</head>
<body>
    <div id="game-container">
        <h1>プログラミング修正ゲーム</h1>
        <div id="level-selection">
            <button onclick="startGame('beginner')">初級</button>
            <button onclick="startGame('intermediate')">中級</button>
            <button onclick="startGame('advanced')">上級</button>
        </div>
        <div id="game-area" style="display:none;">
            <div id="code-editor"></div>
            <button id="submit-button">修正を提出</button>
            <div id="feedback"></div>
        </div>
    </div>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/ace/1.4.12/ace.js"></script>
    <script src="app.js"></script>
<style>
/* styles.css */
body {
    font-family: Arial, sans-serif;
}

#game-container {
    text-align: center;
    margin-top: 50px;
}

#level-selection button {
    margin: 5px;
    padding: 10px 20px;
    font-size: 16px;
}

#game-area {
    margin-top: 20px;
}

#code-editor {
    width: 80%;
    height: 300px;
    margin: 0 auto;
    border: 1px solid #000;
}

#submit-button {
    margin-top: 20px;
    padding: 10px 20px;
    font-size: 16px;
}
</style>
</body>
</html>
