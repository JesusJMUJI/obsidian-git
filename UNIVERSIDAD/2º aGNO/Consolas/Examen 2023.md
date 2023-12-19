3. Implementar RAm de 4 registros y 8 bits. 
4. Memoria capaz de almacenar 16 regs. de 4 bits. 
5. CPU con dos numeros binarios de 8 bits, X y Y. 
6. usando HACK, 
    1. programa con 3 números de entrada, ABC
    2. Si A >= B, el programa obtiene A + C. 
    3. En caso contrario, se suma B y C. 
    4. Los valores A B y C se encuentra al inicio del programa, las posiciones de memoria 0,1 y 2. 
    5. El resultado se almacenará en la posición 3 de la memoria.
7. ![[EjMemoria.png]]

---
16 bits - DiR
16 bits - dato
Cada POS  → 1 DATO

**Número de conjuntos = 4
Número de bloques = 2
Número de datos = 2**

En caso de reemplazo, se usa **LRU**.

| 0000 0000 0000 00000 	| 10  	|   	| 0000 1000 	| 200 	|   	| 0000 0000 0000 0000 	| M 	|
|----------------------	|-----	|---	|-----------	|-----	|---	|---------------------	|---	|
| 0000 0001            	| 14  	|   	|           	| 204 	|   	| 00\|01\|0           	| M 	|
| 0010                 	| 18  	|   	|           	| 208 	|   	| 00\|01\|0           	| H 	|
| 0011                 	| 12  	|   	|           	| 212 	|   	| 10\|00\|0           	| M 	|
| 0100                 	| 100 	|   	|           	| 300 	|   	| 00\|10\|1           	| M 	|
|                      	| 104 	|   	|           	| 304 	|   	| 01\|01\|0           	| M 	|
|                      	| 108 	|   	|           	| 308 	|   	| -------             	|   	|
|                      	| 112 	|   	|           	| 312 	|   	| 01\|00\|1           	| H 	|
|                      	|     	|   	|           	| 400 	|   	| 01\|00\|1           	| M 	|
|                      	|     	|   	|           	| 404 	|   	|                     	|   	|
|                      	|     	|   	|           	| 408 	|   	|                     	|   	|
|                      	|     	|   	|           	| 412 	|   	|                     	|   	|

![[DibujoEjercicioMemoria.excalidraw]]

![[Ejercicio CPU]]

---
Junio 2023

2. Implementa, dados dos numeros de 1 bit A y B, devuelva X,Y,Z. X sera 1 cuando un numero A sea mayor a B, Y sera 1 cuando A sea igual a B y Z sera 1 cuando A sea menor que B. En los tres casos cuando ujna salisa es 1, las otras son dos ceros. 


| A   | B   | A > B | A == B | A < B |
| --- | --- | ----- | ---- | ---- |
| 0   | 0   | 0     | 1 | 0
| 0   | 1   | 0     | 0 | 1
| 1   | 0   | 1     | 0| 0
| 1   | 1   | 0     | 1| 0


6. Implementa CPU dos numeros binarios de 8 bits (A y B) y un binario de 2 bits (F). Como salida un OUT de 8 bits y un num bit (C). Cuando F es 00, devolvera en OUT la suma de A y B. Cuando es 01 devolvera la retsa de A y B. Cuando es 10, devolvera la multiplicacion de A y B. Y si es 11, devolvera el meyor de 2. En todos los casos menos 11, la salida C devolvera 1 si la operacion produce desboramiento, siendo en 0 en caso contrario. Cuando F es 11, devolvera siempre 0. 

![[Ej2 y Ej4]]

---
