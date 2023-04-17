18. Subruitina que dado vector de n words, devuelva el i-enesimo del mismo o mensaje de error si accede a un elemendo no existente:
    Parámetros:
	    - vector 
	    - n
	    - índice

```css

Cuadrados: recorrer array y leer elementos
______________________________
r0 <- dir comienzo matriz
r1 <- nº filas
r2 <- nº columnas
r3 <- dir comienzo matriz Cuadrado

		.data

matriz: .word 11,12,13,14,21,22,23,24,31,32,33,34

n:      .word 2

m:      .word 3

cuadra: .space 16

		.text
main:   ldr r0, =matriz
		ldr r1, =n
		ldr r1, [r1]
		ldr r2, =m
		ldr r2, [r2]
		ldr r3, =cuadra
		bl cuadrados
		wfi

cuadrados: push{r4 - r6,lr}
		mov r4, #0
		mov r6, #0
		mov r5, #1
		mul r5, r1
		mul r5, r2
		
bucle:  cmp r4, r5
		bge fin
		push {r0}
		ldr r0, [r0,r6]
		bl square
		str r0,[r3,r6
		pop {r0}
		add r4,r4,#1
		add r6,r6,#4
		b bucle
fin:    pop {r4-r6,pc}

square:  mul r0,r0 @cuadrado
		 mov pc,lr
		.end

```