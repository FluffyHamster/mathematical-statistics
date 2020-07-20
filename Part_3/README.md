# Оценка неизвестных параметров

**Статистической оценкой** ![\overline{\theta}_{n}](https://render.githubusercontent.com/render/math?math=%5Coverline%7B%5Ctheta%7D_%7Bn%7D) [1, стр 191] (оценкой ![\overline{\theta}](https://render.githubusercontent.com/render/math?math=%5Coverline%7B%5Ctheta%7D)) параметра ![\theta](https://render.githubusercontent.com/render/math?math=%5Ctheta) теоритического распределения называют его приблеженное значение, зависящее от данных выбора.

Функцию результатов наблюдений (т.е. функцию выборки) называют **статистикой**

## Свойства статистических оценок [1, стр 192-194]

Качество оценки определяют, проверяя, обладает ли она свойствами:

1. несмещенность
2. состоятельность
3. эффективность

Оценка ![\overline{\theta}](https://render.githubusercontent.com/render/math?math=%5Coverline%7B%5Ctheta%7D)) параметра ![\theta](https://render.githubusercontent.com/render/math?math=%5Ctheta) называется **несмещенной** если ![M \overline{\theta} = \theta](https://render.githubusercontent.com/render/math?math=M%20%5Coverline%7B%5Ctheta%7D%20%3D%20%5Ctheta), иначе оценка называется смещенной.
Если ![M \overline{\theta}_{n} \rightarrow \theta](https://render.githubusercontent.com/render/math?math=M%20%5Coverline%7B%5Ctheta%7D_%7Bn%7D%20%5Crightarrow%20%5Ctheta), то оценка ![\overline{\theta}_{n}](https://render.githubusercontent.com/render/math?math=%5Coverline%7B%5Ctheta%7D_%7Bn%7D) называется **асимптотически несмещенной**

![M \overline{\theta}](https://render.githubusercontent.com/render/math?math=M%20%5Coverline%7B%5Ctheta%7D) - матиматическое ожидание оценки ![\overline{\theta}](https://render.githubusercontent.com/render/math?math=%5Coverline%7B%5Ctheta%7D).

**Матиматическое ожидание** [1, стр 73] (или средним значением) дискретной случайной величины *X*, имеющей закон распределения ![p_{i} = P \{ X = x_{i} \}](https://render.githubusercontent.com/render/math?math=p_%7Bi%7D%20%3D%20P%20%5C%7B%20X%20%3D%20x_%7Bi%7D%20%5C%7D), i = 1, 2, 3, ..., n, называется число, равное сумме произведений всех ее значений на соответствующие им вероятности.

Оценка ![\overline{\theta}](https://render.githubusercontent.com/render/math?math=%5Coverline%7B%5Ctheta%7D)) параметра ![\theta](https://render.githubusercontent.com/render/math?math=%5Ctheta) называется **состоятельной**, если она сходится по вероятности к оцениваемому параметру:

![\overline{\theta}_{n} \dfrac{p}{n \rightarrow \infty} > \theta](https://render.githubusercontent.com/render/math?math=%5Coverline%7B%5Ctheta%7D_%7Bn%7D%20%5Cdfrac%7Bp%7D%7Bn%20%5Crightarrow%20%5Cinfty%7D%20%3E%20%5Ctheta)

т.е. для любого ![\varepsilon](https://render.githubusercontent.com/render/math?math=%5Cvarepsilon) > 0 выполнено 

![\lim_{n\rightarrow\infty} p \left\{\left|\overline{\theta}_{n} - \theta \right| < \varepsilon\right\} = 1](https://render.githubusercontent.com/render/math?math=%5Clim_%7Bn%5Crightarrow%5Cinfty%7D%20p%20%5Cleft%5C%7B%5Cleft%7C%5Coverline%7B%5Ctheta%7D_%7Bn%7D%20-%20%5Ctheta%20%5Cright%7C%20%3C%20%5Cvarepsilon%5Cright%5C%7D%20%3D%201)

*Свойство состоятельности обязательно для любого правила оценивания (несостоятельные оценки не используются)*

Состоятельность оценки ![\overline{\theta}_{n}](https://render.githubusercontent.com/render/math?math=%5Coverline%7B%5Ctheta%7D_%7Bn%7D) часто может быть установленна с помощью следующей теоремы:

**Теорема 1**. Если оценка ![\overline{\theta}_{n}](https://render.githubusercontent.com/render/math?math=%5Coverline%7B%5Ctheta%7D_%7Bn%7D) параметра ![\theta](https://render.githubusercontent.com/render/math?math=%5Ctheta) является несмещенной и ![D \overline{\theta}_{n} \rightarrow 0](https://render.githubusercontent.com/render/math?math=D%20%5Coverline%7B%5Ctheta%7D_%7Bn%7D%20%5Crightarrow%200) при ![n \rightarrow \infty](https://render.githubusercontent.com/render/math?math=n%20%5Crightarrow%20%5Cinfty), то ![\overline{\theta}_{n}](https://render.githubusercontent.com/render/math?math=%5Coverline%7B%5Ctheta%7D_%7Bn%7D) - состоятельная оценка.

![D \overline{\theta}_{n}](https://render.githubusercontent.com/render/math?math=D%20%5Coverline%7B%5Ctheta%7D_%7Bn%7D) - дисперсия оценки ![\overline{\theta}_{n}](https://render.githubusercontent.com/render/math?math=%5Coverline%7B%5Ctheta%7D_%7Bn%7D).

**Дисперсия (рассеивание)** [1, стр 77] случайной величины *X* называется математическое ожидание квадрата ее отклонения от своего математического ожидания.

Несмещенная оценка ![\overline{\theta}_{n}](https://render.githubusercontent.com/render/math?math=%5Coverline%7B%5Ctheta%7D_%7Bn%7D) параметра ![\theta](https://render.githubusercontent.com/render/math?math=%5Ctheta) называется **эффективной**, если она имеет наименьшую дисперсию среди всех возможных несмещенных оценок параметра ![\theta](https://render.githubusercontent.com/render/math?math=%5Ctheta), т.е. оценка ![\overline{\theta}_{n}](https://render.githubusercontent.com/render/math?math=%5Coverline%7B%5Ctheta%7D_%7Bn%7D) эффективна, если ее дисперсия минимальна.

*Эффективную оценку в ряде случаев можно найти, используя неравенство Рао-Крамера*

*На практике не всегда удается удволетворить всем перечисленных выше требованиям (несмещенность, состоятельность, эффективность)*

## Точечные оценки математического ожидания и дисперсии

Статистика, используемая в качестве приближенного значения неизвестного параметра генеральной совокупности, называется ее **точечной оценкой** (т.е. это число, определяемое по выборке)

**Теорема 2**. Пусть ![X_{1}, X_{2}, ..., X_{n}](https://render.githubusercontent.com/render/math?math=X_%7B1%7D%2C%20X_%7B2%7D%2C%20...%2C%20X_%7Bn%7D) - выборка из генеральной совокупности и ![MX_{i} = MX = a, DX_{i} = DX (i = \overline{1, n})](https://render.githubusercontent.com/render/math?math=MX_%7Bi%7D%20%3D%20MX%20%3D%20a%2C%20DX_%7Bi%7D%20%3D%20DX%20(i%20%3D%20%5Coverline%7B1%2C%20n%7D)). Тогда выборочное среднее ![\overline{X_{B}}](https://render.githubusercontent.com/render/math?math=%5Coverline%7BX_%7BB%7D%7D) - несмещенная и состоятльная оценка математического ожидания *MX* 

**Теорема 3**. Пусть ![X_{1}, X_{2}, ..., X_{n}](https://render.githubusercontent.com/render/math?math=X_%7B1%7D%2C%20X_%7B2%7D%2C%20...%2C%20X_%7Bn%7D) - выборка из генеральной совокупности и ![MX_{i} = MX = a, DX_{i} = DX (i = \overline{1, n})](https://render.githubusercontent.com/render/math?math=MX_%7Bi%7D%20%3D%20MX%20%3D%20a%2C%20DX_%7Bi%7D%20%3D%20DX%20(i%20%3D%20%5Coverline%7B1%2C%20n%7D)). Тогда исправленная выборачная дисперсия ![S^{2}](https://render.githubusercontent.com/render/math?math=S%5E%7B2%7D) - несмещенная состоятльная оценка дисперсии *DX*.

*При больших значениях n разница между выборочной дисперсией и исправленной выборочной дисперсией очень мала и они практически равны, поэтому оценку исправленной выборочной дисперсии используют для оценки дисперсии при малых выборках, обычно при n <= 30*

**Теорема 4**. Относительная частота ![\dfrac{n_{A}}{n}](https://render.githubusercontent.com/render/math?math=%5Cdfrac%7Bn_%7BA%7D%7D%7Bn%7D) появления события *A* в *n* независимых испытаниях является несмещенной состоятельной и эффективной оценкой неизвестной вероятности *p=P(A)* этого события (*p* - вероятность наступления события *A* в каждом испытании) 

**Теорема 5**. Эмперическая функция распределения выборки ![F^{\ast}(X)](https://render.githubusercontent.com/render/math?math=F%5E%7B%5Cast%7D(X)) является несмещенной состоятельной оценкой функции распределения *F(x)* случайной величины *X*.