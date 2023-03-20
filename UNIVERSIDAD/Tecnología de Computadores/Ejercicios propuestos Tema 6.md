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
vector1:    .byte   2,3,4,5
vector2:    .space  16
            .text
            ldr     r0,=vector1
            ldrb    r1,[r0]
            ldr     r2,=vector2
            str     r1,[r2]
            
            ldrb    r1,[r0,#1]
            str     r1,[r2,#4]
            
            ldrb    r1,[r0,#2]
            str     r1,[r2,#8]


```