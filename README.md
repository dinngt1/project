<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Простой сайт</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Добро пожаловать на мой сайт</h1>
        <nav>
            <ul>
                <li><a href="#home">Главная</a></li>
                <li><a href="#about">О нас</a></li>
                <li><a href="#contact">Контакты</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="home">
            <h2>Главная</h2>
            <p>Это главная страница моего сайта.</p>
        </section>
        <section id="about">
            <h2>О нас</h2>
            <p>Здесь можно узнать о нас больше.</p>
        </section>
        <section id="contact">
            <h2>Контакты</h2>
            <p>Свяжитесь с нами через контактную форму ниже.</p>
            <form>
                <label for="name">Имя:</label>
                <input type="text" id="name" name="name">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email">
                <input type="submit" value="Отправить">
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Простой сайт. Все права защищены.</p>
    </footer>
    <script src="scripts.js"></script>
</body>
</html>
