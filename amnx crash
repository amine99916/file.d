<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>لعبة كراش</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; margin-top: 50px; }
        #startBtn { padding: 10px 20px; font-size: 16px; cursor: pointer; }
        #result { margin-top: 20px; font-size: 24px; }
    </style>
</head>
<body>
    <h1>لعبة كراش</h1>
    <button id="startBtn">ابدأ اللعبة</button>
    <div id="result"></div>

    <script>
        document.getElementById('startBtn').addEventListener('click', function() {
            let crashPoint = Math.random() * 10;
            let resultText = `انتهت اللعبة عند ${crashPoint.toFixed(2)}x`;
            document.getElementById('result').textContent = resultText;
        });
    </script>
</body>
</html>
