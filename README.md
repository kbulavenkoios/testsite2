<!DOCTYPE html>   <!-- Заголовок - вказує що це HTML 5 -->
<html lang="uk">  <!-- Відкриваючий тег HTML  -->
<head>   <!-- Відкриваючий тег заголовка який містить мета-теги, назву сторінки або вкладки у браузері  -->
    <meta charset="UTF-8">    <!-- Кодова сторінка файлу HTML  -->
    
    <!-- Сумісність з мобільними пристроями  -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Заголовок вікна або вкладинки у браузері  -->
    <title>Сучасна HTML-сторінка</title>

    <!-- Загрузка каскадної таблиці стилів -->
   <link rel="stylesheet" href="styles.css">  <!-- Підключення CSS -->
</head>  <!-- Закриваючий тег блоку заголовка та метатегів  -->
<body>   <!-- Відкриваючий тег body - початок змісту сторінки  -->
   <div class="wrap"> 
    <header>    <!-- Відкриваючий тег header   - існує тільки в HTML 5.0 і вище  -->
        <h1>Ласкаво просимо!</h1>   <!-- Заголовок першого рівня  -->
        <nav>   <!-- Відкриваючий тег меню  -->
            <ul>   <!-- Відкриваючий тег списка  -->
                <li><a href="#">Головна</a></li>    <!-- Елементи списка  -->
                <li><a href="#">Про нас</a></li>    <!-- наступний елемент списка  -->
                <li><a href="#">Контакти</a></li>   <!-- наступний елемент списка  -->
            </ul>  <!-- Закриваючий тег списка  -->
        </nav>   <!-- Закриваючий тег меню   -->
    </header>  <!-- Закриваючий тег секції header  -->

    <section>  <!-- Відриваючий тег секції section  - містить основну інформацію сторінки  -->
        <h1>Це найбільший заголовок</h1>   <!-- Заголовок першого рівня  -->
        <h2>Трішки менший заголовок</h2>   <!-- Заголовок другого рівня  -->
        <h3>Ще менший</h3>   <!-- Заголовок третього рівня  -->
        <h4>Менше</h4>   <!-- Заголовок четвертого  рівня  -->
        <h5>Дуже маленький</h5>   <!-- Заголовок п'того  рівня  -->
        <h6>Найменший</h6>   <!-- Заголовок шостого рівня  -->
        <p>Text</p>      <!-- Текст відокремлений тегом абзаца  -->
        <p><img src="myimage1.jpg" alt="Моя картинка має бути тут" width="300"></img></p>
        <p>        <!-- Посилання на гугл відокремлено сайтом абзаца  -->
        <a href="https://google.com.ua" target="_blank">Перейти в Гугл</a>
        </p>
        <h2>Про нас</h2>    <!-- Заголовок другого рівня  -->
        <p>Це сучасний шаблон HTML-сторінки.</p>   <!-- Інформаційний текст сайту відокрмелений абзацом  -->
        <p></p>
        <p></p>
        <p></p>
        <p>123...  мене не видно  &#41;&#41; &amp;#41; <code>&#41;</code> </p>
    </section>  <!-- Закриваючий тег секції section -->
   </div> 
    <footer>   <!-- Відкриваючий тег секції footer -->
        <!-- Віддокремлений абзацем текст секції який містить спеціальний символ копірайта  &copy;  -->
        <p>&copy; 2025 Усі права захищені </p>
    </footer>  <!-- Закриваючий тег секції footer -->
    <script src="script.js"></script> <!-- Визов джава скрипта який має привітати користувача на сторінці -->
</body>   <!-- Відкриваючий тег секції body -->
</html>   <!-- Закриваючий тег HTML  -->