__Зробити сценарій з ендпойнтами, що перелічені нижче__

__Дати навантаження на 50, 250, 500 потоків__

__Результати прогонів вивантажити в CSV__
Налаштування Jmeter (файл .jmx) вивантажуємо на гіт.

http://5.75.203.123:5005

1) http://5.75.203.123:5005/get_method
req.
GET
name: str
age: int


2) http://5.75.203.123:5005/user_info_2
req.
POST
name: str
age: int
salary: int


3) http://5.75.203.123:5005/user_info_3
req.
POST
name: str
age: int
salary: int

4) http://5.75.203.123:5005/object_info_1
req.
GET
name: str
age: int
weight: int

5) http://5.75.203.123:5005/object_info_2
req.
GET
name: str
age: int
salary: int

6) http://5.75.203.123:5005/object_info_3
req.
GET
name: str
age: int
salary: int

7) http://5.75.203.123:5005/object_info_4
req.
GET
name: str
age: int
salary: int

