### Operaciones elementales

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

Sirven para acondicionar datos y realizar divisiones y multiplicaciones por *potencias de 2*.

* Operación lógica AND (Y):
	* ``and r0, r3  @ r0 <- r0 AND r3``
* Como máscara, pone a '0' los bits del registro que valen '0' en la máscara y deja como están los que valen '1' en la máscara.

* Operación lógica OR (O):
	* ``orr r0, r3  @ r0 <- r0 OR r3``
* Como máscara, pone a '0' los bits del registro que valen '0' en la máscara y deja como están los que valen '1' en la máscara.

#### Desplazamientos

* **Izquierda:**
	* ``lsl r0,r0, #3  @ r0 <- r0 << 3``
* Equivale a multiplicar por 2<sup>n</sup>

* **Derecha**
	* ``lsr r0, r0,#4  @ r0 <- r0 >> 4``
* Equivale a dividir por 2<sup>N</sup>

* **Aritmético a la Derecha**
	* ``asr r0,r0, #5  @ r0 <- r0 >> 5
* Equivale a dividir 2<sup>N</sup>
* Conserva el signo al replicar el bit de mayor peso del argumento

### Directo a registro

![[Registro.png]]

## Acceso a memoria
**Ejercicio: Dada la sentencia A[12] = h + A[8] obtener el código ensamblador equivalente sabiendo:**
* Que el compilador ha asignado la variable h al registro r2 
* Que la dirección de comienzo del vector A está almacenada en el registro r3

Sol: ``ldr r0, [r3, #32]  @ r0 <- A[8]``

