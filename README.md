## Задача: 
## Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа.
_Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма_
_При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами_

_Схема алгоритма решения_
(https://github.com/hkate1985/TaskFinal/blob/main/MainMetod.jpg)
## Описание алгоритма решения:
### Сначала объявляется два массива: первичный и вторый такой же длины. Далее реализуется метод, в котором цикл соразмерен длине массива, внутри цикла проводится проверка условия ( <=3 ), если да, то элемент первого массива заносится в переменную count элемента второго массива. Переменная count нужна, для того, чтобы поочередно заливать элементы из первого массива во второй  без пробелов. После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором i (индекс)увеличивается на 1. Такая проверка проиcходит до конца.

### Графическое представление метода в папке Task в расширении jpg.
### Реализация алгоритма по пути TaskSolution/Program.cs