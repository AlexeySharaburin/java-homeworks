## Задача 1. Сравнение double

### Описание
Напишем программу для сравнения double, float и округления этих типов

### Функционал программы
1. Ввод двух чисел double или float;
2. Ввод операции;
3. Вывод результата.

### Пример
```
Операции над double/float
1. Сравнить
2. Округлить
3. Отбросить дробную часть

1 <enter>
Введите первое число:
0.33 <enter>
Введите второе число:
0.33 <enter>
Результат:
числа равны
```

### Процесс реализации
1. При запуске программы выведем возможные операции над числами с помощью `System.out.println`

2. Выберем операцию:
  - для отброса дробной части — можно привести к типу long;
  - для сравнения — вычесть одно число из другого и проверить разницу;
  - для округления — воспользуемся Math.round(value).

3. Выведем результат.

