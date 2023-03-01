# goit-node-hw-01

### Get and display the entire list of contacts in the form of a table (console.table)
### Получаем и выводим весь список контактов в виде таблицы (console.table)

```diff
node index.js --action list
```

<img src="https://i.ibb.co/5s4KYdN/1.jpg" alt="List" border="2" />

### Get contact by id
### Получаем контакт по id
```diff
node index.js --action get --id 5
```

<img src="https://i.ibb.co/3drZc48/2.jpg" alt="Get" border="3" />

### Add a contact
### Добавялем контакт
```diff
node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22
```

<img src="https://i.ibb.co/t8jtXLC/3.jpg" alt="Add" border="4" />

### Remove contact using id
### Удаляем контакт используя id
```diff
node index.js --action remove --id=3
```

<img src="https://i.ibb.co/GTXpf9g/4.jpg" alt="Remove" border="5" />
