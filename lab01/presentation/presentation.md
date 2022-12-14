---
marp: true
paginate: true
title: Лабораторная работа №1
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

# Лабораторная работа №1
## Василий О. Худицкий 
## РУДН, 10 сентября 2022, Москва, Россия

---

# Цель лабораторной работы

- Приобретение практических навыков установки операционной системы на виртуальную машину.

- Настройка минимально необходимых для дальнейшей работы сервисов.

---

# Задание лабораторной работы

- Установить операционную систему Linux (дистрибутив Rocky) на виртуальную машину VirtualBox и настроить минимально необходимые для дальнейшей работы сервисы.

- Проанализировать последовательность загрузки системы, выполнив команду dmesg

- Ответить на контрольные вопросы


---

# Выполнение лабораторной работы

---

### Создание виртуальной машины в VirtualBox 



#### ![Создание виртуальной машины](image/1.png)
##### Рис.1 Создание виртуальной машины

---

### Выбор объема оперативной памяти



#### ![Объем оперативной памяти](image/4.png)
##### Рис.2 Объем оперативной памяти

---

### Создание виртуального жесткого диска



#### ![Создание виртуального жесткого диска](image/2.png)
##### Рис.3 Создание виртуального жесткого диска

---

### Выбор образа операционной системы 



#### ![Выбор образа операционной системы](image/7.png)
##### Рис.4 Выбор образа операционной системы

---

### Выбор языка 



#### ![Выбор языка](image/9.png)
##### Рис.5 Выбор языка

---

### Выбор пакета программ 



#### ![Выбор пакета программ](image/10.png)
##### Рис.6 Выбор пакета программ

---

### Отключение KDUMP 



#### ![Отключение KDUMP](image/21.png)
##### Рис.7 Отключение KDUMP

---

### Включение сетевого соединения 



#### ![Включение сетевого соединения](image/11.png)
##### Рис.8 Включение сетевого соединения

---

### Установка пароля для root и создание пользователя с правами администратора 



#### ![Установка пароля для root](image/12.png)
##### Рис.9 Установка пароля для root

---

# Подключение диска дополнительной гостевой ОС 



#### ![Подключение диска дополнительной гостевой ОС](image/14.png)
##### Рис.10 Подключение диска дополнительной гостевой ОС

---

# Домашнее задание

---

#### ![Домашнее задание](image/23.png)
##### Рис.12 Домашнее задание

---

# Выводы
В ходе выполнения лабораторной работы я 
- приобрел практические навыки установки операционной системы на виртуальную машину 
- настроил минимально необходимые для дальнейшей работы сервисы.
