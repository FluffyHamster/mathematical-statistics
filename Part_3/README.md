# Оценка неизвестных параметров

**Статистической оценкой** ![\overline{\theta}_{n}](https://render.githubusercontent.com/render/math?math=%5Coverline%7B%5Ctheta%7D_%7Bn%7D) [1, стр 191] (оценкой ![\overline{\theta}](https://render.githubusercontent.com/render/math?math=%5Coverline%7B%5Ctheta%7D)) параметра ![\theta](https://render.githubusercontent.com/render/math?math=%5Ctheta) теоритического распределения называют его приблеженное значение, зависящее от данных выбора.

Функцию результатов наблюдений (т.е. функцию выборки) называют **статистикой**

## Свойства статистических оценок [1, стр 192]

Качество оценки определяют, проверяя, обладает ли она свойствами:

1. несмещенность
2. состоятельность
3. эффективность

Оценка ![\overline{\theta}](https://render.githubusercontent.com/render/math?math=%5Coverline%7B%5Ctheta%7D)) параметра ![\theta](https://render.githubusercontent.com/render/math?math=%5Ctheta) называется **несмещенной** если ![M \overline{\theta} = \theta](https://render.githubusercontent.com/render/math?math=M%20%5Coverline%7B%5Ctheta%7D%20%3D%20%5Ctheta), иначе оценка называется смещенной.
Если ![M \overline{\theta}_{n} \rightarrow \theta](https://render.githubusercontent.com/render/math?math=M%20%5Coverline%7B%5Ctheta%7D_%7Bn%7D%20%5Crightarrow%20%5Ctheta), то оценка ![\overline{\theta}_{n}](https://render.githubusercontent.com/render/math?math=%5Coverline%7B%5Ctheta%7D_%7Bn%7D) называется **асимптотически несмещенной**

![M \overline{\theta}](https://render.githubusercontent.com/render/math?math=M%20%5Coverline%7B%5Ctheta%7D) - матиматическое ожидание оценки [\overline{\theta}](https://render.githubusercontent.com/render/math?math=%5Coverline%7B%5Ctheta%7D)).

**Матиматическое ожидание** [1, стр 73] (или средним значением) дискретной случайной величины *X*, имеющей закон распределения ![p_{i} = P \{ X = x_{i} \}](https://render.githubusercontent.com/render/math?math=p_%7Bi%7D%20%3D%20P%20%5C%7B%20X%20%3D%20x_%7Bi%7D%20%5C%7D), i = 1, 2, 3, ..., n, называется число, равное сумме произведений всех ее значений на соответствующие им вероятности.

Оценка ![\overline{\theta}](https://render.githubusercontent.com/render/math?math=%5Coverline%7B%5Ctheta%7D)) параметра ![\theta](https://render.githubusercontent.com/render/math?math=%5Ctheta) называется **состоятельной**, если она сходится по вероятности к оцениваемому параметру:

![\overline{\theta}_{n} \dfrac{p}{n \rightarrow \infty} > \theta](https://render.githubusercontent.com/render/math?math=%5Coverline%7B%5Ctheta%7D_%7Bn%7D%20%5Cdfrac%7Bp%7D%7Bn%20%5Crightarrow%20%5Cinfty%7D%20%3E%20%5Ctheta)

т.е. для любого ![\varepsilon](https://render.githubusercontent.com/render/math?math=%5Cvarepsilon) > 0 выполнено 

![\lim_{n\rightarrow\infty} p \left\{\left|\overline{\theta}_{n} - \theta \right| < \varepsilon\right\} = 1](https://render.githubusercontent.com/render/math?math=%5Clim_%7Bn%5Crightarrow%5Cinfty%7D%20p%20%5Cleft%5C%7B%5Cleft%7C%5Coverline%7B%5Ctheta%7D_%7Bn%7D%20-%20%5Ctheta%20%5Cright%7C%20%3C%20%5Cvarepsilon%5Cright%5C%7D%20%3D%201)

*Свойство состоятельности обязательно для любого правила оценивания (несостоятельные оценки не используются)*