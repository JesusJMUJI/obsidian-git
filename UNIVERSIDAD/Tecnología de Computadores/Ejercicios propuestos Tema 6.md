----
Ejercicio 3.

```asmarm
	.data
num:.word 5
	.text
	ldr r0, =numero
	ldr r3,[0]
	mov r2,#1
	___ r3,r2
```

```
r3 <- 5

	  *32 bits*
     -----------
r3   0 --- 00101
r2   00 --- 0001
--------------------------------
r3              operacion logica

```