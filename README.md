# Homework №1 Node.js

## Получаем и выводим весь список контактов в виде таблицы (console.table)

```bash
node index.js --action list
```

![example-1](./assets/img-1.png)

## Получаем контакт по id - выводим в консоль объект контакта или null, если контакта с таким id не существует.

```bash
node index.js --action get --id 05olLMgyVQdWRwgKfg5J6
```

![example-2](./assets/img-2.png)

## Добавляем контакт и выводим в консоль созданный контакт

```bash
node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22
```

![example-3](./assets/img-3.png)

## Удаляем контакт и выводим в консоль удаленный контакт или null, если контакта с таким id не существует.

```bash
node index.js --action remove --id qdggE76Jtbfd9eWJHrssH
```

![example-4](./assets/img-4.png)
