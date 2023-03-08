
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

``d1 - d2 = m(Xk + 1) + b - yk -yk -1 + m(Xk + 1) + b
``d2 = (Yk + 1 -y) = yk + 1[m(yk + 1) + b] = yk + 1 --> -m(Xk + 1) - b
``d1 = y - yk = m(yk + 1) + b - yk = mxK + m + b - yk = m(xk + 1) + b - yk
