# D. K-я единица

| Правила                                     	|
|:---------------------------------------------:|
| ограничение по времени на тест: 1 секунда     |
| ограничение по памяти на тест: 1024 мегабайта |
| ввод: стандартный ввод                        |
| вывод: стандартный вывод                      |

В этой задаче вам нужно добавить в дерево отрезков операцию нахождения ***k***-й единицы.

## Входные данные
Первая строка содержит два числа ***n*** и ***m*** (***1 ≤ n, m ≤ 100000***) — размер массива и число операций. Следующая строка содержит ***n*** чисел ***a<sub>i</sub>*** — начальное состояние массива (***a<sub>i</sub> = {0, 1}***). Далее следует описание операций. Описание каждой операции имеет следущий вид:

`1 i` — изменить элемент с индексом ***i*** на противоположный.\
`2 k` — найти ***k***-ю единицу (единицы нумеруются с ***0***, гарантируется, что в массиве достаточное количество единиц).

## Выходные данные
Для каждой операции второго типа выведите индекс соответствующей единицы (все индексы в этой задаче от ***0***).

## Пример
входные данные
```
5 7
1 1 0 1 0
2 0
2 1
2 2
1 2
2 3
1 0
2 0
```

выходные данные
```
0
1
3
3
1
``` 