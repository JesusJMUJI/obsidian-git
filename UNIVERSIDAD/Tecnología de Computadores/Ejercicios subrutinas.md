18. Subruitina que dado vector de n words, devuelva el i-enesimo del mismo o mensaje de error si accede a un elemendo no existente:
    Parámetros:
	    - vector 
	    - n
	    - índice

```arm

Cuadrados: recorrer array y leer elementos
______________________________
r0 <- dir comienzo matriz
r1 <- nº filas
r2 <- nº columnas
r3 <- dir comienzo matriz Cuadrado

	    .data
matriz: .word    11,12,13,14,21,22,23,24,31,32,33,34
n:      .word    3
m:      .word    4
i:      .word    2
j:      .word    3

		.text
main:   

```