<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dog Friendly Cafe</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5e6ca;
            background-image: radial-gradient(circle, rgba(0, 0, 0, 0.1) 10%, transparent 10%),
                              radial-gradient(circle, rgba(0, 0, 0, 0.1) 10%, transparent 10%);
            background-size: 40px 40px;
            background-position: 0 0, 20px 20px;
            text-align: center;
            color: white;
        }
        header {
            background-color: rgba(106, 75, 61, 0.9);
            color: white;
            padding: 20px;
            font-size: 24px;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        header img {
            height: 50px;
            margin-right: 15px;
        }
        nav {
            background: rgba(106, 75, 61, 0.9);
            padding: 15px;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            margin: 0 15px;
            font-weight: 600;
            transition: color 0.3s ease;
        }
        nav a:hover {
            color: #d9b08c;
        }
        .container {
            max-width: 900px;
            margin: 40px auto;
            background: rgba(255, 255, 255, 0.9);
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            color: black;
        }
        .menu {
            text-align: left;
            margin-top: 20px;
        }
        .menu ul {
            list-style-type: none;
            padding: 0;
        }
        .menu ul li {
            background: #d9b08c;
            padding: 10px;
            margin: 5px 0;
            border-radius: 5px;
        }
        footer {
            background-color: rgba(106, 75, 61, 0.9);
            color: white;
            padding: 15px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo.png" alt="Dog Friendly Cafe Logo">
        Добро пожаловать в Dog Friendly Cafe
    </header>
    
    <nav>
        <a href="#about">О нас</a>
        <a href="#menu">Меню</a>
        <a href="#contact">Контакты</a>
    </nav>
    
    <div class="container" id="about">
        <h2>О нас</h2>
        <p>Dog Friendly Cafe — это уютное кафе в Одессе, где вы можете насладиться вкусным кофе и десертами вместе со своим питомцем.</p>
    </div>
    
    <div class="container" id="menu">
        <h2>Меню</h2>
        <div class="menu">
            <h3>Кофе</h3>
            <ul>
                <li>Эспрессо</li>
                <li>Капучино</li>
                <li>Латте</li>
                <li>Фильтр-кофе</li>
            </ul>
            <h3>Десерты</h3>
            <ul>
                <li>Чизкейк</li>
                <li>Круассан</li>
                <li>Пирог дня</li>
            </ul>
            <h3>Для собак</h3>
            <ul>
                <li>Натуральные лакомства</li>
                <li>Свежая вода</li>
            </ul>
        </div>
    </div>
    
    <div class="container" id="contact">
        <h2>Контакты</h2>
        <p>ул. Примерная, 12, Одесса | Тел: +380 67 123 45 67</p>
    </div>
    
    <footer>
        © 2025 Dog Friendly Cafe. Все права защищены.
    </footer>
</body>
</html>
