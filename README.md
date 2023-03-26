# MySQL_GB

Изучение реляционной БД MySQL на платформе GeekBrains. 
Резульататом знаний является сдача курсового проекта с использванием всего изученного материала(DLL, DML, DQL комманды).   

### Lesson_1. DDL-команды
[Заполнить все таблицы БД vk данными (по 10-100 записей в каждой таблице).](https://github.com/ZoooMX/MySQL_GB/blob/main/1-4_lesson/%D0%94%D0%BE%D0%BC%D0%B0%D1%88%D0%BD%D1%8F%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%20%D0%BA%20%D0%A3%D1%80%D0%BE%D0%BA%D1%83%204.%20%D0%92%D0%B5%D0%B1%D0%B8%D0%BD%D0%B0%D1%80.%20CRUD-%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%86%D0%B8%D0%B8.sql)

### Lesson_2. Управление БД. Язык запросов SQL
[Написать скрипт, возвращающий список имен (только firstname) пользователей без повторений в алфавитном порядке.](https://github.com/ZoooMX/MySQL_GB/blob/main/1-4_lesson/%D0%94%D0%BE%D0%BC%D0%B0%D1%88%D0%BD%D1%8F%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%20%D0%BA%20%D0%A3%D1%80%D0%BE%D0%BA%D1%83%204.%20%D0%92%D0%B5%D0%B1%D0%B8%D0%BD%D0%B0%D1%80.%20CRUD-%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%86%D0%B8%D0%B8.sql) (в скрипте после 1 задачи)

### Lesson_3. Введение в проектирование БД
[Первые пять пользователей пометить как удаленные.](https://github.com/ZoooMX/MySQL_GB/blob/main/1-4_lesson/%D0%94%D0%BE%D0%BC%D0%B0%D1%88%D0%BD%D1%8F%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%20%D0%BA%20%D0%A3%D1%80%D0%BE%D0%BA%D1%83%204.%20%D0%92%D0%B5%D0%B1%D0%B8%D0%BD%D0%B0%D1%80.%20CRUD-%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%86%D0%B8%D0%B8.sql) (в скрипте после 2 задачи)

### Lesson_4. CRUD-операции
[Написать скрипт, удаляющий сообщения «из будущего» (дата больше сегодняшней).](https://github.com/ZoooMX/MySQL_GB/blob/main/1-4_lesson/%D0%94%D0%BE%D0%BC%D0%B0%D1%88%D0%BD%D1%8F%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%20%D0%BA%20%D0%A3%D1%80%D0%BE%D0%BA%D1%83%204.%20%D0%92%D0%B5%D0%B1%D0%B8%D0%BD%D0%B0%D1%80.%20CRUD-%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%86%D0%B8%D0%B8.sql) (в скрипте после 3 задачи)

 
### Написать название темы курсового проекта.
##### Тема: 
Организация охраны труда на предприятии.
##### Описание процесса внутри организации: 
Для получения допуска к работе сотрудник должен пройти медосмотр по необходимым пунктам, 
несколько инструктажей, обучение и проверку зананий по охране труда. Формируются записи 
для инструктажей и обучения с разной периодичностью в зависимости от должности.
Виды инструктажей: Вводный, первичный, повторный, первичный по пожарной безопасности. 
Виды обучения с проверкой знаний: охрана труда по виду работ(руководитель/специаилст или рабочий), 
электробезопасность, первая помощь, промышленная безопасность (только для руководителей и специалистов).
Возможно включу рейтинг работника по нарушениям после обучения с целью выявления 
злокачественного сотрудника для формирования списка на депремирование или увольнения.

### Lesson_5. Операторы, фильтрация, сортировка и ограничение. Агрегация данных. 
##### Практическое задание по теме «Операторы, фильтрация, сортировка и ограничение»
1. Пусть в таблице users поля created_at и updated_at оказались незаполненными. 
Заполните их текущими датой и временем.
2. Таблица users была неудачно спроектирована. Записи created_at и updated_at были 
заданы типом VARCHAR и в них долгое время помещались значения в формате 20.10.2017 8:10. 
Необходимо преобразовать поля к типу DATETIME, сохранив введённые ранее значения.
3. В таблице складских запасов storehouses_products в поле value могут встречаться 
самые разные цифры: 0, если товар закончился и выше нуля, если на складе имеются запасы. 
Необходимо отсортировать записи таким образом, чтобы они выводились в порядке увеличения 
значения value. Однако нулевые запасы должны выводиться в конце, после всех записей.
4. (по желанию) Из таблицы users необходимо извлечь пользователей, 
родившихся в августе и мае. Месяцы заданы в виде списка английских 
названий (may, august)
5. (по желанию) Из таблицы catalogs извлекаются записи при помощи запроса. 
SELECT * FROM catalogs WHERE id IN (5, 1, 2); Отсортируйте записи в порядке, 
заданном в списке IN.
##### Практическое задание теме «Агрегация данных»
1. Подсчитайте средний возраст пользователей в таблице users.
3. (по желанию) Подсчитайте произведение чисел в столбце таблицы.
##### Выполнение:
[sql_скрипт](https://github.com/ZoooMX/MySQL_GB/blob/main/5_lesson/%D0%94%D0%BE%D0%BC%D0%B0%D1%88%D0%BD%D1%8F%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%20%D0%BD%D0%B0%20%D0%A3%D1%80%D0%BE%D0%BA%205.%20%D0%92%D0%B8%D0%B4%D0%B5%D0%BE%D1%83%D1%80%D0%BE%D0%BA.%20.sql)

### Lesson_6. Операторы, фильтрация, сортировка и ограничение. Агрегация данных. 
[Исходные данные](https://github.com/ZoooMX/MySQL_GB/blob/main/6_lesson/vk_db_seed.sql)
##### Практическое задание по теме “Операторы, фильтрация, сортировка и ограничение. Агрегация данных”
1. Пусть задан некоторый пользователь. Из всех друзей этого пользователя найдите человека, который больше всех общался с нашим пользователем.
2. Подсчитать общее количество лайков, которые получили пользователи младше 11 лет.
3. Определить кто больше поставил лайков (всего): мужчины или женщины.
##### Выполнение:
[sql_скрипт](https://github.com/ZoooMX/MySQL_GB/blob/main/6_lesson/HW_6_lesson.sql)

### Lesson_7. Сложные запросы. 
[Исходные данные](https://github.com/ZoooMX/MySQL_GB/blob/main/7_lesson/DB_and_HW_for_7_lesson.sql)
##### Практическое задание по теме "Сложные запросы."
1. Составьте список пользователей users, которые осуществили хотя бы один заказ orders в интернет магазине.
2. Выведите список товаров products и разделов catalogs, который соответствует товару.
3. (по желанию) Пусть имеется таблица рейсов flights (id, from, to) и таблица городов cities (label, name). Поля from, to и label содержат английские названия городов, поле name — русское. Выведите список рейсов flights с русскими названиями городов.
##### Выполнение:
[sql_скрипт](https://github.com/ZoooMX/MySQL_GB/blob/main/7_lesson/DB_and_HW_for_7_lesson.sql)

### Lesson_8. Сложные запросы. 
##### Практическое задание по теме "Сложные запросы."
1. Пусть задан некоторый пользователь id=1. Из всех друзей этого пользователя найдите человека, который больше всех общался с выбранным пользователем (написал ему сообщений).
2. Подсчитать общее количество лайков, которые получили пользователи младше 11 лет.
3. (Определить кто больше поставил лайков (всего): мужчины или женщины.
##### Выполнение:
[sql_скрипт](https://github.com/ZoooMX/MySQL_GB/blob/main/8_lesson/WH_for_8_lesson.sql)

### Lesson_9. Транзакции, переменные, представления. Хранимые процедуры
##### Практическое задание по теме "Транзакции, переменные, представления. Хранимые процедуры"
1. В базе данных shop и sample присутствуют одни и те же таблицы, учебной базы данных. Переместите запись id = 1 из таблицы shop.users в таблицу sample.users. Используйте транзакции.
4. Создайте хранимую функцию hello(), которая будет возвращать приветствие, в зависимости от текущего времени суток. С 6:00 до 12:00 функция должна  возвращать фразу "Доброе утро", с 12:00 до 18:00 функция должна возвращать фразу "Добрый день", с 18:00 до 00:00 — "Добрый вечер", с 00:00 до 6:00 — "Доброй ночи".
##### Выполнение:
[sql_скрипт](https://github.com/ZoooMX/MySQL_GB/blob/main/9_lesson/HW_9_lesson.sql)

