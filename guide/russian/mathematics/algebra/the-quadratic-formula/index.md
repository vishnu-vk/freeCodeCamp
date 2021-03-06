---
title: The Quadratic Formula
localeTitle: Квадратичная формула
---
## Квадратичная формула

Это простая формула, которую мы можем получить, решая основное представление квадратичного уравнения для x:
```
      ax^2 + bx + c = 0 
```

где a, b, c - заполнители коэффициентов (или константы в реальном уравнении) и x - переменная, для которой нужно найти значение.

Решая для х, получаем квадратичную формулу:
```
    x = (-b +- sqroot(b^2 - 4ac)) / (2a) 
```

Это более **ясно** здесь: ![Вот](https://wikimedia.org/api/rest_v1/media/math/render/svg/2a9804ca8ce019507e3199ca8fced800fb5b7d7c)

### Последствия формулы для нахождения решений:

На первый взгляд, мы можем заключить несколько утверждений для любого квадратичного уравнения в домене и диапазоне реального номера:

Рассмотрим выражение под корень sqare «b ^ 2 - 4ac» как E

1.  Если E положительно, то мы будем иметь 2 решения для x (свойство квадратов)
2.  Если E равно нулю, то существует одно и только одно решение для x
3.  Если E отрицательно, то нет **реального** решения для x

Квадратичная формула является инструментом решения квадратичных уравнений. Квадратичное уравнение является полиномиальным уравнением второй степени. Полином второй степени является просто полиномом, где наивысший показатель _x_ равен 2. Ниже приведены примеры квадратичных уравнений.

*   ![x^2-5x+6=0](https://github.com/jasonu/freecodecamp-images/blob/master/quadratic_integer_roots.png "примерное квадратичное уравнение")
*   ![x^2+x-1=0](https://github.com/jasonu/freecodecamp-images/blob/master/quadratic_irrational_roots.png "примерное квадратичное уравнение")

Формула применима только к уравнениям, которые имеют форму выше, где многочлен равен нулю. В общем случае формула применима к уравнениям, которые имеют вид:

![ax^2+bx+c=0](https://github.com/jasonu/freecodecamp-images/blob/master/quadratic_equation.png "общее квадратичное уравнение")

Где _a_ , _b_ и _c_ - коэффициенты многочлена. В этом случае уравнение будет иметь решение (ы):

![quadratic formula](https://github.com/jasonu/freecodecamp-images/blob/master/quadratic_formula.png "квадратичная формула")

#### Пример:

Предположим, вы хотите найти решения для: ![x^2-5x+6=0](https://github.com/jasonu/freecodecamp-images/blob/master/quadratic_integer_roots.png "примерное квадратичное уравнение") , то, вставив _a = 1, b = -5, c = 6_ в квадратичную формулу, получим:

*   _x = 2_ ,
*   _x = 3_ .

#### Пример:

Решение: ![x^2+x-1=0](https://github.com/jasonu/freecodecamp-images/blob/master/quadratic_irrational_roots.png "примерное квадратичное уравнение") получается установкой _a = 1, b = 1, c = -1_ в квадратичной формуле. Это дает два иррациональных решения или корни:

*   _x = (- 1 + √5) / 2_ ,
*   _x = (- 1-√5) / 2_ .

Квадратическую формулу можно использовать для нахождения решения (-ов) любого квадратичного уравнения, и с помощью определителя можно определить, сколько решений присутствует. Другие методы, такие как факторинг, графическое отображение или завершение квадрата, находят решение (ы) квадратичного уравнения, но квадратичная формула очень полезна в тех случаях, когда вы не можете использовать коэффициент или график.

При написании квадратного уравнения:

![ax ^ 2 + bx + c = 0](https://wikimedia.org/api/rest_v1/media/math/render/svg/70a0e43dfc81e6fea3be4fc96895a8f9ec2966ac/)

(x - переменная, а a, b и c - константы)

Квадратичная формула:

![x = -b +/- sqrt (b ^ 2 - 4ac) по всему 2a](https://wikimedia.org/api/rest_v1/media/math/render/svg/2a9804ca8ce019507e3199ca8fced800fb5b7d7c/)

### дискриминантный

Дискриминант - все под радикалом в квадратичной формуле. ![b ^ 2 - 4ac](http://www.katesmathlessons.com/uploads/1/6/1/0/1610286/what-is-the-discriminant_orig.png/)

Если дискриминант = 0, то квадратичное имеет только одно решение. Графически это означает, что вершина расположена на оси х.

Если дискриминант положителен (> 0), то квадратичное имеет два вещественных решения или корни. Это представляет квадратичное пересечение оси x в двух местах.

Если дискриминант отрицательный (<0), квадратичный не имеет реальных решений (двух мнимых решений). Это потому, что вы не можете взять квадратный корень из отрицательного. Грубо говоря, это представляет собой функцию, не проходящую через ось х.

### запоминание

Чаще всего вам потребуется запомнить квадратичную формулу. Вот некоторые полезные мнемонические устройства:

Есть несколько [песен,](https://www.youtube.com/watch?v=2lbABbfU6Zc/) которые помогают.

Кроме того, помогает создать историю, чтобы помнить квадратичную формулу. Например: отрицательный мальчик был неуверен (плюс или минус), чтобы пойти к радикальной партии, но поскольку он был таким квадратным, он упустил четырех замечательных птенцов. Партия закончилась в 2 часа ночи.

### Распространенные ошибки:

Многие люди забывают о порядке операций и вычитают 4, прежде чем умножать его на a и c.

Кроме того, 2a находится под всем этим, а не только квадратным корнем.

Убедитесь, что вы стараетесь не бросать квадратный корень или «плюс / минус» в середине ваших вычислений.

Помните, что «b ^ 2» означает «квадрат ALL of b, включая его знак», поэтому не оставляйте b ^ 2 отрицательным.

#### Дополнительная информация:

[Объясненная квадратичная формула](http://www.purplemath.com/modules/quadform.htm "Объясненная квадратичная формула")

[Википедия - Квадратичная формула](https://en.wikipedia.org/wiki/Quadratic_formula/)

[Фиолетовая математика](http://www.purplemath.com/modules/quadform.htm/)

[Ханская академия](https://www.khanacademy.org/math/algebra/quadratics/solving-quadratics-using-the-quadratic-formula/a/quadratic-formula-explained-article/)