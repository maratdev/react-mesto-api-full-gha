[![Статус тестов](../../actions/workflows/tests.yml/badge.svg)](../../actions/workflows/tests.yml)

# Проект Mesto бэкенд + frontend
 _***Проектная работа №15. Курс «Веб-разработчик» от Яндекс Практикум.***_

## Технологии:
  <a href="https://expressjs.com/ru/" target="_blank" rel="noreferrer"><img src="https://img.shields.io/badge/-Express-090909?style=for-the-badge&logo=Express" alt="Express" /></a>
  <a href="https://nodejs.org/ru" target="_blank" rel="noreferrer"><img src="https://img.shields.io/badge/-Node.js-090909?style=for-the-badge&logo=Node.js" alt="Node.js" /></a>
  <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"><img src="https://img.shields.io/badge/-MongoDB-090909?style=for-the-badge&logo=MongoDB" alt="MongoDB" /></a>
  <a href="https://www.postman.com/" target="_blank" rel="noreferrer"><img src="https://img.shields.io/badge/-Postman-090909?style=for-the-badge&logo=Postman" alt="Postman" /></a>
  <a href="https://eslint.org/" target="_blank" rel="noreferrer"><img src="https://img.shields.io/badge/-Eslint-090909?style=for-the-badge&logo=Eslint&logoColor=blue" alt="Eslint" /></a>
  <a href="https://jwt.io/" target="_blank" rel="noreferrer"><img src="https://img.shields.io/badge/-Jsonwebtokens-090909?style=for-the-badge&logo=json-web-tokens&logoColor=d63aff" alt="jwt" /></a>

### Функционал:

+ Регистрация
+ Авторизация
+ Обновление данных пользователя
+ Обновление аватара
+ Получение списка пользователя
+ Получение пользователя по ID
+ Получение информации о текущем пользователе
+ Получение списка карточек
+ Создание карточки
+ Удаление карточки
+ Постановка лайка
+ Снятие лайка
+ Центральная обработка ошибок
+ Валидация входящих данных
+ Защитита API авторизации
+ Деплой на Яндекс.Облако
------
### О чём проект?

*Данное серверное приложение предназначено для храниния и обмена файлами с вэб-приложением Mesto.*

* Возможность зарегестрироваться и залогиниться с помощью почты и пароля. Токен для авторизации хранится 7 дней.
* У каждого пользователя есть поля name, about, avatar, email, password. Их можно задать при регистрации. Если не задать name, about или avatar, то установятся дефолтные.
* Поля name, about, avatar можно обновить после регистрации.
* Можно создавать карточки. У каждой каточки есть есть поля name, link (ссылка на картинку), owner (id создателя карточки), createdAt (дата создания карточки) и массив likes (лайков карточки, которые могут ставить пользователи).
* Карточки можно создавать и удалять, а также лайкать.
* Поля валидируются (например ссылки или email).
------

### Ссылки на проект

IP-адрес 51.250.26.68   
Frontend <a href="https://voredev.nomoredomains.xyz/" target="_blank" rel="noreferrer">https://voredev.nomoredomains.xyz</a>   
Backend <a href="https://api.nomoredomains.xyz/" target="_blank" rel="noreferrer">https://api.nomoredomains.xyz</a>


Репозиторий:

```bash
git clone https://github.com/maratdev/react-mesto-api-full-gha/
```
