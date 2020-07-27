### Numpy

##### import numpy as np

    np.arange(start , stop , step) - эквивалент функции range в Python но работает быстрее и поддерживает числа с плавающей запятой

    np.zeros(M,N) - генерирует матрицу нулей размером M на N

    np.ones(M,N) - генерирует матрицу единиц размером M на N

    np.linspace(start , stop , amount) - генерирует массив чисел размером amount  содержащий числа от start до stop 

    np.eye(M,N) - генерирует единичную матрицу M на N

    np.random.rand(*args) - генерирует матрицу или массив случайных чисел от 0 до 1
    
    np.random.randn(*args) - генерирует матрицу или массив случайных чисел c нормальным распределением от 0 до 1

    np.random.randint(start , stop ,  amount) - генерирует последовательность случайных чисел длинной amount от start  до stop


    rand_arr.reshape(M,N) - изменяет форму массива без изменения его данных

    Example: 
            rand_arr = matrix([ [88, 11, 97],
                                [84, 81, 59],
                                [74, 34, 10],
                                [71, 31, 23]    ])
            
            rand_arr.reshape(3,4)
            rand_arr = matrix([ [88, 11, 97, 84],
                                [81, 59, 74, 34],
                                [10, 71, 31, 23]    ])


