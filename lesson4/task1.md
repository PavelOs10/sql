# Базы данных и SQL. Обучение в записи
### Урок 4. Семинар: SQL – создание объектов, простые запросы выборки

Задание 1: Создание таблицы с жанрами книг

Создайте таблицу (сущность) с жанрами книг genres.

Перечень полей (атрибутов):

● id – числовой тип, автоинкремент, первичный ключ;

● name – строковый тип, обязательный к заполнению.

Заполните сущность genres следующими данными:
name
Художественная литература
Нехудожественная литература
Детектив
Биография
Наука

```
CREATE TABLE genres (
id INT AUTO_INCREMENT PRIMARY KEY,
name VARCHAR(255) NOT NULL
);

INSERT INTO genres (name) VALUES
('Художественная литература'),
('Нехудожественная литература'),
('Детектив'),
('Биография'),
('Наука');
```
