# Морской бой
Задали сделать сделать морской бой в универе и я решил, почему бы не закинуть на Гитхаб :)


На поле можно расставить заданное количество кораблей заданной длины, причем между всеми кораблями будет интервал в минимум одну клетку.
Так же программа сообщает пользователю, ранил ли он, потопил кораблик полностью или промахнулся.
Игра реализована на 1 игрока, доделать мульплеер не видел смысла.



## ТЗ
Реализовать программу, с которой можно играть в игру «Морской бой».
Программа автоматически случайно расставляет на поле размером 10 на 10 клеток: 4 1-палубных корабля,
3 2-палубных корабля, 2 3-палубных корабля и 1 4-х палубный. Между любыми двумя кораблями по
горизонтали и вертикали должна быть как минимум 1 незанятая клетка. Программа позволяет игроку ходить,
производя выстрелы. Сама программа НЕ ходит т.е. не пытается топить корабли расставленные игроком.
Взаимодействие с программой производится через консоль. Игровое поле изображается в виде 10 текстовых
строк и перерисовывается при каждом изменении состояния поля. При запросе данных от пользователя
 программа сообщает, что ожидает от пользователя (в частности, координаты очередного «выстрела») и
проверяет корректность ввода. Программа должна уметь автоматически определять потопление корабля и
окончание партии и сообщать об этих событиях.
