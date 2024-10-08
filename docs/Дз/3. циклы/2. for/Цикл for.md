# Цикл For
## Теория
```python
for {имя переменной счётчика} in range({start}, {stop}, {step}):
	<...>
```

- счётчик будет изменятся от `start` (включительно) до `stop` (не включительно) с шагом `step`
- Если `step` отрицательный, то счётчик будет уменьшаться на `step`, тогда должно быть: `start` >= `end`
- Так же `range` можно задать проще:
```python
for {имя переменной счётчика} in range({start}, {stop}):  # step=1
	<...>
# или
for {имя переменной счётчика} in range({stop}):  # start=0, step=1
	<...>
```

Пример:
```python
for i in range(0, 3, 1):
	print(i)
```
```cpp
>>>
0
1
2
<<<
```

## Задачи
### 1. Вывод четных чисел:
Напишите программу, которая выводит все четные числа от 1 до 100 с помощью цикла `for`.
```cpp
2
4
6
...
100
```

### 2. Степени двойки:
Напишите программу, которая выводит степени числа `2` от 1 до 50.
```cpp
2^1 = 2
2^2 = 4
2^3 = 8
...
2^10 = 1024
```

### 3. Обратный порядок:
Напишите программу, которая запрашивает у пользователя число `N` и выводит все числа от `N` до 1 в обратном порядке.
```cpp
Введите число: 5
5 4 3 2 1
```

### 4.  Сумма чисел от 1 до N:
Напишите программу, которая запрашивает у пользователя число `N` и выводит сумму всех чисел от 1 до N.
```cpp
Введите число: 5
Сумма: 15
```