# EDKI v0.1.7

[Завантажити версію 0.1.7](https://github.com/ArchExalt/EDKIApp/blob/main/EDKI-v0.1.7.apk)

Оновлення v0.1.7 (10.06.2023):

- оновлено глосарій;
- змінено піктограми для нумерації модулів.

Додаток, створений для підготовки до Єдиного Державного Кваліфікаційного Іспиту за спеціальністю 125 (Кібербезпека та захист інформації).
Планується створення 7 курсів, що складаються більш ніж з 20 тем для вивчення (кожна з тем містить до 12 коротких лекцій)/

Поточний функціонал:
- вхід через обліковий запис Google та вихід з нього (Firebase Authentication);
- зворотній зв'язок (Realtime Firebase);
- тестування за всіма модулями та за кожним окремо (у випадковій послідовності);
- перемикання між світлою/темною темою (sharedPreferences);
- можливість відмічати прапорцями пройдені модулі та теми (sharedPreferences);
- статистика щодо кількості завершених лекцій (sharedPreferences).

Реалізовано:
- Курси: навігація, список тем та шаблони лекцій для першого курсу;
- Глосарій: список корисних аббревіатур українською та англійською;
- Тести: тестування за всіма модулями, за кожним окремо та відображення результатів;
- Профіль: зміна теми, відображення фото та імені користувача, інформація про розробника та версію, зворотній зв'язок, кількість завершений лекцій.

- 7 курсів, що складаються з 20+ тем (кожна тема містить <15 лекцій);
- глосарій (словник основних аббревіатур);
- тестування за 10 випадковими запитаннями з усіх модулів та за кожним окремо.

Баги:
- відсутність плавного переходу до інтерфейсу додатка після автентифікації;
- чорний екран тривалістю 1 с після перемикання теми.
