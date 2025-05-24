# individual-work Григоровский Дмитрий
## 1. Инструкции по запуску проекта
1. Скачайте проект и разместите файлы в директории веб-сервера:
`git clone https://github.com/ваш-репозиторий.git`
2. Запустите проект:
   $ npm start

   
## 2. Описание лабораторной работы   

Для индивидуальной работы я разбрабатыл онлайн магазин книг. В данном магазине пользователь можно найти множество книг,

кликнув на одну из них мы можем получить ее описание, а также ее оценку и ену.

В своей работе я реальзовал разделение на роли, регистрации, авторизацию. Также была реальзована пагинация и свзясь с бд и работа с сервером.   

## 3. Краткая документация к проекту 

Стек, используемый в приложении технологий:

BACKEND                

Node js  

Postgresql 

sequelize 

express 

Jwt

FRONTEND

 React js   
 
Axios

 React-routerdom 
 
React-bostrap

 MobX

Содержание.

<table>
    <tr>
        <th>Файл</th>
        <th>Описание</th>
    </tr>
    <tr>
        <td>assets</td>
        <td>папка с фото</td>
    </tr>
    <tr>
       <td>components</td>
      <td>Реализация всей логики приложения</td>
    </tr>
     <tr>
          <td>pages</td>
      <td>Реализация страниц магазина </td>
    </tr>
   <tr>
          <td>http</td>
      <td>Реализация http</td>
    </tr>
  <tr>
        <td>utils</td>
        <td>константные переменные </td>
    </tr>
  <tr>
        <td>index.js</td>
        <td>гланая страница</td>
    </tr>
</table>

![image](https://github.com/user-attachments/assets/283c2514-819e-4636-9e37-4620a76043b2)

схема проекта
![image](https://github.com/user-attachments/assets/665a268f-10b3-4ef9-82c3-dfa095f567a6)

Функциональные возможности.

В приложение реализованы регистрация и авторизация
![image](https://github.com/user-attachments/assets/2b57b05b-ead3-4b57-83a9-7fe32ffe4a40)
![image](https://github.com/user-attachments/assets/5b4e67aa-5195-4405-8357-363133b4b378)

Также присутствует разделение на роли, в частности, Админ и обычный пользователь
![image](https://github.com/user-attachments/assets/d7b40e70-d4b4-46e3-9f39-8fb0af914080)

Админу доступна панель с дополнительными возможностями, например добавить книгу, жанр или язык

![image](https://github.com/user-attachments/assets/45d785e6-ba9b-485f-bd1b-34962c0ef235)

![image](https://github.com/user-attachments/assets/8c55f604-fb30-407f-b877-c8389bedda60)

Сам сайт представляет собой онлайн магазин книг с выбором по жанру и языку книги, также реализована пагинация  
![image](https://github.com/user-attachments/assets/fbd2922c-e8c2-4936-aa4a-b30aece44f29)
![image](https://github.com/user-attachments/assets/c6de746b-594c-4887-8e17-bf3e9d406366)

При нажатии на одну из книг мы увидим дополнительную информацию о ней 
![image](https://github.com/user-attachments/assets/bdcb5635-2c20-486a-94ee-b748469e4f98)

Сценарии взаимодействия пользователей с приложением.

Наше приложение это базовый интернет магазин, пользователь может просмотривать информацию о книгах, выбрать книгу по жанру и языку.

Структура базы данных.

![image](https://github.com/user-attachments/assets/f768efcc-b363-42f5-8300-9bb6aff0da91)



## 4. Примеры использования проекта с приложением скриншотов или фрагментов кода



## 5. Ответы на контрольные вопросы

$_POST - суперглобальный массив, содержащий данные, отправленные медотом POST.

$_SERVER["PHP_SELF"]- возвращает путь к текущему скрипту, используется как action, чтобы отправить форму на ту же страницу

$_REQUEST - Объединяет $_GET, $_POST B $_COOKIE. Имеет проблемы с безопасностью.

$_POST - массив, содержащий данные из формы, отправленные методом POST.

## 6. Список использованных источников

https://metanit.com/php/tutorial/3.4.php

https://www.php.net/manual/ru/tutorial.forms.php



