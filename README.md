## Here's example of checklist made by me

| Версия      |   1.0  |  |   |
| --- | --- |--- |--- |
| Окружение   |   Windows 10 Pro      |    |    |
| Даты тестирования   |     22.12.22 - 23.12.22    |    |    |
| Проверка   |    Результат     |Комментарии    |Тип теста    |
| **Анкета**   |    **bugs**     |     |    |
| Ввод в поле "Имя" текста в верхнем и нижнем регистре   |    ok     |    |<span style="color:green">positive</span>    |
| Ввод в поле "Имя" спецсимволов   |    ok     |    |<span style="color:green">positive</span>    |
| Ввод в поле "Имя" неограниченного числа латинских символов   |    failed     |bug#1    |<span style="color:red">negative</span>    |
|Ввод в поле "Имя" цифр   |   failed      |bug#2    |<span style="color:red">negative</span>    |
|Пустое поле  |     ok |      | <span style="color:red">negative</span> |
|Ввод в поле "Имя" нескольких пробелов   |   ok   |    |<span style="color:red">negative</span>    |
| Ввод в поле "Имя" пробела до текста   |failed    |bug#3    |<span style="color:red">negative</span>    |
| **Личный кабинет**   |    **bugs**     |     |    |
| Ввод в поле "Логин" текста в верхнем и нижнем регистре   |    ok     |    |<span style="color:green">positive</span>    |
| Ввод в поле "Логин" спецсимволов   |    ok     |    |<span style="color:green">positive</span>    |
| Ввод в поле "Логин" цифр   |    ok     |    |<span style="color:green">positive</span>    |
|Ввод в поле "Логин" текста из русских букв   |   failed      |bug#4   |<span style="color:red">negative</span>    |
|Ввод в поле "Логин" большого числа (>1000) латинских символов  |     failed |   bug#5   | <span style="color:red">negative</span> |
|Пустое поле "Логин"  |   ok   |    |<span style="color:red">negative</span>    |
| Ввод в поле "Логин" нескольких пробелов   |ok    |   |<span style="color:red">negative</span>    |
| **Обратная связь**   |    **bugs**     |     |    |
| Выбор в календаре буднего дня в текущем месяце   |    ok     |    |<span style="color:green">positive</span>    |
| Выбор в календаре буднего дня в следующем месяце   |    ok     |    |<span style="color:green">positive</span>    |
| Выбор в календаре буднего дня в следующем году   |    ok     |    |<span style="color:green">positive</span>    |
|Выбор в календаре выходного дня   |   failed      |bug#6   |<span style="color:red">negative</span>    |
|Выбор в календаре дня из прошедших дней  |     failed |   bug#7   | <span style="color:red">negative</span> |
|Выбор времени начала интервала для звонка в указанном диапазоне  |   ok   |    |<span style="color:green">positive</span>    |
| Выбор времени конца интервала для звонка в указанном диапазоне   |ok    |   |<span style="color:green">positive</span>    |
| **Pairwise-тестирование**   |    **bugs**     |     |    |
| холост/не замужем, Россия, 24, Жен, дети есть, Неполное высшее   |    ok     |    |<span style="color:green">positive</span>    |
| холост/не замужем, Казахстан, 28, Жен, дети есть, Высшее    | ok |  |<span style="color:green">positive</span>    |
| в гражданском браке, Казахстан, 28, Муж, детей нет, Неполное Высшее   |    ok     |    |<span style="color:green">positive</span>    |
|в гражданском браке, Казахстан, 24, Жен, дети есть, Высшее   |   ok      | |<span style="color:green">positive</span>    |
|холост/не замужем, Казахстан, 27, Жен, дети есть, Доктор наук  |     failed |   bug#8  | <span style="color:green">positive</span> |
|в гражданском браке, Россия, 30, Жен, дети есть, Неполное Высшее  |   ok   |    |<span style="color:green">positive</span>    |
| Выбор времени конца интервала для звонка в указанном диапазоне   |ok    |   |<span style="color:green">positive</span>    |