<!DOCTYPE html>
<html>
<head>
    <title>TonEarn</title>
    <script src="https://telegram.org/js/telegram-web-app.js"></script>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            background: purple;
            color: white;
            text-align: center;
            padding: 50px;
            font-family: Arial;
        }
        button {
            background: white;
            color: purple;
            border: none;
            padding: 15px;
            margin: 10px;
            border-radius: 10px;
            width: 200px;
        }
    </style>
</head>
<body>
    <h1>⛏️ TonEarn</h1>
    <p>Mini App работает!</p>
    
    <button onclick="alert('Майнинг запущен!')">🚀 Майнинг</button>
    <button onclick="alert('TON адрес: UQCH1F3tgQ8yyqYHxZyFBw6_Y3tfYu91KP5ko16mM7CPaWY5')">💰 Пополнить</button>
    <button onclick="alert('Реферальная система')">👥 Рефералы</button>

    <script>
        let tg = window.Telegram.WebApp;
        tg.expand();
    </script>
</body>
</html>
