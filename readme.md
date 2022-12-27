## Задача

*Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами*


**Алгоритм решения.**

1. Объявляется два массива: изначальный и вторый такой же длины.
2. Далее метод, в котором цикл соразмерный длине массива, внутри цикла делаем проверку условия ( <=3 ), если "да" элемент первого массива заносится в count элемент второго массива.
3. Переменная count чтобы поочередно записывать из первого массива во второй.
4. После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором i увеличивается на 1.
И так проходимся по всему массиву до конца.
