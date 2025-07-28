<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Моё Mini App</title>
    <script src="https://telegram.org/js/telegram-web-app.js"></script>
    <style>
        body { font-family: Arial; text-align: center; margin-top: 50px; background: #f0f0f0; }
        button { background: #007bff; color: white; border: none; padding: 15px; margin: 10px; font-size: 20px; cursor: pointer; border-radius: 5px; }
        button:hover { background: #0056b3; }
    </style>
</head>
<body>
    <h1>Добро пожаловать, Dimas!</h1>
    <button onclick="buttonClicked(1)">Кнопка 1</button>
    <button onclick="buttonClicked(2)">Кнопка 2</button>

    <script>
        function buttonClicked(number) {
            alert(`Нажата кнопка ${number}!`);
        }
    </script>
</body>
</html>
