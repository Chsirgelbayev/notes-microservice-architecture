# Сервис заметок

Микросервис пользователей

Хост: https://usermicroserviceapp.herokuapp.com

-   [**Регистрация**](https://usermicroserviceapp.herokuapp.com/auth/register) - Метод: POST, Поля: name, email, password. После регистрация приходит cообщение на почту mail.ru;
```Javascript
  body: {
    "name": "Jonh Doe",
    "email": "doe@mail.ru",
    "password": "1234AB1234a"
  }
```
-   [**Авторизация**](https://usermicroserviceapp.herokuapp.com/auth/login) - Метод: POST, Поля: email, password;
```Javascript
  body: {
    "email": "doe@mail.ru",
    "password": "1234AB1234a"
  }
```
-   [**Создать пользователя**](https://usermicroserviceapp.herokuapp.com/users) - Метод: POST, Поля: name, email, password;
-   [**Получить список всех пользователей**](https://usermicroserviceapp.herokuapp.com/users) - Метод:GET;
-   [**Получить пользователя**](https://usermicroserviceapp.herokuapp.com/users/:id) - Метод: GET;
-   [**Обновить пользователя**](https://usermicroserviceapp.herokuapp.com/users/:id) - Метод: PUT;
```Javascript
  body: {
    "email": "doe@mail.ru",
     "name": "Jonh Doe"
  }
```
-   [**Удалить пользователя**](https://usermicroserviceapp.herokuapp.com/users/:id) - Метод: DELETE;


Микросервис Записей

Хост: https://recordsmicroserviceapp.herokuapp.com

-   [**Создать запись**](https://recordsmicroserviceapp.herokuapp.com/records) - Метод: POST, Поля: title, body;
```Javascript
  body: {
    "title": "test_record",
     "body": "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has "
  }
```
-   [***Обновить запись**](https://usermicroserviceapp.herokuapp.com/users/:id) - Метод: PUT, Поля: title, body;
```Javascript
  body: {
    "title": "test_record",
    "body": "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has "
}
```
-   [**Получить список всех записей**](https://usermicroserviceapp.herokuapp.com/users) - Метод:GET;
-   [**Получить запись**](https://usermicroserviceapp.herokuapp.com/users/:id) - Метод: GET;
-   [**Удалить запись**](https://recordsmicroserviceapp.herokuapp.com/records/2) - Метод: DELETE;

Миеросервис Email-рассылки

Хост: https://emailmicroserviceapp.herokuapp.com/


