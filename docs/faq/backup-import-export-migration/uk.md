---
layout: main
---

# Резервне копіювання та переміщення даних

> Резервне копіювання даних необхідне, якщо ви збираєтеся перенести книги на новий пристрій, нову папку або SD-карту

# Експорт (резервне копіювання)

Торкніться _Експорт_, щоб зберегти всі налаштування програми у файл .zip. Виберіть папку для збереження файлу .zip та перейменуйте файл, якщо хочете.

Таким чином ви заощадите:

* Налаштування програми
* Закладки
* Хід читання
* Теги користувача
 
# Імпорт

Торкніться _Import_ і знайдіть файл .zip із даними резервної копії. Торкніться файлу, а потім натисніть _SELECT_

# Перемістити

Міграція замінить лише шляхи до файлів у файлах конфігурації програми.

Повний шлях зберігається в налаштуваннях. Наприклад, якщо шлях до вашої книги (example.pdf) такий:

/storage/Books/example.pdf

і ви хочете перемістити його до папки **MyBooks**, вам потрібно змінити розташування у файлі конфігурації програми на:

/storage/MyBooks/example.pdf

Запустіть _Migrate_ та замініть:

Старий шлях: **/Books/**
Новий шлях: **/MyBooks/**

Торкніться _ПОЧАТИ МІГРАЦІЮ_

Якщо ви переміщуєте свою книгу на **зовнішню SD-карту**, ви можете зробити це легко, замінивши місце призначення:

_Migrate_: /storage/AAAA-AAAA/Книги в /storage/BBBB-BBBB/Книги:

Старий шлях: **/storage/AAAA-AAAA/**
Новий шлях: **/storage/BBBB-BBBB/**

> **Нагадування**: не забудьте спочатку виконати _Export_, щоб створити резервну копію.

|1|2|3|
|-|-|-|
|![](1.png)|![](2.png)|![](3.png)|