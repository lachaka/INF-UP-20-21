# Задачи:

### Задача 1.

При въведена матрица 9х9 проверете дали е валидно решение на судоку.

### Задача 2.

Напишете функция, която при подадена матрица A[n][m] намира за колко елемента е изпълнено: 
   1) A[i-1][j] + A[i+1][j] + A[i][j+1] + A[i][j-1] <= A[i][j]
   2) A[i-1][j+1] + A[i+1][j] + A[i-1][j+1] + A[i-1][j-1] <= A[i][j]

### Задача 3.

Напишете функция, която приема 2 матрици и ги умножава. Умножението се извършва ред по стълб.

### Задача 4.

Коледа наближава и искаме да зарадваме максимално много приятели като им подарим подарък.
По даден масив от числа с плаваща запетая: *gifts* - цените на подаръци и число с плаваща запетая: *budget* - парична сума с която разполагаме. Тъй като искаме да зарадваме максимално много хора искаме да купим възможно най-много подаръци с бюджета с който разполагаме. Да се изведат на екрана цените на подаръците които ще купим. \

Пример: \
Вход: [10, 10.5, 13, 1, 5, 7, 100, 2, 16] 15.5 \
Изход:
```
1
2
5
7
```

### Задача 5.

Играем следната игра:
Пешо си намисля число в интервала от 1 до 100.
Ванката задава въпроси от рода на "Твоето число по-голямо ли е от X?", където X е число в интервала. За всеки отговор Ванката трябва да плати на Пешо по 1 лев. Помогнете на Ванката като напишете функция която с възможно най-малко пари винаги познава числото на Пешо.