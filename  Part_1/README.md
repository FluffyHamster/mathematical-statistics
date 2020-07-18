# Ститистическое распределение выборки. Эмпирическая функция распределения

**Ранжирование** ([1 стр 181]) - операция расположения значений случайной величины (признака) по неубыванию. Полученная таким образом последовательность значений случайной величины называется **вариационным рядом**.

**Частоты** ([1 стр 182]) - числа, показывающие, сколько раз встречаются варианты, в ряде наблюдений, а отношение их к объему выборки называется **частостями** или **относительными частотами** (![p^{\ast}](https://render.githubusercontent.com/render/math?math=p%5E%7B%5Cast%7D%0A))

**Статистическим распределением выборки** или **статистическим рядом** называется перечень вариантов и соответствующих им частот или частостей.

*example_1* - пример статистического ряда и вариационного ряда

*Статистическое распределение выборки является оценкой неизвестного распределения*

В случае, когда число значений признака (случайная величина *X*) велико или признак является неприрывным (т.е. когда случайная величина *X* может принять любое значение в некотором интервале), составляют **интервальный статистический ряд**

для определения величины интервала (*h*) можно использовать **формулу Стерджеса**:

![h=\dfrac{x_{\max}-x_{\min}{1+\log_{2}n}](https://render.githubusercontent.com/render/math?math=h%3D%5Cdfrac%7Bx_%7B%5Cmax%7D-x_%7B%5Cmin%7D%7B1%2B%5Clog_%7B2%7Dn%7D) 

![m=1+\log_{2}n](https://render.githubusercontent.com/render/math?math=m%3D1%2B%5Clog_%7B2%7Dn) - число интерваллов

За начало первого интервала рекомендуется брать величину ![x_{\start}=x_{\min}-\dfrac{h}{2}](https://render.githubusercontent.com/render/math?math=x_%7B%5Cstart%7D%3Dx_%7B%5Cmin%7D-%5Cdfrac%7Bh%7D%7B2%7D)

*n* - количество наблюдений

*example_2* - пример интервальный статистический ряд

Одним из способов обработки вариационного ряда является построение **эмперической (статистической) функции распределения** - функция, определяющая для каждого значения *x* частость события {*X* < *x*}:

![F^{\ast}_{n}\left(x\right)=p^{\ast}\left\{X<x\right\}=\dfrac{n_{\x}}{n}](https://render.githubusercontent.com/render/math?math=F%5E%7B%5Cast%7D_%7Bn%7D%5Cleft(x%5Cright)%3Dp%5E%7B%5Cast%7D%5Cleft%5C%7BX%3Cx%5Cright%5C%7D%3D%5Cdfrac%7Bn_%7B%5Cx%7D%7D%7Bn%7D)

где *n* - объем выборки, ![n_{\x}](https://render.githubusercontent.com/render/math?math=n_%7B%5Cx%7D) - число наблюдений, меньших *x*.

Эмперическая функция распределения ![F^{\ast}_{n}\left(x\right)](https://render.githubusercontent.com/render/math?math=F%5E%7B%5Cast%7D_%7Bn%7D%5Cleft(x%5Cright)) является *оценкой* вероятности события {*X* < *x*}

## Теорема (Гливенко):

Пусть *F*(*x*) - теоретическая функция распределения случайной величины *X*, а ![F^{\ast}_{n}\left(x\right)](https://render.githubusercontent.com/render/math?math=F%5E%7B%5Cast%7D_%7Bn%7D%5Cleft(x%5Cright)) - эмперическая. Тогда для любого ![\varepsilon](https://render.githubusercontent.com/render/math?math=%5Cvarepsilon) > 0

![\lim_{n\rightarrow\infty}\left\{\left|F^{\ast}_{n}\left(x\right)-F\left(x\right)\right| > \varepsilon\right\}=0](https://render.githubusercontent.com/render/math?math=%5Clim_%7Bn%5Crightarrow%5Cinfty%7D%5Cleft%5C%7B%5Cleft%7CF%5E%7B%5Cast%7D_%7Bn%7D%5Cleft(x%5Cright)-F%5Cleft(x%5Cright)%5Cright%7C%20%3E%20%5Cvarepsilon%5Cright%5C%7D%3D0)

используя условие из *example_1*

получаем:

![график](./photo_2020-07-16_21-21-38.jpg)
