# Содержание


# Математический анализ

## Основные задачи анализа 

- Проблема касательной: определить касательную к данной кривой – основная задача дифференциального исчисления. 
- Проблема квадратуры: определить площадь, связанную с данной кривой – основная задача интегрального исчисления.

## Анализ

- Если мы мы построим последовательность `S_1, S_2, S_3, ...` приближений прямоугольниками площади под кривой, причем основание самого широкого прямоугольника в сумме `S_n` стремится к 0, когда `n` возрастает, то последовательность `S` стремиться к пределу `A` и этот предел `A`, представляющий собой площадь под данной кривой, не зависит от того, каким именно образом выбрана последовательность S, раз только основания прямоугольников неограниченно уменьшаются.  Площадь A по определению мы называем интегралом от функции `f(x)` в пределах от `a` до `b`.
- В точках максимума или минимума касательная к кривой `y = f(x)` должна быть параллельна оси `x`; в противном случае кривая около этих точек или поднималась бы или опускалась бы. 
- Под наклоном кривой в точке `P` мы подразумеваем наклон ее касательной в этой точке. 
- Касательная `t` к данной кривой имеет наклон, равный пределу разностного отношения `dy/dx` при стремлении `dx = x_1 - x` к нулю. 
- Предельный процесс, с помощью которого получена производная, называется дифференцированием функции `f(x)`. Этот процесс есть такая операция, которая по определенному правилу сопоставляет данной функции `f(x)` другую функцию `f'(x)`. 

  - `f(x)` есть высота кривой `y = f(x)` в точке `x`.
  - `f'(x)` есть наклон кривой `y = f(x)` в точке `x`.

- Производная в некоторой точке положительна, `f'(x) > 0`, означает подъем кривой (значения y возрастают). Напротив, то обстоятельство, что производная отрицательная, `f'(x) < 0`, означает падения кривой (значения y убывают), если производная обращается в нуль, `f'(x) = 0`, то это означает горизонтальное направление кривой для соответствующего значения `x`. Решая уравнение `f'(x) = 0` относительно `x`, мы можем найти положения максимумов и минимумов. 
- Необходимым условием дифференцируемости некоторой функции является ее непрерывность. 
- Если в некотором промежутке вторая производная больше нуля, то скорость изменения наклона `f'(x)` положительна.
- Положительный знак скорости изменения некоторой функции указывает на то, что эта функция возрастает с возрастанием аргумента `x`. Следовательно неравенство `f''(x) > 0` указывает на то, что наклон `f'(x)` есть возрастающая функция `x` и, значит, при увеличении `x` кривая становится более крутой там, где наклон ее положителен, и более пологой там, где наклон отрицателен. Если `f''(x) > 0` кривая вогнута, если `f''(x) < 0` кривая выпукла. 
- Касательная пересекает пересекает кривую в точках перегиба (`f''(x) = 0`, при `x = 0`).
- Производная неопределенного интеграла по его верхнему пределу `x` равна значению функции `f(u)` в точке `u = x`. 
- Для того, чтобы вычислить определенный интеграл, достаточно найти такую функцию `G(x)`, для которой `G'(x) = f(x)`, и затем составить разность `G(b) - G(a)`.
- Производная от натуральной показательной функции тождественно равна самой функции.

----

- Пусть `f(x)` дифференцируемая на `|a, b|`, тогда:

  - `f(x)` — возрастающая тогда и только тогда `f'(x) >= 0`;
  - `f(x)` — убывающая  тогда и только тогда `f(x) <= 0`.

- Необходимое условие экстремума: Если `x_0` — точка локального экстремума, то `f'(x_0) = 0` или `f'(x_0)` не существует.
- Точки, в которых производная равна 0 или не существует называются критическими точками 1-го порядка.
- Пусть `f(x)` определена в окрестности своей критической точки `x_0` и дифференцируема (хотя бы в проколотой окрестности этой точки). Если `f'(x)` меняет знак при переходе через `x_0`, то `x_0` — точка локального экстремума.
- Пусть в окрестности `U(x_0)` критической точки `x_0` функция `f(x)` дважды непрерывно дифференцируема (те ее вторая производная существует и является непрерывной; множество таких функций часто обозначают `C^2(U(x_0)))`. Если `f''(x) < 0`, то `x_0` – точка максимума, если `f''(x_0) > 0`, то `x_0` — точка минимума.
- Точка, отделяющая участок выпуклости от участка вогнутости, называется точкой перегиба.
- Необходимое условие перегиба: Если `x_0` – точка перегиба дважды непрерывно дифференцируемой функции, то `f''(x_0) = 0`.
- Прямая `L` называется асимптотой графика функции `f(x)`, если расстояние от точки графика до `L` (измеряемое по перпендикуляру к `L`) стремится к 0 при неограниченном удалении точки графика от начала координат.
- Прямая `y = kx + b` является правой асимптотой функции `f(x)` тогда и только тогда, когда `k = lim f(x)/x` и `b = lim (f(x) - kx)` при `x -> плюс бесконечности`.
- Функцией `n` переменных называется отображение `f:D -> R`, где `R` – поле действительных чисел, `D` – подмножество в `R^n`. Таким образом, функция `f = f(x_1, ..., x_n)` считается заданной, если задан закон, позволяющий для каждого упорядоченного набора чисел `(x_1, ...,  x_n)` из `D` находить единственное значение `f(x_1, ..., x_n)` в `R`.
- Областью определения всякой функции `n` переменных является некоторое множество упорядоченных наборов чисел, то есть подмножество в `R^n`.
- Множество `R^n` состоит из всех упорядоченных наборов действительных чисел: `R^n = R x R x ... x R`, то есть является декартовым произведением `n` экземпляров множества `R`.
- Конечное линейное пространство со скалярным произведением называется евклидовым пространством.
- Пусть `а` из `R^n`. Окрестностью точки `а` называется множество `U_e(a) = {x из R^n | |x - a| < e}`.
- Пусть `M` из `R^n`. 

  - Точка с называется внутренней точкой множества `М`, если существует окрестность `U_e(c)`, целиком  лежащая в `M`. 
  - Если любая `U_e(c)` содержит и точки множества `М`, и точки, не лежащие в `М`, то `с` называется граничной точкой `М`. Множество всех граничных точек называется границей множества `М`.
  - Если существует `U_e(c)`, которая содержит только одну точку `М` — саму точку `c`, то такая точка называется изолированной.

- Множество, все точки которого являются внутренними, называются открытыми. Множество, дополнение к которому открыто, называется замкнутым.
- Множество замкнуто тогда и только тогда, когда содержит все свои граничные точки.
- Множество называется ограниченным, если оно лежит в некоторой окрестности точки 0. Последовательность называется ограниченной, если множество ее значений ограничено.
- Любая ограниченная последовательность точек `R^n` содержит сходящуюся подпоследовательность.
- Пусть точка `M` из `R^n`. Точка `с` называется предельной точкой множества `М`, если в любой ее окрестности есть точки `М`, отличные от `с`. Предельными являются все внутренние и все граничные точки множества, кроме изолированных.
- Точка `с` — предельная точка множествам `М` тогда и только когда `с = lim x_k`, где `x_k` из `М, x_k != c`.
- Множество `М` из `R^n` называется компактным, если оно ограничено и замкнуто.
- Если `М` компактно, то любая последовательность точек `М` содержит сходящуюся подпоследовательность, предел которой принадлежит также `М`.
- Множество `М` из `R^n` называется связанным или линейно связным, если для любых точек `a`, `b` из `М` существует непрерывная кривая с концами `a` и `b` целиком лежащая в `М`.
- Ф-я `f` называется непрерывной в точке `P`, если она определена в этой точке и `lim f(P) = f(P_0)` при `P -> P_0`.
- Точка разрыва — любая предельная точка области определения, в которой нарушается непрерывность.
- Функция `f` непрерывна на множестве `D`, если она непрерывна в каждой точке этого множества.
- Если ф-я `f` непрерывна на компактном множестве `D`, то она ограничена на `D` и достигает своих точных верхней и нижней граней.
- Частное приращение (по `x`): `del f(x, y) = f(x + del x, y) - f(x,y)`.
- Частная производная (по `х`): `lim del f(x, y) / del x`
- Если ф-я дифференцируема в точке `(x, y)`, то она непрерывна в этой точке.
- Градиентом функции  в точке  называется направленный отрезок, отложенный от точки, который показывает направление и скорость наискорейшего роста функции в данной точке. Куда «смотрит» градиент – там и самый крутой «подъём в гору». Производная по некоторому направлению в точке  – это проекция градиента в данной точке на данное направление


## Анализ R^n

- Линейная относительно `h` функция `L(x)` из `L(X;Y)`, удовлетворяющая соотношению `f(x+h) - f(x) = L(x)h + a(x; h)`, называется дифференциалом, касательным отображением или производной отображения `f:E->Y`.
- Если отображение `f:E->Y` дифференцируема во внутренней точке `x` множества `E` в `X`, то его дифференциал `L(x)` в этой точке определен однозначно.
- Если линейные отображения `f_i:E->Y, i = 1,2`, дифференцируемы в точке `x` из `U`, то их линейная комбинация также дифференцируемы в точке `x`. Дифференциал линейной комбинации отображения есть соответствующая линейная комбинация дифференциалов этих отображений.
- Если отображение `f:U->V` дифференцируемо в точке `x` из `U` из `X`, а отображение `g:V->Z` дифференцируемо в точке `f(x)=y` из `V` из `Y`, то композиция `gf` этих отображений дифференцируемо в точке `x`. Дифференциал композиции равен композиции дифференциалов. 
- Дифференциал обратного отображения есть линейное отображение, обратное к дифференциалу исходного отображения в соответствующей точке
- Если, например, `X =  R^m`, `Y = R^n` и отображение `f` из `L (R^m, R^n)` задается матрицей `(аji)`, то в любой точке `x` из `R^n` касательное к нему отображение `f'(x): TR^m _x -> TR^n _f(x)` также будет задаваться той же матрицей. 
- Отображение `f':X->Y`, производное от линейного отображения: `f:X->Y` линейных нормированных пространств, постоянно, причем `f'(x)= f` в любой точке `x` из `X`.
- Если `X` – полное пространство и `A` из `U`, то при любом `h` из `L(X; Y)` таком, что `||h|| < ||A^(-1)||^(-1)`, оператор `A + h` также принадлежит `U` и справедливо соотношение: `(A+h)^(-1) = A^(-1) - A^(-1)*h*A^(-1) + o(h)`, при `h->0`.
- `d f(A)h = d(A^(-1)) * h = -A^(-1) h A^(-1)`.
- Производным отображением порядка `n` из `N` или `n`-м дифференциалом отображения в точке `x` из `U` называется отображение, касательное в этой точке к производному отображению `n–1` от `f`.
- Если `X` и `Y` – линейные  нормированные пространства над полем `R`, то производной отображения в точке `x` из `U` по вектору `h` из `TX_x ~ X` назовем предел `D_h f(x):= lim [f(x+th) - f(x)]/t` при `t` из `R –> 0`.
- Если для отображения форма `f^(n) (x)` в точке `x` определена, то она симметрична относительно любой пары своих аргументов. 
- Если в некоторой точке `x` из `X = X_1 * X_2 * ... * X_n` все частные производные `d_i..n f(x)` отображения `f:U–>Y` непрерывны, то в этой точке отображения `f` имеет дифференциал `n`–го порядка. 
- Множество `I = { x из R^n | a^i <= x^i <= b^i, i = 1, ..., n }` называется промежутком или координатным параллелепипедом в `R^n`.
- Промежутку `I = { x из R^n | a^i <= x^i <= b^i, i = 1, ..., n }` ставится в соответствие число `|I| = Произведение (b^i - a^i)`, называемое объемом или мерой промежутка. Объем (меру) промежутка `I` обозначают также символами `v(I)` или `мю(I)`.
- Мера промежутка в `R^n` может быть (а) однородна, (б) аддитивна.
- Представление промежутка `I` в виде объединения `I = Пересечение I_j` будем называть разбиением промежутка `I` и обозначать символом `P`.
- Величина `лямбда(P) := max d(I_j)` (максимального из диаметров промежутков разбиения `P`) называется параметром разбиения `P`.
- Если в каждом промежутке `I_j` разбиения `P` фиксирована некоторая точка `E_j` из `I_j`, то говорят, что имеется разбиение с отмеченными точками. Разбиение с отмеченными точками будем обозначать `(P, E)`.
- Сумма `f(E_i) * |I_i|` называется интегральной суммой (Римана) функции `f`, соответствующей разбиению `(Р, E)` с отмеченными точками промежутка `I`. Предел этой суммы, если она существует, при параметре разбиение стремящимся к нулю, называется интегралам (Римана) от функции `f` на промежутке `I`. Также его называют кратным интегралом. Если такой предел существует, то функция называется интегрируемой (по Риману) функцией на промежутке `I`. Множество всех таких функций мы будем обозначать символом `R(I)`.
`f` принадлежит `R(I)` если `f` ограничена на `I`.
- Множество `E` в `R^n` будем называть допустимым, если оно ограничено в `R^n` и его граница `дE` есть множество меры нуль (в смысле Лебега). 
- Множество `R(E)` функции, интегрируемых по Риману на ограниченном множестве `E` из `R^n`, является линейным пространством относительно стандартных операций сложения функции и умножения функции на число. 

# Ряды

- Выражение `a1 + a2 + ... + an + ...` обозначают символом `SUMn an` и называют рядом или бесконечным рядом.
- Элементы последовательности `{an}`, рассматриваемые как элементы ряда, называют членами ряда; элемент `an` называют `n`-м членом ряда.
- Сумму `sn = SUMk ak` называют частичной суммой ряда.
- Если последовательность `{sn}` частичных сумм ряда сходится, то ряд называется сходящимся. Если последовательность `{sn}` не имеет предела, то ряд называется расходящимся. 
- Предел `lim sn = s` последовательности частичных сумм, если он существует, называется суммой ряда.
- Ряд `a1 + a2 + ... + an + ...` сходится тогда и только тогда, когда для любого `e > 0` найдется такое число `N`, что из `m >= n > N` следует `|an + ... + am| < e`.
- Для того, чтобы ряд сходился, необходимо, чтобы его члены стремились к нулю при `n -> inf`.
- Если в ряде изменить только конечное число членов, то получающийся при этом новый ряд будет сходится, если сходился исходный, и будет расходится, если исходный ряд расходился. 


# Предел

### Общие слова

- Функция `f(x)` имеет предел `a` при `x` стремящемся к бесконечности, и записывается в форме: `f(x) –> a` при `x –> бесконечности`, если, как бы мало ни было положительное число `e`, можно к нему подобрать такое положительное число `K` (зависящее от `e`), что неравенство `|f(x) - a| < e` выполняется при условии `|x| > K`.
- Если функция `f(x)` непрерывна в интервале `I`, `a <= x <= b`, не исключая также и конечных точек интервала `a` и `b`, то в интервале `I` должна существовать по крайней мере одна точка, в которой функция `f(x)` достигает своего наибольшего значения `М`, и другая точка, в которой функция `f(x)` достигает своего наименьшего значения `m`.  
- Пусть `e` – какое–нибудь положительное число. Тогда мы можем подобрать такое целое положительное число `N`, что все члены `a_n` последовательности `1, ½, ⅓, ..., 1/n, ...`, для которых `n >= N`, будет лежать внутри интервала `I` длины `2e` с центром в точке `e`.
- Если последовательность имеет предел, то она называется сходящейся. Последовательность не имеющая предела – расходящейся.
- Последовательность `a_1, a_2, ...` имеет предел `a` при неограниченном возрастании `n`, если каждому сколь угодно малому положительному числу `e` можно поставить в соответствие такое целое положительное число `N` (зависящее от `e`), что неравенство `|a - a_n| < e` выполняется для всех значений `n >= N`. 
- Последовательность, в которой `a_n+1 > a_n` называется монотонно возрастающей. Последовательность, в которой `a_n > a_n+1` называется монотонно убывающей.  Такие последовательности могут приближаться к своему пределу только с одной стороны, либо слева, либо справа.
- Монотонно возрастающая последовательность, ограниченная сверху, сходится к некоторому пределу. Монотонно убывающая последовательность, ограниченная снизу, также сходится к некоторому пределу. 

## Предел

- Функция `f: N -> X`, областью определения которой является множество натуральных чисел, называется последовательностью.
- Число `A из R` называется пределом последовательности `{x_n}`, если для любого `e > 0` существует номер `N` такой, что при всех `n > N` имеем `|x_n - A| < e`.
- Последовательность, принимающая только одно значение называется постоянной.
- Если существуют число `A` и номер `N` такие, что `x_n = A` при любом `n > N`, то последовательность `{x_n}` будем называть финально постоянной. 
- Последовательность `{x_n}` называется фундаментальной, если для любого числа `e > 0` найдется такой номер `N`, что из `n > N` и `m > N` следует `|x_m – x_n| < e`.
- Для того, чтобы ряд `a_1 + a_2 + ... a_n + ...`  сходился, необходимо чтобы его члены стремились к нулю при `n -> к бесконечности`, т.е.  `lim a_n = 0`.
- Ряд называется абсолютно сходящимся, если сходится аналогичный ряд из модулей. 
- Если члены ряда по абсолютной величине мажорируется с членами сходящегося числового ряда, то исходный ряд сходится абсолютно.
- Проколотой окрестностью точки называется окрестность точки, из которой исключена сама эта точка.
- Последовательность `{xn}` называется ограниченной, если существует число `M`, что `|xn| < M` при любом `n` из `N`.
- Основные выводы:

  - Финально постоянная последовательность сходится.
  - Любая окрестность предела последовательности содержит все члены последовательности, за исключением конечного их числа.
  - Последовательность не может иметь двух различных пределов.
  - Сходящаяся последовательность ограничена.

- Пусть `{xn}`, `{yn}` — числовые последовательности. Если `lim xn = A`, `lim yn = B`, то  

  - `lim (xn + yn) = A + B`.
  - `lim (xn * yn) = A * B`.
  - `lim xn/yn = A/B`.

- Пусть `{xn}`, `{yn}` — две сходящиеся последовательности, причем `lim xn = A`, `lim yn = B`. Если `A < B`, то найдется такой номер `N`, что при любом `n > N` выполняется неравенство `xn < yn`.
- Пусть `{xn}`, `{yn}`, `{zn}` таковы, что при любом `n > N` имеет место соотношение `xn <= yn <= zn`. Если при этом последовательности `{xn}`, `{zn}` сходятся к одному и тому же пределу, то последовательность `{yn}` также сходится к этому же пределу.
- Последовательность `{xn}` называется фундаментальной (или последовательностью Коши), если для любого числа `e > 0` найдется такой номер `N`, что из `n > N` и `m > N` следует `|xm - xn| < e`. 
- Числовая последовательность сходится тогда и только тогда, когда она фундаментальная.
- Для того, чтобы неубывающая последовательность имела предел, необходимо и достаточно, чтобы она была ограниченной сверху. 
- Каждая ограниченная последовательность действительных чисел содержит сходящуюся подпоследовательность.
- Из каждой последовательности действительных чисел можно извлечь сходящуюся подпоследовательность или подпоследовательность стремящуюся к бесконечности.
- Число или символ `+inf/-inf` называется частичным пределом последовательности, если в ней есть подпоследовательность, стремящаяся к этому пределу. Нижний и верхний пределы ограниченной последовательности являются соответственно наименьшими и наибольшими из ее частичных пределов.
- Последовательность сходится тогда и только тогда, когда сходится любая ее подпоследовательность.

## Предел функции

- Функция `f: E -> R` стремится к `A` при `x`, стремящимся к `a`, или `А` является пределом функции `f` при `x`, стремящимся к `a`, если для любого `e > 0` существует число `delta > 0` такое, что для любой точки `x` из `E` такой, что `0 < |x - a| < delta`, выполнено соотношение `|f(x) - A| < e`.
- Проколотой окрестностью точки называется окрестность точки, из которой исключена сама эта точка.
- Число `A` называется пределом функции `f: E -> R` при `x`, стремящимся по множеству `E` к точке `a` (предельной для `E`), если для любой окрестности точки `A` найдется проколотая окрестность точки `a` в множестве `E`, образ которой при отображении `f: E -> R` содержится в заданной окрестности точки `A`.
- Соотношение `lim f(x) = A` имеет место тогда и только тогда, когда для любой последовательности `{xn}` точек `xn` из `E\a`, сходящейся к `а` последовательность `{f(xn)}` сходится к `A`.
- Функция `f: E -> R` называется финально постоянной при `x -> a`, где `x` из `E`, если она постоянна в некоторой проколотой окрестности `U(a)` точки `a`, предельной для множества `E`.
- Функция `f: E -> R` называется ограниченной (сверху, снизу) если найдется число `C` из `R` такое, что для любого `x` из `E` выполнено соответственно `|f(x)| < C`, `f(x) < C`, `C < f(x)`.
- Отображение `x -> a^x` называется показательной функцией и есть отображение вида `R -> R+`. Обратное отображение называется логарифмом `loga: R+ -> R`.
- Элементы совокупности `В` суть непустые множества и в пересечении любых двух из них содержится некоторый элемент из той же совокупности.
- Пусть `f: X -> R` — функция на множестве `X`; `B` — база в `X`. Число `A` из `R` называется пределом функции `f: X -> R` по базе `B`, если для любой окрестности `V(A)` точки `A` найдется элемент `b` из `B`, образ которого `f(b)` содержится в окрестности `V(A)`.
- Колебанием функции `f: X -> R` на множестве `E` из `X` называется величина `w(f;E) := sup |f(x1) - f(x2)|`, то есть верхняя грань модуля разности значений функции на всевозможных парах точек `x1`, `x2` из `E`.
- Пусть `X` — множество и `B` — база `X`. Функция `f: X -> R` имеет предел по базе `B` в том и только в том случае, когда для любого числа `e > 0` найдется элемент `b` из `B` на котором колебания функции меньше `e`.
- Чтобы монотонная функция имела предел, необходимо и достаточно, чтобы она была соответствующе ограничена.
- Говорят, что функция `f` есть бесконечно малая по сравнению с функцией `g` при базе `B` и пишут `f = o(g)`, если финально при базе `B` выполнено соотношение `f(x) = alpha(x) * g(x)`, где `alpha` — функция, бесконечно малая при базе `B`.

# Непрерывные функции

- Функция `f` непрерывна в точке `a`, если ее значения `f(x)` по мере приближения аргумента `x` к точке a приближаются к значениям `f(a)` функции в самой точке `а`.
- Функция `f` называется непрерывной в точке `a`, если для любой окрестности `V(f(a))` значения `f(a)` функции в точке `a` найдется такая окрестность `U(a)` точки `a`, образ которой при отображении `f` содержится в `V(f(a))`.
- Если функция `f: E -> R` не является непрерывной в некоторой точке множества `E`, то эта точка называется точкой разрыва функции `f`.
- Локальными называются такие свойства функций, которые определяются поведением функции в сколь угодно малой окрестности точки области определения.
- Глобальным свойством функции называется свойство, связанное со всей областью определения функции.
- Если функция, непрерывная на отрезке, принимает на его концах значения разных знаков, то на отрезке есть точка, в которой функция обращается в нуль.
- Функция, непрерывная на отрезке, ограничена на нем. При этом на отрезке есть точка, где функция принимает максимальное значение, и есть точка, где она принимает минимальное значение. 
- Монотонная функция — это функция, которая всё время либо не убывает, либо не возрастает.
- Каждая строго монотонная функция `f: X -> R`, определенная на числовом множестве `X` из `R`, обладает обратной функцией `f^-1: Y -> R`, которая определена на множестве `Y = f(X)` значений функции `f` и имеет на `Y` тот же характер монотонности, какой имеет функция `f` на множестве `X`.


# Дифференциальное исчисление

- Функция `f: E -> R`, определенная на множестве `E` из `R`, называется дифференцируемой в точке `a` из `E`, предельной для множества `E`, если существует такая линейная относительно приращения `x - a` аргумента функция `A * (x - a)`, что приращение `f(x) - f(a)` функции `f` представляется в виде: `f(x) - f(a) = A * (x - a) + o(x - a)`. То есть функция дифференцируема в точке `a`, если изменение ее значений в окрестности исследуемой точки линейно с точностью до поправки, бесконечно малой по сравнению с величиной `x - a` смещения от точки `a`.
- Линейная функция `A * (x - a)` называется дифференциалом функции `f` в точке `a`.
- Величина `f'(a) = lim (f(x) - f(a))/(x - a)` называется производной функции в точке `a`. Что равносильно `(f(x) - f(a)) / (x-a) =f'(a) + alpha(x)`, и `f(x) - f(a) = f'(a) * (x - a) + o(x - a)`.
- Если функция `f: E -> R` определена на множестве `E` из `R` и дифференцируема в точке `x0` из `E`, то прямая, задаваемая уравнением `у - f(x0) = f'(x0) * (x - x0)`, называется касательной к графику этой функции в точке `(x0, f(x0))`.
- Если функции `f: X -> R`, `g: X -> К` дифференцируемы в точке `x` из `X`, то

  - `(f + g)’(x) = (f’ + g’)(x)`.
  - `(f * b)’(x) = f’(x) * g(x) + f(x) * g’(x)`.
  - `(f/g)’(x) = (f’(x)*g(x) - f(x) * g’(x)) /g^2(x)`.
  - `(g (f))’(x) = g’(f(x)) * f’(x)`.

- Пусть функции `f: X -> Y`, `f^-1: Y -> X` взаимно обратны и непрерывны в точках `x0` из `X` и `f(x0) = y0` из `Y`. Если функция `f` дифференцируема в точке `x0` и `f’(x0) != 0`, то функция `f^-1` также дифференцируема в точке `y0`, причем `(f^-1)’(y0) = (f’(x0))^-1`.
- Точка `x0` из `E` называется точкой локального максимума (минимума), а значение функции в ней — локальным максимумом (минимумом) функции `f: E -> R`, если существует окрестность `U(x0)` точки `x0`, в множестве `E` такая, что в любой точке `x` из `U(x0)` имеем `f(x) <= f(x0)` (соответственно, `f(x) >= f(x0)`). 
- Точки локального максимума или минимума называются точками локального экстремума, а значения в функции в них — локальными экстремумами функции.
- Точку `x0` из `E` экстремума функции `f: E -> R` называют точкой внутреннего экстремума, если `x0` является предельной точкой как для множества `E- = {x < x0}`, так и для множества `E+ = {x > x0}`.
- Если функция `f: E -> R` дифференцируема в точке внутреннего экстремума `x0` из `E`, то ее производная в этой точке равна нулю `f’(x0) = 0`.
- Алгебраический полином вида `p(x) = p(x0) + p’(x0)/1! * (x - x0) + ... + p^(n) (x0)/n! * (x - x0)^n` называется полиномом Тейлора порядка `n` функции `f(x)` в точке `x0`.
- Между характером монотонности дифференцируемой функции и знаком ее производной `f’` на этом интервале имеется взаимосвязь:

  - `f’(x) > 0` => `f` возрастает.
  - `f’(x) >= 0` => `f` не убывает.
  - `f’(x) = 0` => `f` = const.
  - `f’(x) <= 0` => `f` не возрастает.
  - `f’(x) < 0` => `f` убывает.

- Для того чтобы точка `x0` была точкой экстремума функции `f: U(x0) -> R`, определенной в окрестности `U(x0)` этой точки, необходимо выполнение одного из двух условий: либо функция не дифференцируема в `x0`, либо `f’(x0) = 0`.
- Функция `f: ]a, b[ -> R` определенная на интервале `]a, b[` из `R`, называется выпуклой на нем, если для любых точек `x1`, `x2` из `]a, b[` и любых числа `n1 >= 0`, `n2 >= 0` таких, что `n1 + n2 = 1`, имеет место неравенство `f(n1*x1 + n2*x2) <= n1 * f(x1) + n2 * f(x2)`.

# Дифференциальное исчисление. Общая теория

- Пусть X — линейное пространство над полем действительных или комплексных чисел. Функция || ||: X -> R ставящая каждому вектору x из X в соответствие действительное число ||x||, называется нормой в линейном пространстве X, если она удовлетворяет следующим трем условиям:

  - `||x|| = 0 ⇔ x = 0` (невырожденность).
  - `||c * x|| = |c| * ||x||` (однородность).
  - `||x1+x2|| <= ||x1|| + ||x2||` (неравенство треугольника).


- Линейное пространство с определенной на нем нормой называется нормированным линейным пространством. 
- Говорят, что в линейном пространстве `X` эрмитова форма, если задано отображение `<,>: X * X -> C`, обладающее свойствами:

  - `<x1, x2> = не <x1, x2>`.
  - `<с * x1, x2> = c * <x1, x2>`.
  - `<x1 + x2, x3> = <x1, x3> + <x2, x3>`.

- Невырожденную положительную эрмитову форму в линейном пространстве называют скалярным произведением в этом пространстве. 
- Отображение `A: X1 * X2 * ... * Xn -> Y` прямого произведения линейных пространств `X1 * X2 * … * Xn` в линейное пространство `Y` называется полилинейным, если это отображение `y = A(x1, ..., xn)` линейно по каждой переменной при фиксированных значениях остальных переменных. 
- Пусть `A: X1 * X2 * ... * Xn -> Y` — полилинейный оператор, действующих из прямого произведения нормированных пространств `X1, ..., Xn` в нормированное пространство `Y`. Тогда `||A|| := sup |A(x1, ..., xn)| / (|x1| * … * |xn|)`, где верхняя грань берется по всевозможным наборам `x1, ..., xn` отличных от нуля векторов пространств `X1, ..., Xn`, называется нормой полилинейного оператора `A`.
- Полилинейный оператор `A: X1 * X2 * ... * Xn -> Y` называется ограниченным, если существует такое число `М` из `R`, что при любых значениях `x1, ..., xn` из пространств `X1, .., Xn` соответственно справедливо неравенство `|A(x1, ..., xn)| <= M * |x1| * ... * |xn|`. Ограниченными являются только те операторы, которые имеют конечную норму.
- Для полилинейного оператор `A: X1 * X2 * ... * Xn -> Y` действуют условия:

  - `A` имеет конечную норму.
  - `А` – ограниченный оператор.
  - `А` – непрерывный оператор.
  - `А` – оператор, непрерывный в точке `(0, ..., 0)` из `X1 * ... * Xn`.

  # Дифференциал отображения

- Пусть `X`, `Y` — нормированные пространства. Отображение `f: E -> Y` множества `E` из `X` в `Y` называется дифференцируемым в точке `x` из `E`, внутренней для `E`, если существует такое линейное непрерываное отображение `L(x): X -> Y`, что `f(x+h) - f(x) = L(x)*h + alpha(x; h)`, где `alpha(x; h) = o(h)` при `h -> 0`, `x+h` из `E`.
- Линейная относительно `h` функция `L(x)` из `L(X; Y)`, удовлетворяющая соотношению `L(x): X -> Y`, что `f(x+h) - f(x) = L(x)*h + alpha(x; h)`, называется дифференциалом, касательным отображением или производной отображения `f: E -> Y` в точке `x`. `L(x)` обозначается как `df(x)`, `Df(x)` или `f'(x)`.
- Если отображение `f: E -> Y` дифференцируема во внутренней точке `x` множества `E` из `X`, то его дифференциал `L(x)` в этой точке определен однозначно. 
- `df(A) * h = d(A^-1) * h = - A^-1 * h * A^-1`.
- Если отображение `y = f(x) = f(x1, ..., xm)` дифференцируемо в точке `a = (a1, ..., am)` из `X1 * ... * Xm = X`, то оно имеет в этой точке частные дифференциалы по каждой из переменных, причем полный дифференциал и частные дифференциалы связаны соотношением `df(a) * h = d1f(a) * h1 + ... + dmf(a) * hm`.



