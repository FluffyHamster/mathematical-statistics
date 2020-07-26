# Доверительные интервалы для параметров нормального распределения

Интервал ![(\overline{\theta_1}, \overline{\theta_2})](https://render.githubusercontent.com/render/math?math=(%5Coverline%7B%5Ctheta_1%7D%2C%20%5Coverline%7B%5Ctheta_2%7D)%0A), накрывающий с вероятностью ![\gamma](https://render.githubusercontent.com/render/math?math=%5Cgamma) истинное значение параметра ![\theta](https://render.githubusercontent.com/render/math?math=%5Ctheta), называется **доверительным интервалом**, а вероятность ![\gamma](https://render.githubusercontent.com/render/math?math=%5Cgamma) **надежностью оценки или доверительной вероятностью**.

Построим доверительные интервалы для параметров нормального распределения, т.е. когда выборка производится из генеральной совокупности, имеющей нормальное распределение с параметрами ![\alpha](https://render.githubusercontent.com/render/math?math=%5Calpha) и ![\sigma^{2}](https://render.githubusercontent.com/render/math?math=%5Csigma%5E%7B2%7D).

1. **Доверительный интервал для математического ожидания при извстной дисперсии (использование таблицы функции Лапласа)**

![Таблица](./Laplace.gif)

*example_1* - пример

2. **Доверительный интервал для математического ожидания при неизвестной дисперсии (использование таблицы квантилей распределения Стьюдента)**

![Таблица](./student.png)

*example_2* - пример

3. **Доверительный интервал для среднего квадратического отклонения нормального распределения (использование таблицы квантилей ![\chi^{2}_{\alpha, n}](https://render.githubusercontent.com/render/math?math=%5Cchi%5E%7B2%7D_%7B%5Calpha%2C%20n%7D) распределения ![\chi^{2}_{n}](https://render.githubusercontent.com/render/math?math=%5Cchi%5E%7B2%7D_%7Bn%7D))**

![Таблица](./chi2.jpg)

*example_3* - пример

**Для оценкивероятности успеха прибольшом числе испытаний Бернули** доверительный интервал, который с надежностью ![\gamma](https://render.githubusercontent.com/render/math?math=%5Cgamma) покрывает оцениваемый параметр *p* при больших значениях *n* (порядка сотен), имеет вид ![(p_{1}; p_{2})](https://render.githubusercontent.com/render/math?math=(p_%7B1%7D%3B%20p_%7B2%7D)), где

![p_{1} = p^{\ast} - t \cdot \sqrt{\dfrac{p^{\ast}(1 - p^{\ast})}{n}}](https://render.githubusercontent.com/render/math?math=p_%7B1%7D%20%3D%20p%5E%7B%5Cast%7D%20-%20t%20%5Ccdot%20%5Csqrt%7B%5Cdfrac%7Bp%5E%7B%5Cast%7D(1%20-%20p%5E%7B%5Cast%7D)%7D%7Bn%7D%7D) и ![p_{2} = p^{\ast} + t \cdot \sqrt{\dfrac{p^{\ast}(1 - p^{\ast})}{n}}](https://render.githubusercontent.com/render/math?math=p_%7B2%7D%20%3D%20p%5E%7B%5Cast%7D%20%2B%20t%20%5Ccdot%20%5Csqrt%7B%5Cdfrac%7Bp%5E%7B%5Cast%7D(1%20-%20p%5E%7B%5Cast%7D)%7D%7Bn%7D%7D)

где ![p^{\ast} = \dfrac{n_{A}}{n}](https://render.githubusercontent.com/render/math?math=p%5E%7B%5Cast%7D%20%3D%20%5Cdfrac%7Bn_%7BA%7D%7D%7Bn%7D) - относительная частота события *A*; *t* определяется из равенства ![2\Phi_{0}(t) = \gamma](https://render.githubusercontent.com/render/math?math=2%5CPhi_%7B0%7D(t)%20%3D%20%5Cgamma)


