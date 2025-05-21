![Header](assets/meditation_calmness_harmony_122011_2560x1080.jpg)

# Greetings 👋
I’m Pavel Dmitrievich, a dedicated QA Specialist with a passion for identifying bugs and enhancing software quality. My goal is to ensure seamless user experiences by collaborating closely with developers and applying meticulous testing methodologies. Committed to improving software, one bug at a time! 🐞🚀

### My skills
| Skill         | Level        | Description                  |
|---------------|--------------|------------------------------|
| ![SQL](https://img.shields.io/badge/SQL-090909?logo=mysql)        | ⭐⭐⭐⭐⭐       | Работа с базами данных       |
| ![Postman](https://img.shields.io/badge/Postman-090909?logo=postman) | ⭐⭐⭐⭐        | Тестирование API             |
| ![Python](https://img.shields.io/badge/Python-090909?logo=python)  | ⭐⭐⭐⭐⭐       | Скриптование и автоматизация |
| ![HTML](https://img.shields.io/badge/HTML-090909?logo=html5)       | ⭐⭐⭐⭐        | Разметка веб-страниц         |
| ![CSS](https://img.shields.io/badge/CSS-090909?logo=css3)          | ⭐⭐⭐⭐        | Стилизация веб-страниц       |
| ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-090909?logo=postgresql) | ⭐⭐⭐⭐⭐       | Работа с реляционными БД     |

### 🌟 Achievements
- **SQL**: Experience working with various databases, including MySQL and PostgreSQL.
- **Postman**: The ability to create and execute API tests to ensure quality.
- **Python**: Used to automate testing and script writing.
- **HTML/CSS**: Knowledge of the basics of web development for creating user interfaces.

### 🎯 Goals
- Continue to develop your skills in testing and automation.
- Explore new technologies and tools to improve software quality.


#  Follow Me 
---
[![Stepik](https://img.shields.io/badge/Stepik-1C1C1C?logo=stepik&logoColor=white&style=for-the-badge)](https://stepik.org/users/546768757/profile)
[![SQL Academy](https://img.shields.io/badge/SQL%20Academy-2D2D2D?logo=database&logoColor=white&style=for-the-badge)](https://sql-academy.org/ru/profile/204238)
[![Telegram](https://img.shields.io/badge/Telegram-3E3E3E?logo=telegram&logoColor=white&style=for-the-badge)](https://t.me/pbnne1)
[![Website](https://img.shields.io/badge/Website-4F4F4F?logo=link&logoColor=white&style=for-the-badge)](https://pbnne.github.io/qa-web-testing/)
---
<details><summary> Подробнее </summary>  

## [LIB-8981] Авторизация существующего пользователя

Приоритет Высокий (High)
Серьезность Критический (Critical)

Предусловия
1. Открыт сайт [www.livelib.ru](https://www.livelib.ru/)
2. Валидные данные для входа  
логин: test01, пароль: Qwerty123
3. Вход не осуществлен

|№| Действия | Ожидаемый результат |
|---|----|----|
|1| Нажать кнопку "Войти" | Открывается окно авторизации |
|2| Ввести логин и нажать кнопку "Продолжить" | Открывается окно ввода пароля |
|3| Ввести невалидный пароль |1. Пользователь не авторизован |
||  | 2. Выдается ошибка "Пользователь с указанными логином и паролем не найден"|
|4| Ввести валидный пароль и нажать кнопку "Войти" | Авторизация прошла успешно, пользователь остался на странице [www.livelib.ru](https://www.livelib.ru/)|

-----
