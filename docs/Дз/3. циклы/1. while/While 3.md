# While 3
### 1. **Квадраты:**
Вывести квадраты чисел от 1 до введенного пользователем числа. *```(1 2 4 9 ... x**2)```*

### 2. **Фильтр:**
Пользователь вводит 2 числа `s` и `f`. Вывести все числа от `s` до `f`, которые делятся на 7 или на 3.

### 3. **Угадайка:**
Задайте в программе переменную `SECRET = 13`. Пользователь вводит числа до тех пор, пока не введёт число `N`, после чего Вывести `"Вы угадали число"`.
   
   > **Дополнительно\*:**
   > Число `SECRET` можно сделать случайным с помощью кода:
   > 
   > ```python
   > import random
   > 
   > SECRET = random.randint(1, 15)  # случайное число от 1 до 15 включительно
   > # ... остальной код
   > ```

### 4. **Депозит\*:**
Пользователь вводит числа. Когда сумма ввёденных чисел превысит 100, вывести количество чисел и их сумму.
    *Пример:*
   
   ```
   20
   30
   40
   50
   сумма: 90
   чисел: 3
   ```

### 5. **Сумма цифр:**
Пользователь вводит число `x`, вывести сумму его цифр.
   
   > Получить последнюю цифру числа можно, если взять остаток от деления на 10:
   > 
   > ```python
   > 8375 % 10 = 5
   > ```
   > 
   > Получить число без последней цифры можно, если разделить его нацело на 10:
   > 
   > ```python
   > 8375 // 10 = 837
   > ```