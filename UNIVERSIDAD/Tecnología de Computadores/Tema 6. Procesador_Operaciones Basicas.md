#### Operaciones elementales

Indicar suma:
```
add a,b,c @ a <- b + c
```

Suma de cuatro comandos:
```
add a,b,c    @  a <- b + c
add a, a, d  @  a <- b + c + d 
add a, a, e  @  a <- b + c + d + e
```

#### Operaciones aritméticas elementales

Si el compilador asigna las variables f,g,h,i,k y a registros r0,r1,r2,r3 y r4, ¿cuál es el código?

```armasm
add r5,r1,r2  @ r5 <- g + h
add r6, r3, r4 @ r6 i + k
add r7, r5, r6 @ f <- (g+h) - (i+k)
```

#### Instrucciones aritméticas
* Suma y resta con dos registros:
	* ``add r0,r1,2     sub r0,r1,r2``
* Suma y resta con dato inmediato:
	* ``add r0, r1, #2  sub r0,r1,#4``
* Multiplicación
	* ``mul r0,r0,r1  sub r0,r1``

### Operaciones lógicas y desplazamiento

