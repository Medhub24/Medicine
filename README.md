# Medicine
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Качественное медицинское образование</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f9fa;
            margin: 0;
            padding: 0;
            animation: fadeIn 1s ease-in-out;
        }

        header {
            background-color: #005f6b;
            color: white;
            text-align: center;
            padding: 20px 0;
            animation: slideInDown 1s ease-out;
        }

        header h1 {
            margin: 0;
        }

        nav {
            background-color: #003d44;
            padding: 10px 0;
            text-align: center;
            animation: fadeIn 1.5s ease-in-out;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #ffd700;
        }

        section {
            padding: 40px;
            margin: 20px;
        }

        footer {
            background-color: #003d44;
            color: white;
            text-align: center;
            padding: 15px 0;
        }

        .content {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            animation: fadeIn 2s ease-in-out;
        }

        .content div {
            width: 45%;
            margin-bottom: 20px;
        }

        .testimonial, .resources {
            background-color: #e9ecef;
            padding: 20px;
            border-radius: 8px;
            animation: fadeIn 2s ease-in-out;
        }

        .resources ul {
            list-style-type: none;
            padding: 0;
        }

        .resources li {
            margin: 10px 0;
        }

        .contact-form {
            background-color: #ffffff;
            padding: 20px;
            border-radius: 8px;
            animation: fadeIn 2.5s ease-in-out;
        }

        /* Анимации */
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        @keyframes slideInDown {
            from {
                transform: translateY(-100%);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        /* Стиль для кнопки оплаты */
        .payment-btn {
            background-color: #005f6b;
            color: white;
            padding: 15px 25px;
            border: none;
            border-radius: 8px;
            font-size: 18px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .payment-btn:hover {
            background-color: #00494d;
        }

        /* Стиль для создания тестов */
        .test-creation {
            background-color: #f0f0f0;
            padding: 20px;
            border-radius: 8px;
        }

        .test-creation input, .test-creation textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
    </style>
</head>
<body>

<header>
    <h1>Качественное медицинское образование</h1>
    <p>Доступ к знаниям, инновационные методы обучения и цифровые инструменты для студентов и врачей</p>
</header>

<nav>
    <a href="#home">Главная</a>
    <a href="#features">Особенности</a>
    <a href="#news">Новости</a>
    <a href="#reviews">Отзывы</a>
    <a href="#contact">Контакты</a>
</nav>

<section id="home">
    <h2>Быстрое и доступное медицинское образование</h2>
    <p>Мы предоставляем доступ к лучшим ресурсам для студентов медиков, резидентов и врачей. Мы поможем вам найти сайты, источники и приложения для повышения квалификации, научных исследований, мотивации, а также методики для успешного карьерного роста.</p>
    <div class="content">
        <div>
            <h3>Ресурсы для студентов</h3>
            <p>Найдите лучшие источники для обучения, актуальные темы для исследований и эффективные методики запоминания информации.</p>
        </div>
        <div>
            <h3>Ресурсы для резидентов</h3>
            <p>Ресурсы для резидентов с актуальными курсами и программами для профессионального роста и углубленного обучения.</p>
        </div>
    </div>
</section>

<section id="features">
    <h2>Особенности</h2>
    <div class="resources">
        <h3>Рекомендуемые ресурсы</h3>
        <ul>
            <li><a href="#">Сайт 1: Курсы по медицине</a></li>
            <li><a href="#">Сайт 2: Программы повышения квалификации</a></li>
            <li><a href="#">Сайт 3: Образовательные приложения</a></li>
        </ul>
    </div>

    <h3>Бесплатный доступ на 2 недели</h3>
    <p>Попробуйте все возможности сайта бесплатно в течение 2 недель. После этого доступ к образовательному контенту будет доступен только после онлайн-оплаты.</p>
    <button class="payment-btn">Оплатить доступ</button>
</section>

<section id="news">
    <h2>Новости о медицине</h2>
    <p>Ознакомьтесь с актуальными новостями, исследовательскими статьями и последними достижениями в медицинской сфере.</p>
    <ul>
        <li><a href="#">Новость 1: Новые методы лечения рака</a></li>
        <li><a href="#">Новость 2: Прорыв в области нейронаук</a></li>
        <li><a href="#">Новость 3: Актуальные темы для научных исследований</a></li>
    </ul>
</section>

<section id="reviews">
    <h2>Отзывы пользователей</h2>
    <div class="testimonial">
        <p><strong>Иван, студент:</strong> «Этот сайт помог мне найти все необходимые материалы для моего обучения и научных исследований!»</p>
        <p><strong>Анна, резидент:</strong> «Потрясающие ресурсы для повышения квалификации и карьерного роста. Очень рекомендую!»</p>
    </div>
</section>

<section id="test-creation">
    <h2>Создайте свой тест</h2>
    <div class="test-creation">
        <h3>Создайте медицинский тест для других пользователей</h3>
        <form action="#" method="POST">
            <label for="test-title">Название теста:</label><br>
            <input type="text" id="test-title" name="test-title" required><br><br>
            <label for="questions">Вопросы:</label><br>
            <textarea id="questions" name="questions" rows="5" required></textarea><br><br>
            <button type="submit">Создать тест</button>
        </form>
    </div>
</section>

<section id="contact">
    <h2>Контакты</h2>
    <p>Если у вас есть вопросы, пожалуйста, свяжитесь с нами по электронной почте: <a href="mailto:jazi.mirzamurat@gmail.com">jazi.mirzamurat@gmail.com</a></p>
    <div class="contact-form">
        <h3>Оставьте отзыв</h3>
        <form action="#" method="POST">
            <label for="name">Имя:</label><br>
            <input type="text" id="name" name="name" required><br><br>
            <label for="email">Электронная почта:</label><br>
            <input type="email" id="email" name="email" required><br><br>
            <label for="message">Сообщение:</label><br>
            <textarea id="message" name="message" rows="4" required></textarea><br><br>
            <button type="submit">Отправить</button>
        </form>
    </div>
</section>

<footer>
    <p>&copy; 2024 Качественное медицинское образование. Все права защищены.</p>
</footer>

</body>
</html>
