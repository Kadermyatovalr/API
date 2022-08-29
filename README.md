Тестирование API, Postman Здесь можно ознакомиться с запросами и ответами к сервису DummyApi при помощи Postman
### Запрос на создание нового пользователя:
![Запрос](https://github.com/Kadermyatovalr/API/blob/main/%D1%81%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/%D0%97%D0%B0%D0%BF%D1%80%D0%BE%D1%81%20%D0%BD%D0%B0%20%D0%B4%D0%BE%D0%B1%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BD%D0%BE%D0%B2%D0%BE%D0%B3%D0%BE%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F1.jpg)
### Ответ на создание нового пользователя:
![Ответ](https://github.com/Kadermyatovalr/API/blob/main/%D1%81%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/%D0%9E%D1%82%D0%B2%D0%B5%D1%82%20%D0%BD%D0%B0%20%D0%B7%D0%B0%D0%BF%D1%80%D0%BE%D1%81.jpg)
### Получение пользователя по ID
![Получение пользователя по ID, ответ запроса](https://github.com/Kadermyatovalr/Postman/blob/main/%D1%81%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/%D0%BF%D0%BE%D0%B8%D1%81%D0%BA%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F.jpg)

# В тестируемой системе были обнаружены ошибки, такие как:
+ ### PUT запрос допускает сохранения пустого значения для полей firstName, lastName
 Запрос на ввод пустого значения в поля:
![Запрос на ввод пустого значения](https://github.com/Kadermyatovalr/API/blob/main/%D1%81%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/%D0%A1%D0%BC%D0%B5%D0%BD%D0%B0%20%D0%98%D0%BC%D0%B5%D0%BD%D0%B8%20%D0%B8%20%D0%A4%D0%B0%D0%BC%D0%B8%D0%BB%D0%B8%D0%B8.jpg)

Ответ на ввод пустого значения в поля:
![Ответ на ввод пустого значения](https://github.com/Kadermyatovalr/API/blob/main/%D1%81%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/%D0%9E%D1%82%D0%B2%D0%B5%D1%82%20%D0%BD%D0%B0%20%D0%B7%D0%B0%D0%BF%D1%80%D0%BE%D1%81%20%D1%81%D0%BC%D0%B5%D0%BD%D1%8B%20%D1%84%D0%B0%D0%BC%D0%B8%D0%BB%D0%B8%D0%B8%20%D0%B8%20%D0%B8%D0%BC%D0%B5%D0%BD%D0%B8.jpg)

+ ### PUT запрос допускает сохранение 1 буквы в поле firstName, lastName
Запрос на редактирование. В поля "Имя", "Фамилия" вводим 1 букву
![Запрос 1 буква](https://github.com/Kadermyatovalr/Postman/blob/main/%D1%81%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/%D0%97%D0%B0%D0%BF%D1%80%D0%BE%D1%81%20%D0%BD%D0%B0%20%D1%81%D0%BC%D0%B5%D0%BD%D1%83%20%D0%B8%D0%BC%D0%B5%D0%BD%D0%B8%20%D0%BD%D0%B0%201%20%D0%B1%D1%83%D0%BA%D0%B2%D1%83.jpg)

Ответ на запрос редактирование. В поля "Имя", "Фамилия" сохранена 1 буква
![Ответ 1 буква](https://github.com/Kadermyatovalr/Postman/blob/main/%D1%81%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/%D0%9E%D1%82%D0%B2%D0%B5%D1%82%20%D1%81%D0%BC%D0%B5%D0%BD%D1%8B%20%D0%BF%D0%BE%D0%BB%D1%8F%20%D0%B8%D0%BC%D1%8F%20%D0%BD%D0%B0%201%20%D0%B1%D1%83%D0%BA%D0%B2%D1%83.jpg)

+ ### PUT запрос допускает сохранения 51 буквы в полях firstName, lastName
Запрос на редактирование. В поля "Имя", "Фамилия" вводим 51 букву
![Запрос 51 буква](https://github.com/Kadermyatovalr/Postman/blob/main/%D1%81%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/%D0%B7%D0%B0%D0%BF%D1%80%D0%BE%D1%81%2051%20%D0%B1%D1%83%D0%BA%D0%B2%D0%B0%20%D0%B2%20%D0%BF%D0%BE%D0%BB%D0%B5.jpg)

Ответ на запрос редактирование. В поля "Имя", "Фамилия" сохранена 51 буква
![Ответ 51 буква](https://github.com/Kadermyatovalr/Postman/blob/main/%D1%81%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/%D0%BE%D1%82%D0%B2%D0%B5%D1%82%20%D0%BD%D0%B0%20%D0%B2%D0%B2%D0%BE%D0%B4%2051%20%D0%B1%D1%83%D0%BA%D0%B2%D1%8B.jpg)
