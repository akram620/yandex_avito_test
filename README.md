# Тестовое задание в Avito

Ребята, я нашел эту задачу на GitHub Avito. Там условия немного другие. То есть сказано, что вы должны брать эту матрицу с удаленного сервера и затем отправить результат на сервер. Но у меня есть только чистое решение. То есть только основной алгоритм. Если кто-то хочет, может использовать любой язык или библиотеку для получения и отправки на сервер.

Вот ссылка на репозиторий Avito: 
```
https://github.com/avito-tech/python-trainee-assignment
```
У меня эта задача в файл ``54_leetcode_spiral_matrix_avito.py``
## Условие

У нас есть матрица (NxN). Надо вернуть её пользователю в виде `List[int]`. Этот список должен содержать результат обхода полученной матрицы по спирали: против часовой стрелки, начиная с левого верхнего угла (см. test case ниже).

Пример исходной матрицы:

``` 
+-----+-----+-----+-----+
|  10 |  20 |  30 |  40 |
+-----+-----+-----+-----+
|  50 |  60 |  70 |  80 |
+-----+-----+-----+-----+
|  90 | 100 | 110 | 120 |
+-----+-----+-----+-----+
| 130 | 140 | 150 | 160 |
+-----+-----+-----+-----+
```

Результат:
```
[10, 50, 90, 130, 140, 150, 160, 120, 80, 40, 30, 20, 60, 100, 110, 70]
```

Матрица гарантированно содержит целые неотрицательные числа. Форматирование границ иными символами не предполагается.

# Yandex
У Яндекса тоже такая, но здесь матрица уже готова и мы идем не против часовой стрелки, а по часовой стрелке.
``54_leetcode_spiral_matrix_yandex.py``