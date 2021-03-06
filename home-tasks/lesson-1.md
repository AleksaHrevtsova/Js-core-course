# Критерии приема

1. Код сохранен в репозиторий на Github
2. Имя репозитория js-core-lesson-1
3. В шапке репозитория есть ссылка на живую страницу gh-pages
4. Структура репозитория обязательно файлы:

- index.html - с базовой разметкой и, при необходимости, подключением всех остальных файлов
- index.js - с JavaScript-кодом задания

## Подключение файла с кодом JavaScript в файл index.html:

```
<script src="./index.js" type="module"></script>
```

## Расширения (плагины) в редакторе кода (устанавливаются в разделе, где кнопка "тетриса"):

- Live Server
- Path Intellisense
- Prettier - Code formatter
- HTMLHint
- stylelint

# Заданиz к lesson-1

## task-1

Объяви две переменные хранящие имя пользователя и вариант приветствия.

Дай имена (идентификаторы) переменных, согласно правил именования перемнных.

Присвой переменным (сразу при объявлении) соответствующие им значения, то есть, имя и приветствие.

Не забывай про строчный тип данных и используй кавычки.

Используя шаблонную строку и интерполяцию, выведи в консоль приветствие пользователя через подстановку значений твоих переменных.  
Например: Валик, привет!

Присвой своим переменным новые значения и снова выведи в консоль получившийся результат.

## task-2

Cоздай 6 переменных с именами, согласно правил именования переменных, присвой им значения всех типов примитивов:  
string  
number  
boolean (для обоих значений по отдельной переменной)  
null  
undefined

Выведи по две консоли для каждой переменной, указав комментарий в команде перед именем переменной,
например:

```
const fruit = 'apple';
console.log("fruit: ", fruit);
console.log("type of data: ", typeof fruit);
```
