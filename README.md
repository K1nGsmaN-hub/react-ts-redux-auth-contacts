# Менеджер контактов (в разработке)
Приложение является менеджером ваших контактов. Вы можете зайти под своим пользователем или создать нового. После входа, вас перенаправит на страницу менеджера.\
Интерфейс менеджера состоит из двух частей:
* зона контактов
* зона действия (рабочий стол)

В зоне контактов отображаются ваши контакты, если контактов ещё нет, то вы можете нажать на плюсик в правом верхнем углу. Откороется форма, после заполнения которой ваш контакт отобразится в списке.\
При нажатии на контакт, он открывается в зоне действий, где показана информация о нем (контакте). В зоне действий вы можете удалить контакт, по нажатию кнопки "Удалить" или отредактировать контакт, при нажатии кнопки "Редактировать". При редактировании контакта, открывается форма, после заполнения и откправки которой, изменения применятся, и Ваш контакт обновится.\
Если Вы хотите завершить работу с приложением, нажмите на красный кнопку в левом верхнем углу.

## От себя
Это приложение является новой версией моего старого приложения, написанного 5 месяцев назад. Старое приложение находится [https://github.com/K1nGsmaN-hub/react-auth-contacts](тут)\
Старое приложение было написанно, в качестве тестового задания одной из компаний, куда я подавал резюме. Тогда оно мне очень понравилось и недавно, я решил переписать его, с новыми знаниями и технологиями.\
Итак, в это приложении используются технологии: `ReactJS`, `TypeScript`, `Redux`, `Redux-thunk`, `Redux-saga`, `StyledComponent`, `React-router`

Проект был создан с использование утилиты **`create-react-app`**

Это мой первый опыт написания документации, к своему проекту, если есть замечания, кидайте pull request'ы. (Документация ещё не полная)

## Инициализация проекта

Перед запуском проекта, откройте терминал в папке с проектом и введите:

### `yarn`

В проекте используется утилита **`json-server`**, если она у Вас не установлена, введите в терминал:

Для глобальной установки ( [ ] - необязательный параметр):
### `[sudo] npm i -g json-server`

Для установки внутри проекта, из папки с проектом, введите в терминал:
### `yarn add json-server`

## Запуск проекта

**Для старта проекта необходимо открыть два окна с терминалом в папке с проектом!**

В-первом окне с терминалом, вводим:
### `yarn start`

Во-втором окне с терминалом, вводим:
### `json-server db.json --port 3001`

Проект откроется в режиме разработки по адресу [http://localhost:3000](http://localhost:3000)

