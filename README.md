## Задача 
Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.
## Примеры:

[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]
[“1234”, “1567”, “-2”, “computer science”] → [“-2”]
[“Russia”, “Denmark”, “Kazan”] → []


## Алгоритм решения


1 Начинаем формирование кода с "Console.Clear();"

2 Добавляем описание задания

3 Задаем массивы строк и назначаем переменные

4 Поскольку отсутствует конкретное требование к размеру массива, мы задаем данные вручную. Для этого используем переменную "count"

5 Выделяем память для массива из "count" строк. Размер "массива №2", содержащего конечный результат, принимаем за массива №1 (размер массива 2 может быть <= размеру "массива №1", но не больше него.

6 Запускаем цикл для ввода строк массива с клавиатуры.

7 Проверяем соответсвие элементов массива требованию задания и формируем "массив №2". Для этого запускаем цикл для поэментного сравнения длины строк "массива №1". Если текущая длина строки массива <=3, то записывае данную строку в "массив №2". При заполнении "массива №2" используется переменная "j", в которой сохраняется текущий индекс элемента.
При достижении счетчиком максимального значения <(размер массива), цикл завершается.

8 Выводим элементы "массива №2" на экран.