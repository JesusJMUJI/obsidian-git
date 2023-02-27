----

>[!SUMMARY]- Resumen
>[[#Arquitectura del procesador]]
>


# Intro

Llevar a cabo un numero de tareas segun lo que dicte el programa. 
* Un ordenador necesita: 
	* Procesadora 
	* Memoria
	* Periféricos
	* Entrada/Salida

# Arquitectura del procesador

* Proporciona todo lo relacionado para codificar y ejecutar código máquina:
	* Instrucciones
	* Formatos de instrucción y modos de direccionamiento
	* Organización de la memoria
	* Codificación de los datos
	* Excepciones
	* Gestión Entrada / Salida

### Juego o repertorio de instrucciones

* Conjunto de instrucciones elementales. 
* Grupos de bits de tamaño fijo (palabra o tamaño de instrucción)
* Instrucciones expresadas en código máquina
* Se escriben mediante lengiaje ensamblador

##### Instrucción de resta en lenguaje ensamblador

| opcode | Inm | Op  | Rn/Inm | Rs  | Rs  |
| ------ | --- | --- | ------ | --- | --- |
| 00011  | 0   | 1   | 010    | 001 | 000 |

Cada instruccion en ensamblador equivale a uns instruccion en máquina y se usa hexadecimal:

| 0001 | 1010 | 1000 | 1000 |
| ---- | ---- | ---- | ---- |
| 1     | A     |   8   |  8    |


##### Se dividen en categorías:
* Carga (ldr, ldrh, etc.)
* Almacenamiento (str, strb, strh)
* Aritméticas y lógicas (add, sub, mult, and, orr, etc.)
* Desplazamiento (lsl, lsr, asr)
* Comparaciones (cmp, tst, cmn)
* Saltos (condicionales e incondicionals) (b, beq, bne, etc.)
* Interacción con la pila (push, pop)

### Formatos de instrucción (ARM Thumb)

![[Tabla ARM Thumb.png]]

### Modos de direccionamiento

* Diferentes formas que puede espeficicarse un operador de una instrucción
* Permiten:
	* Ahorrar espacio en el código
	* Facilitar operaciones
	* Reubiar código
* Ejemplo ARM:
	* Directo a registro
	* Inmediato
	* Indirecto con desplazamiento
	* Indirecto con registro de desplazamiento
	* Relativo al PC (contador de programa)

### Rula de Datos

![[Rula de datos.png]]

### Organización de la memoria
