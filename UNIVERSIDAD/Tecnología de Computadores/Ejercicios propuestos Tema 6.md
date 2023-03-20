----
Ejercicio 3.

```asmarm
	.data
num:.word 5
	.text
	ldr r0, =numero
	ldr r3,[0]
	mov r2,#1
	and r3,r2
```

```
r3 <- 5

	  *32 bits*
     -----------
r3   0 --- 00101    5o (par/impar)
r2   00 --- 0001    (máscara)
____________________________________
r3   0--------01    operacion logica

```

Ejercicio 4.
```
		.data
vector  .byte    2,3,4,5


```