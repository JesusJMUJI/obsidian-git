3. Implementar RAm de 4 registros y 8 bits. 
4. Memoria capaz de almacenar 16 regs. de 4 bits. 
5. CPU con dps numeros binarios de 8 bits, X y Y. 
6. usando HACK, 
    1. programa con 3 numeros de entrada, ABC
    2. Si A >= B, el programa obtiene A + C. 
    3. En caaso contrario, se suma B y C. 
    4. Los valores A B y C se eneucnetra al inicio del programa, las posiciones de memoria 0,1 y 2. 
    5. El resultado se almacenara en la posicion 3 de la memoria.
7. ![[EjMemoria.png]]

---
16 bits - DiR
16 bits - dato
Cada POS menos -> 1 DATO

**Numero de conjuntos = 4
Numero de bloques = 2
Numero de datos = 2**

| 0000 0000 0000 00000 	| 10  	|   	| 0000 1000 	| 200 	|   	| 0000 0000 0000 0000 	|
|----------------------	|-----	|---	|-----------	|-----	|---	|---------------------	|
| 0000 0001            	| 14  	|   	|           	| 204 	|   	| 00\|01\|0           	|
| 0010                 	| 18  	|   	|           	| 208 	|   	| 00\|01\|0           	|
| 0011                 	| 12  	|   	|           	| 212 	|   	| 10\|00\|0           	|
| 0100                 	| 100 	|   	|           	| 300 	|   	| 00\|10\|1           	|
|                      	| 104 	|   	|           	| 304 	|   	| 01\|01\|0           	|
|                      	| 108 	|   	|           	| 308 	|   	|                     	|
|                      	| 112 	|   	|           	| 312 	|   	|                     	|
|                      	|     	|   	|           	| 400 	|   	|                     	|
|                      	|     	|   	|           	| 404 	|   	|                     	|
|                      	|     	|   	|           	| 408 	|   	|                     	|
|                      	|     	|   	|           	| 412 	|   	|                     	|
|                      	|     	|   	|           	|     	|   	|                     	|

![[DibujoEjercicioMemoria.excalidraw]]
