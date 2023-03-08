
*Consideraciones de un buen algoritmo de dibujado de líneas rectas:*
* Secuencia de píxeles lo más recta posible.
* Líneas con mismo grosor e intensidad.
* Las líneas deben dibujarse lo más rápido posible. 

Ecuación de la recta: ``y = mx + b`` 

$$m=\frac{\Delta y}{\Delta x}=\frac{y_1 - y_0}{x_1 - x_0}$$

Pero la fórmula final es:
$$y_{i+1} = y_{i + m}$$

----
Ejercicio 2 --> Pi = (20,10) - Pf = (30,18)

dx = 30 -20 = 10
dy = 18 - 10 = 8

dx > dy => 10 *steps*

xinc = 1
yinc = 0,8

x = 20
y = 10

| k   | y   | (x,y) |
| --- | --- | ----- |
| 1   |     |       |
| 2   |     |       |
| 3   |     |       |
| 4   |     |       |
| 5   |     |       |
| 6   |     |       |
| 7   |     |       |
| 8   |     |       |
| 9   |     |       |
| 10  |     |       |


Ejercicio 4:
--> Pi = (-1, -6) - Pf = (2,1) * Pi = (2, 4) - Pf = (-1,-3)

dx = 3
dy = 7
steps = 7

dx < dy 

x0 = -1
x1 = -6

xinc = 0,43
yinc = 1
| k   | y                    | (x,y) |
| --- | -------------------- | ----- |
| 1   | -1 + 0,43 = -0,57=-1 |  (-1,-5)     |
| 2   |                      |       |
| 3   |                      |       |
| 4   |                      |       |
| 5   |                      |       |
| 6   |                      |       |
| 7   |                      |       |

Ej 4.2 / 7

#### Ej3.

``(2,4) -> (-1,-3)``
``(-1,-3) (2,4)
dx = -3
dy = -7
	steps = 7

xinc = -0,43
yinc = -1

| k   | (x, y) | x   |
| --- | ----- | --- |
| 1   |       |     |
| 2   |       |     |
| 3   |       |     |
| 4   |       |     |
| 5   |       |     |
| 6   |       |     |
| 7   |       ||

## Algoritmo de Bresenham

``d1 - d2 = m(Xk + 1) + b - yk -yk -1 + m(Xk + 1) + b``
``d2 = (Yk + 1 -y) = yk + 1[m(yk + 1) + b] = yk + 1 --> -m(Xk + 1) - b``
``d1 = y - yk = m(yk + 1) + b - yk = mxK + m + b - yk = m(xk + 1) + b - yk``

### Ej1.

$$(20, 10) - (30,18)$$
$$\frac{\Delta y}{\Delta x} = \frac{8}{10} = 0,8$$
$$ A =2\Delta x = -4$$
$$ B =2\Delta y-2 \Delta x = -4$$
$$ P_o =2\Delta y-\Delta x = 6$$

| k   | Pk  | (x, y)  |
| --- | --- | ------- |
| 0   | 6   | (21,11) |
| 1   | 2   | (22,12) |
| 2   | -2  | (23,12) |
| 3   | 14  | (24,13) |
| 4   | 10  | (25,14) |
| 5   | 6   | (25,15) |
|     | 2   | (27,16)        |
|     | -2  | (28,16)        |
|     | 14  |  (29,17)       |
|     |  10   |  (30,18)       |

### Ej3.
*a) (-1,-6) y (2,1)
b) (2,4) y (-1,-3)*

$$\frac{\Delta y}{\Delta x} = \frac{7}{3}> 0y>1$$

| k   | Pk  | (x, y)  |
| --- | --- | ------- |
| 0   | 1   | (-3,-1) |
| 1   |  5   |  (-2,-1)       |
| 2   |   -3  | (-1,0)        |
| 3   | +3    | (0,0)        |
| 4   |  -5   |  (1,1)       |
|  5   |     |         |

