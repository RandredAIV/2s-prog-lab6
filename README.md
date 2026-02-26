# RU

# Обработка двумерных массивов и алгоритм AES-128 (CFB)

## Описание

Данная лабораторная работа посвящена изучению обработки двумерных массивов, 
работе со статическими и динамическими структурами данных, 
а также реализации алгоритма симметричного шифрования AES-128 в режиме CFB (Cipher Feedback Mode).

В рамках работы реализованы алгоритмы анализа матриц и программная реализация 
процесса шифрования и дешифрования текста.

---

## Цели работы

- Изучение алгоритмов формирования и обработки двумерных массивов
- Освоение работы со статическими и динамическими структурами данных
- Реализация алгоритмов поиска и анализа элементов матрицы
- Реализация алгоритма симметричного шифрования AES-128
- Закрепление навыков программирования и тестирования алгоритмов

---

## Задание 6.1 — Обработка двумерных массивов

### Задача 1

- Создание матрицы размерности M × N
- Заполнение случайными числами в диапазоне [0; 50]
- Определение простого числа, которое встречается чаще всего

### Задача 2

- Формирование квадратной матрицы размерности N × N
- Инициализация по заданному правилу
- Модификация формата вывода: вместо 0 выводится 000

### Задача 3

- Для матрицы размерности M × N определить элементы, которые:
  - являются минимальными в своей строке
  - одновременно являются максимальными в своём столбце

---

## Задание 6.2 — Алгоритм AES-128 (CFB)

Реализована система симметричного шифрования на основе алгоритма AES-128
в режиме CFB (Cipher Feedback Mode).

### Реализованные этапы

- Генерация мастер-ключа (128 бит)
- Расширение ключа (Key Expansion)
- SubBytes
- ShiftRows
- MixColumns
- AddRoundKey
- Процесс шифрования
- Процесс дешифрования

---

## Используемые языки программирования

- C++
- Java

---

## Сборка и запуск

- Открыть соответствующий файл задания.
- Скомпилировать программу выбранного языка.
- Запустить программу.
- Ввести необходимые параметры.
- Получить результат вычислений в консоли.

---

# EN

# Two-Dimensional Arrays Processing and AES-128 (CFB)

## Description

This laboratory work focuses on two-dimensional array processing,
working with static and dynamic data structures,
and implementing the AES-128 symmetric encryption algorithm
in CFB (Cipher Feedback Mode).

The project includes matrix analysis algorithms
and a software implementation of text encryption and decryption.

---

## Objectives

- Study algorithms for creating and processing two-dimensional arrays
- Work with static and dynamic data structures
- Implement matrix element analysis algorithms
- Implement the AES-128 symmetric encryption algorithm
- Improve programming and debugging skills

---

## Task 6.1 — Two-Dimensional Arrays

### Task 1

- Create a matrix of size M × N
- Fill it with random numbers in the range [0; 50]
- Determine the prime number that appears most frequently

### Task 2

- Create a square matrix of size N × N
- Initialize it according to a given rule
- Modify the output format: display 000 instead of 0

### Task 3

- For a matrix of size M × N determine elements that:
  - are minimum in their row
  - and maximum in their column

---

## Task 6.2 — AES-128 Algorithm (CFB Mode)

Implementation of the AES-128 symmetric encryption algorithm
in CFB (Cipher Feedback Mode).

### Implemented stages

- 128-bit master key generation
- Key expansion
- SubBytes
- ShiftRows
- MixColumns
- AddRoundKey
- Encryption process
- Decryption process

---

## Programming Languages

- C++
- Java

---

## How to Use

1. Open the required source file.
2. Compile the required source file.
3. Run the program.
4. Enter input parameters.
5. View the results in the console.
