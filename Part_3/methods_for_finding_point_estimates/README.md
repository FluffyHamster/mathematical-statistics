# Методы нахождения точечных оценок

1. Метод моментов
2. Метод максимального правдоподобия
3. Метод наименьших квадратов

## Метод моментов

Метод моментов для нахождения точечных оценок неизвестных параметров заданного распределения состоит в приравнивании теоретических моментов распределения соответствующим эмперическим моментам, найденных по выборке.

Если распределение зависит от одного параметра, то для нахождения его оценки надо решить относительно этого параметра ур-е:

![MX = \overline{X_{B}}](https://render.githubusercontent.com/render/math?math=MX%20%3D%20%5Coverline%7BX_%7BB%7D%7D)

Если распределение зависит от двух параметров, то надо решить относительно этих параметров систему ур-й:

![\begin{cases} MX = \overline{X_{B}} \\ DX = D_{B} \end{cases}](https://render.githubusercontent.com/render/math?math=%5Cbegin%7Bcases%7D%20MX%20%3D%20%5Coverline%7BX_%7BB%7D%7D%20%5C%5C%20DX%20%3D%20D_%7BB%7D%20%5Cend%7Bcases%7D)

Если распределение зависит от *k* параметров, то надо решить относительно этих параметров систему ур-й:

![\begin{cases} MX = \overline{X_{B}} \\ MX^{2} = \dfrac{1}{n}\sum^{n}_{i=1}X^{2}_{i} \\ ... \\MX^{k} = \dfrac{1}{n}\sum^{n}_{i=1}X^{k}_{i} \end{cases}](https://render.githubusercontent.com/render/math?math=%5Cbegin%7Bcases%7D%20MX%20%3D%20%5Coverline%7BX_%7BB%7D%7D%20%5C%5C%20MX%5E%7B2%7D%20%3D%20%5Cdfrac%7B1%7D%7Bn%7D%5Csum%5E%7Bn%7D_%7Bi%3D1%7DX%5E%7B2%7D_%7Bi%7D%20%5C%5C%20...%20%5C%5CMX%5E%7Bk%7D%20%3D%20%5Cdfrac%7B1%7D%7Bn%7D%5Csum%5E%7Bn%7D_%7Bi%3D1%7DX%5E%7Bk%7D_%7Bi%7D%20%5Cend%7Bcases%7D)

Метод моментов является наиболее простым методом оценки параметров. Он был предложен Пирсоном в 1894 г. Оценки метода моментов обычно состоятельны, однако их эффективность часто значительно меньше единицы.

*Example_1* - пример использования метода моментов

## Метод максимального правдоподобия

В основе метода максимального правдоподобия (ММП), предложенного Р. Фишером, лежит понятие функции правдоподобия.

**Ф-я правдоподобия**:

![L(x, \theta) = \prod^{n}_{i = 1} f(x_{i}, \theta)](https://render.githubusercontent.com/render/math?math=L(x%2C%20%5Ctheta)%20%3D%20%5Cprod%5E%7Bn%7D_%7Bi%20%3D%201%7D%20f(x_%7Bi%7D%2C%20%5Ctheta))

*За точечную оценку параметра, согласно ММП, берут такое значение, при котором ф-я правдоподобия достигает максимума*

Эта оценка, называется **оценкой максимального правдоподобия**, является решением уравнения:

![\dfrac{dL(x, \theta)}{d \theta} = 0](https://render.githubusercontent.com/render/math?math=%5Cdfrac%7BdL(x%2C%20%5Ctheta)%7D%7Bd%20%5Ctheta%7D%20%3D%200)

Т.к. ф-я ![L(x, \theta)](https://render.githubusercontent.com/render/math?math=L(x%2C%20%5Ctheta)) и ![ln L(x, \theta)](https://render.githubusercontent.com/render/math?math=ln%20L(x%2C%20%5Ctheta)) достигают максимума при одном и томже значении ![\theta](https://render.githubusercontent.com/render/math?math=%5Ctheta), то вместо ф-и ![L(x, \theta)](https://render.githubusercontent.com/render/math?math=L(x%2C%20%5Ctheta)) ищут (что проще) максимум ф-и ![ln L(x, \theta)](https://render.githubusercontent.com/render/math?math=ln%20L(x%2C%20%5Ctheta))

Т.о для нахождения оценки максимального правдоподобия надо:

1. решить уравнение правдоподобия

![\dfrac{d(lnL(x, \theta))}{d \theta} = 0](https://render.githubusercontent.com/render/math?math=%5Cdfrac%7Bd(lnL(x%2C%5Ctheta))%7D%7Bd%5Ctheta%7D%20%3D%200)

2. отобрать то решение, которое обращает ф-ю ![ln L(x, \theta)](https://render.githubusercontent.com/render/math?math=ln%20L(x%2C%20%5Ctheta)) в максимум (удобно использовать вторую производную) 

*Example_2* - пример использования ММП

