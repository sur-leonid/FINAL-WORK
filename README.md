ЗАДАНИЕ:
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. 
Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, 
лучше обойтись исключительно массивами.

Описание алгоритма решения:
Сперва объявляется два массива -  первый-изначальный  и второй такой же длины. Далее объявляем-описываем метод внутри которого заложен цикл учитывающий парматры длинны массива, внутри цикла заложена проверка длинны входящих массивов по условию (<=3) , и если условие выполняется то элемент первого массива заносится в элемент второго массива. 
После этого установлен и срабатывает счетчик-переключатель  count++ , для поэтапного переноса подходящих по условиям массивов из первого во второй. После  того как во второй массив присвоены подходящие данные из первого  массива переменная count увеличивается на 1 и возвращается к циклу for в котором i увеличивается на 1. Данны цикл повторяется до достжения длинны первого массива.
