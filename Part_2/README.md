# Численные характеристики статистического распределения

**Выборочным среднем** ([1, стр 187]) (![\overline{x_{B}}](https://render.githubusercontent.com/render/math?math=%5Coverline%7Bx_%7BB%7D%7D), ![m^{\ast}_{x}](https://render.githubusercontent.com/render/math?math=m%5E%7B%5Cast%7D_%7Bx%7D), ![M^{\ast}(x)](https://render.githubusercontent.com/render/math?math=M%5E%7B%5Cast%7D(x))) называется среднее арифметическое всех значений выборки:

![\overline{x_{B}} = \dfrac{1}{n}\sum^{n}_{i = 1} x_{i} \cdot n_{i}](https://render.githubusercontent.com/render/math?math=%5Coverline%7Bx_%7BB%7D%7D%20%3D%20%5Cdfrac%7B1%7D%7Bn%7D%5Csum%5E%7Bn%7D_%7Bi%20%3D%201%7D%20x_%7Bi%7D%20%5Ccdot%20n_%7Bi%7D)

Выборочное среднее можно записать через частость ![\overline{x_{B}} = \sum^{n}_{i = 1} x_{i} \cdot p^{\ast}_{i}](https://render.githubusercontent.com/render/math?math=%5Coverline%7Bx_%7BB%7D%7D%20%3D%20%5Csum%5E%7Bn%7D_%7Bi%20%3D%201%7D%20x_%7Bi%7D%20%5Ccdot%20p%5E%7B%5Cast%7D_%7Bi%7D)

**Выборочной дисперсией** ([1, стр 188]) (![D_{B}](https://render.githubusercontent.com/render/math?math=D_%7BB%7D)) называется среднее арифметическое квадратов отклонений значений выборки от выборочной средней ![\overline{x_{B}}](https://render.githubusercontent.com/render/math?math=%5Coverline%7Bx_%7BB%7D%7D), т.е.

![D_{B} = \dfrac{1}{n} \sum^{n}_{i = 1} \left(x_{i} - \overline{x_{B}}\right)^{2} \cdot n_{i} = \sum^{n}_{i = 1} \left(x_{i} - \overline{x_{B}}\right)^{2} \cdot p^{\ast}_{i}](https://render.githubusercontent.com/render/math?math=D_%7BB%7D%20%3D%20%5Cdfrac%7B1%7D%7Bn%7D%20%5Csum%5E%7Bn%7D_%7Bi%20%3D%201%7D%20%5Cleft(x_%7Bi%7D%20-%20%5Coverline%7Bx_%7BB%7D%7D%5Cright)%5E%7B2%7D%20%5Ccdot%20n_%7Bi%7D%20%3D%20%5Csum%5E%7Bn%7D_%7Bi%20%3D%201%7D%20%5Cleft(x_%7Bi%7D%20-%20%5Coverline%7Bx_%7BB%7D%7D%5Cright)%5E%7B2%7D%20%5Ccdot%20p%5E%7B%5Cast%7D_%7Bi%7D%20)

**Выборочное среднее квадратическое отклонение** выборки определяется формулой:

![\sigma_{B} = \sqrt{D_{B}}](https://render.githubusercontent.com/render/math?math=%5Csigma_%7BB%7D%20%3D%20%5Csqrt%7BD_%7BB%7D%7D%20)

**Исправленная выборочная дисперсия**:

![S^{2} = \dfrac{n}{n - 1} \cdot D_{B}](https://render.githubusercontent.com/render/math?math=S%5E%7B2%7D%20%3D%20%5Cdfrac%7Bn%7D%7Bn%20-%201%7D%20%5Ccdot%20D_%7BB%7D)

**Исправленное выборочное среднее квадратическое отклонение**:

![S = \sqrt{S^{2}}](https://render.githubusercontent.com/render/math?math=S%20%3D%20%5Csqrt%7BS%5E%7B2%7D%7D%20)

Для непрерывно распределенного признака формулы для выборочных средних будут такимиже, но за значения выборки надо брать не концы промежутков, а их середины.

**Размах вариации** называется разность между максимальным и минимальным элементами выборки.

**Мода** вариационного ряда - вариант, имеющий наибольшую частоту.

**Медианой** вариационного ряда - значение признака приходящегося на середину выборки. Если количество элементов выборки четное, то медиана равна ![\dfrac{x_{k} + x_{k+1}}{2}](https://render.githubusercontent.com/render/math?math=%5Cdfrac%7Bx_%7Bk%7D%20%2B%20x_%7Bk%2B1%7D%7D%7B2%7D); если нечетное, то ![x_{k+1}](https://render.githubusercontent.com/render/math?math=x_%7Bk%2B1%7D)

*example_1* - пример поиска характеристики выборки