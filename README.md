<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For You ❤️</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #ffe6e6;
            font-family: Arial, sans-serif;
            text-align: center;
            flex-direction: column;
        }
        .message {
            font-size: 30px;
            color: red;
            text-shadow: 2px 2px 5px pink;
            display: none;
        }
        .heart {
            font-size: 50px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h1 class="heart" onclick="showMessage()">❤️ Click Me ❤️</h1>
    <h2 class="message">Get well soon my cappyberrry ❤️</h2>

    <script>
        function showMessage() {
            document.querySelector('.message').style.display = 'block';
            document.querySelector('.heart').style.display = 'none';
        }
    </script>
</body>
</html>
