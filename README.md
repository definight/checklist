## Here's example of checklist made by me

| Версия      |   1.0  |  |   |
| --- | --- |--- |--- |
| Окружение   |   Windows 10 Pro      |    |    |
| Даты тестирования   |     22.12.22 - 23.12.22    |    |    |
| Проверка   |    Результат     |Комментарии    |Тип теста    |
| **Анкета**   |    **bugs**     |     |    |
| Ввод в поле "Имя" текста в верхнем и нижнем регистре   |    ok     |    |![positive](https://img.shields.io/badge/-positive-378805?style=for-flat-square)    |
| Ввод в поле "Имя" спецсимволов   |    ok     |    |![positive](https://img.shields.io/badge/-positive-378805?style=for-flat-square)    |
| Ввод в поле "Имя" неограниченного числа латинских символов   |    failed     |bug#1    |![negative](https://img.shields.io/badge/-negative-580818?style=for-flat-square)    |
|Ввод в поле "Имя" цифр   |   failed      |bug#2    |![negative](https://img.shields.io/badge/-negative-580818?style=for-flat-square)    |
|Пустое поле  |     ok |      | ![negative](https://img.shields.io/badge/-negative-580818?style=for-flat-square) |
|Ввод в поле "Имя" нескольких пробелов   |   ok   |    |![negative](https://img.shields.io/badge/-negative-580818?style=for-flat-square)    |
| Ввод в поле "Имя" пробела до текста   |failed    |bug#3    |![negative](https://img.shields.io/badge/-negative-580818?style=for-flat-square)    |
| **Личный кабинет**   |    **bugs**     |     |    |
| Ввод в поле "Логин" текста в верхнем и нижнем регистре   |    ok     |    |![positive](https://img.shields.io/badge/-positive-378805?style=for-flat-square)    |
| Ввод в поле "Логин" спецсимволов   |    ok     |    |![positive](https://img.shields.io/badge/-positive-378805?style=for-flat-square)    |
| Ввод в поле "Логин" цифр   |    ok     |    |![positive](https://img.shields.io/badge/-positive-378805?style=for-flat-square)    |
|Ввод в поле "Логин" текста из русских букв   |   failed      |bug#4   |![negative](https://img.shields.io/badge/-negative-580818?style=for-flat-square)    |
|Ввод в поле "Логин" большого числа (>1000) латинских символов  |     failed |   bug#5   | ![negative](https://img.shields.io/badge/-negative-580818?style=for-flat-square) |
|Пустое поле "Логин"  |   ok   |    |![negative](https://img.shields.io/badge/-negative-580818?style=for-flat-square)    |
| Ввод в поле "Логин" нескольких пробелов   |ok    |   |![negative](https://img.shields.io/badge/-negative-580818?style=for-flat-square)    |
| **Обратная связь**   |    **bugs**     |     |    |
| Выбор в календаре буднего дня в текущем месяце   |    ok     |    |![positive](https://img.shields.io/badge/-positive-378805?style=for-flat-square)    |
| Выбор в календаре буднего дня в следующем месяце   |    ok     |    |![positive](https://img.shields.io/badge/-positive-378805?style=for-flat-square)    |
| Выбор в календаре буднего дня в следующем году   |    ok     |    |![positive](https://img.shields.io/badge/-positive-378805?style=for-flat-square)    |
|Выбор в календаре выходного дня   |   failed      |bug#6   |![negative](https://img.shields.io/badge/-negative-580818?style=for-flat-square)    |
|Выбор в календаре дня из прошедших дней  |     failed |   bug#7   | ![negative](https://img.shields.io/badge/-negative-580818?style=for-flat-square) |
|Выбор времени начала интервала для звонка в указанном диапазоне  |   ok   |    |![positive](https://img.shields.io/badge/-positive-378805?style=for-flat-square)    |
| Выбор времени конца интервала для звонка в указанном диапазоне   |ok    |   |![positive](https://img.shields.io/badge/-positive-378805?style=for-flat-square)    |
| **Pairwise-тестирование**   |    **bugs**     |     |    |
| холост/не замужем, Россия, 24, Жен, дети есть, Неполное высшее   |    ok     |    |![positive](https://img.shields.io/badge/-positive-378805?style=for-flat-square)    |
| холост/не замужем, Казахстан, 28, Жен, дети есть, Высшее    | ok |  |![positive](https://img.shields.io/badge/-positive-378805?style=for-flat-square)    |
| в гражданском браке, Казахстан, 28, Муж, детей нет, Неполное Высшее   |    ok     |    |![positive](https://img.shields.io/badge/-positive-378805?style=for-flat-square)    |
|в гражданском браке, Казахстан, 24, Жен, дети есть, Высшее   |   ok      | |![positive](https://img.shields.io/badge/-positive-378805?style=for-flat-square)    |
|холост/не замужем, Казахстан, 27, Жен, дети есть, Доктор наук  |     failed |   bug#8  | ![positive](https://img.shields.io/badge/-positive-378805?style=for-flat-square) |
|в гражданском браке, Россия, 30, Жен, дети есть, Неполное Высшее  |   ok   |    |![positive](https://img.shields.io/badge/-positive-378805?style=for-flat-square)    |
| Выбор времени конца интервала для звонка в указанном диапазоне   |ok    |   |![positive](https://img.shields.io/badge/-positive-378805?style=for-flat-square)    |
