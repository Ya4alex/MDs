# While 4
### 1. Горизонтальная ходилка:
Робот находится на `0` координате числовой прямой. Робот ходит, пока не доберется до числа `54`. Ход происходит следующим образом: пользователь вводит число `n`, и робот сдвигается на `n` клеток вправо (Если `n` отрицательное - влево). Когда пользователь дойдёт до `54`, программа должна вывести количество затраченных ходов и завершится.
### 2. Поиск наибольшей цифры в числе:
Пользователь вводит число `x`, вывести наибольшую цифру числа.

> Получить последнюю цифру числа:
> ```python
> last_d = x % 10
> ```
> Получить число без последней цифры:
> ```python
> x_without_last = x // 10
> ```

```cpp
>
54683257
<
8
```
### 3. Вывести число в развёрнутом виде:
Пользователь вводит число `x`, вывести его задом наперёд.
```cpp
> 
1234
< 
4321
```