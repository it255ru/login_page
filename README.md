# Задача

Разобратся как устроена авторизация по паролю в web-приложениях от простого к сложному.

## 01. JS Авторизация и переход на следующую страницу

Я набросал страничку авторизации "Simple Login Page". Разместил поле логин и пароль. Добавил две кнопки "войти" и "сброс". После того, как я ввожу логин и пароль нажимается кнопка "войти". Отправляется запрос логин и пароль в  JS-скрипт, встроенный в страницу "Simple Login Page". На стороне клиента проверяются логин и пароль, если логин и пароль совпадают - открывается страница "target.html" с произвольным содержимым. Иначе, если пароль или логин не верный, то выводит ошибку авторизации сгенерированный JS-скриптом.


