<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Университет</title>
    <style>
        nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: space-around;
    background-color: #356791; /* Цвет фона */
    border-radius: 8px;
    overflow: hidden;
}

nav ul li {
    transition: transform 0.3s ease-out;
}

nav ul li a {
    display: block;
    color: #fff; /* Цвет текста */
    padding: 15px 30px;
    text-decoration: none;
    transition: background-color 0.3s ease; /* Анимация при наведении */
    position: relative;
}

nav ul li a:before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(255, 255, 255, 0);
    transition: background 0.3s ease;
}

nav ul li a:hover:before {
    background: rgba(255, 255, 255, 0.2);
}
        nav ul {
        list-style-type: none;
        margin: 0;
        padding: 0;
        display: flex;
        justify-content: space-around;
        background-color: #356791;
        border-radius: 8px;
        overflow: hidden;
    }

    nav ul li {
        transition: transform 0.3s ease-out;
    }

    nav ul li a {
        display: block;
        color: #fff;
        padding: 15px 30px;
        text-decoration: none;
        transition: background-color 0.3s ease;
        position: relative;
    }

    nav ul li a:before {
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background: rgba(255, 255, 255, 0);
        transition: background 0.3s ease;
    }


    nav ul li {
        transition: transform 0.3s ease-out;
    }

    nav ul li a {
        display: block;
        color: #fff;
        padding: 15px 30px;
        text-decoration: none;
        transition: background-color 0.3s ease;
        position: relative;
    }

    nav ul li a:before {
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background: rgba(255, 255, 255, 0);
        transition: background 0.3s ease;
    }

    nav ul li a:hover:before {
        background: rgba(255, 255, 255, 0.2);
    }
        /* Общие стили */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
            line-height: 1.6;
        }

        header {
            background-color: #fff;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            padding: 20px;
            text-align: center;
        }

        h1, h2 {
            margin: 0;
            font-size: 36px;
            color: #356791;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        a {
            text-decoration: none;
            color: #333;
        }

        main {
            padding: 20px;
            text-align: center;
        }

        section {
            margin-bottom: 40px;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: left;
            opacity: 0;
            transition: opacity 0.5s ease;
        }

        section.active {
            opacity: 1;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #fff;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        /* Форма обратной связи */
        form {
            max-width: 400px;
            margin: 0 auto;
        }

        input[type="text"],
        input[type="email"],
        textarea {
            width: calc(100% - 22px);
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
            background-color: #fff;
            color: #333;
        }

        input[type="submit"] {
            background-color: #356791;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        input[type="submit"]:hover {
            background-color: #28536b;
        }

        /* Медиа запросы для адаптивности */


         @media screen and (max-width: 1080px) {


            header {
                padding: 10px;
            }
            h1, h2 {
                font-size: 28px;
            }
            nav ul li {
                display: block;
                margin-bottom: 10px;
            }
            main {
                padding: 10px;
            }
            section {
                margin-bottom: 20px;
                padding: 15px;
            }
            input[type="text"],
            input[type="email"],
            textarea {
                width: calc(100% - 20px);
            }
        }
         @media screen and (max-width: 2160px) {


            header {
                padding: 10px;
            }
            h1, h2 {
                font-size: 28px;
            }
            nav ul li {
                display: block;
                margin-bottom: 10px;
            }
            main {
                padding: 10px;
            }
            section {
                margin-bottom: 20px;
                padding: 15px;
            }
            input[type="text"],
            input[type="email"],
            textarea {
                width: calc(100% - 20px);
            }
        }
        @media screen and (max-width: 1440px) {


            header {
                padding: 10px;
            }
            h1, h2 {
                font-size: 28px;
            }
            nav ul li {
                display: block;
                margin-bottom: 10px;
            }
            main {
                padding: 10px;
            }
            section {
                margin-bottom: 20px;
                padding: 15px;
            }
            input[type="text"],
            input[type="email"],
            textarea {
                width: calc(100% - 20px);
            }
        }

        /* Кнопки навигации */
        .navigation {
            text-align: center;
            margin-top: 20px;
        }

        .navigation a {
            padding: 8px 16px;
            margin: 0 8px;
            border: 1px solid #356791;
            color: #356791;
            text-decoration: none;
            border-radius: 4px;
            transition: background-color 0.3s ease;
        }

        .navigation a:hover {
            background-color: #356791;
            color: #fff;
        }

        /* Стили для раздела "Главная" */
        .special-content {
            background-color: #f0f0f0;
            padding: 30px;
            border-radius: 8px;
            margin: 20px 0;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
    </style>
</head>
<body>
<header>
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS8hEQ3OY0g8cnsVKsCFS9eObzYqKkXZ67on4zZpb3n8Q&s" alt="Логотип ITII">
    <h1>МЕЖДУНАРОДНЫЙ ТАРАЗСКИЙ
        ИННОВАЦИОННЫЙ ИНСТИТУТ
        ИМ.Ш.МУРТАЗЫ</h1>
    <nav>
        <ul>
            <li><a href="#home">Главная</a></li>
            <li><a href="#about">О нас</a></li>
            <li><a href="#events">События</a></li>
            <li><a href="#contact">Контакты</a></li>
            <li><a href="https://example.com" target="_blank">Другие ресурсы</a></li>
        </ul>
    </nav>
</header>

<main>
    <section id="home" class="active">
        <div class="special-content">
            <h2>Добро пожаловать в наш университет!</h2>
            <p>Здесь можно разместить информацию о вашем университете, особенности обучения или преимущества, которые он предоставляет.</p>
        </div>
    </section>

    <section id="about">
        <h2>О нас</h2>
        <p>Университет предлагает широкий спектр курсов и программ обучения. Наш факультет постоянно стремится предоставить наилучшее образование и помощь студентам.</p>
    </section>

    <section id="events">
        <h2>События</h2>
        <p>Не упустите наши предстоящие семинары, лекции и мероприятия. Следите за обновлениями нашего расписания событий.</p>
    </section>

    <section id="contact">
        <h2>Контакты</h2>
        <form action="#" method="post">
            <label for="name">Имя:</label><br>
            <input type="text" id="name" name="name" required><br><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" required><br><br>
            <label for="message">Сообщение:</label><br>
            <textarea id="message" name="message" rows="4" required></textarea><br><br>
            <input type="submit" value="Отправить">
        </form>
    </section>
</main>

<footer>
    <p>&copy; 2023 Университет. Все права защищены.</p>
</footer>

<script>
    document.querySelectorAll('nav a').forEach(anchor => {
        anchor.addEventListener('click', function(e) {
            e.preventDefault();
            const sectionId = this.getAttribute('href');
            document.querySelector(sectionId).scrollIntoView({
                behavior: 'smooth'
            });
        });
    });

    const sections = document.querySelectorAll('section');
    const options = {
        threshold: 0.3
    };

    const observer = new IntersectionObserver(function(entries, observer) {
        entries.forEach(entry => {
            if (entry.isIntersecting) {
                entry.target.classList.add('active');
                observer.unobserve(entry.target);
            }
        });
    }, options);

    sections.forEach(section => {
        observer.observe(section);
    });
</script>
</body>
</html>

