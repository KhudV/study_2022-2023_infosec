---
marp: true
paginate: true
title: Лабораторная работа №2
author: Vasily Khuditsky
theme: default
---
<style>
section::after {
  content: attr(data-marpit-pagination) ' / ' attr(data-marpit-pagination-total);
}
img[alt="center"] {
     display: block;
     margin: 0 auto;
}
h1 {
    font-size: 60px;
    text-align: center;
}
h2 {
    font-size: 30px;
    text-align: left;
    position: relative;
    left: -2em;
    line-height: 0px;
    top: 8em;
}
h3 {
    font-size: 40px;
    text-align: left;
    position: relative;
    left: -0.5em;
    bottom: 0.2em;
}
h4 {
    font-size: 25px;
    text-align: center;
    position: relative;
    left: -0.5em;
    bottom: 0.2em;
}
</style>

# Лабораторная работа №2
## Василий О. Худицкий 
## РУДН, 17 сентября 2022, Москва, Россия

---

# Цель лабораторной работы

- Получение практических навыков работы в консоли с атрибутами файлов. 
- Закрепление теоретических основ дискреционного разграничения доступа в современных системах с открытым кодом на базе ОС Linux.

---

# Задание лабораторной работы

- Выполнить задания лабораторной работы.

- Проанализировать полученные результаты.


---

# Выполнение лабораторной работы

---

# Создание пользователя guest 



#### ![Создание пользователя guest](image/1.png)
##### Рис.1 Создание пользователя guest

---

# Установка пароля

#### ![Установка пароля](image/2.png)
##### Рис.2 Установка пароля

---

# Определение текущей директории

#### ![Определение текущей директории](image/4.png)
##### Рис.3 Определение текущей директории

---

# Определение имени пользователя

#### ![Имя пользователя](image/5.png)
##### Рис.4 Имя пользователя

---

# Уточнение имени пользователя, его группы, а также групп, в которые он входит 



#### ![Команда id](image/6.png)
##### Рис.5 Команда id

---

# Просмотр файла /etc/passwd

#### ![Файл /etc/passwd](image/8.png)
##### Рис.6 Файл /etc/passwd

---

# Существующие в системе директории



#### ![Существующие в системе директории](image/9.png)
##### Рис.7 Существующие в системе директории

---

# Расширенные атрибуты



#### ![Расширенные атрибуты](image/10.png)
##### Рис.8 Расширенные атрибуты

---

# Новая директория и информация о ней

#### ![Директория dir1 и информация о ней](image/11.png)
##### Рис.9 Директория dir1 и информация о ней

---

# Установленные права и разрешённые действия

#### ![Фрагмент таблицы «Установленные права и разрешённые действия»](image/16.png)
##### Рис.10 Фрагмент таблицы «Установленные права и разрешённые действия»

---

# Минимально необходимые права для выполнения операций внутри директории

---

#### ![Таблица «Минимально необходимые права для выполнения операций внутри директории»](image/15.png)
##### Рис.11 Таблица «Минимально необходимые права для выполнения операций внутри директории»

---

# Выводы
В ходе выполнения лабораторной работы я 
- получил практические навыки работы в консоли с атрибутами файлов 
- закрепил теоретические основы дискреционного разграничения доступа в современных системах с открытым кодом на базе ОС Linux.