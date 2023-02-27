----
```
---  
share: true  
---  
```

>[!SUMMARY]- Resumen
>[[#Arquitectura del procesador]]
>[[#Introducción al procesadorr ARM]]

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

* Las instrucciones se almacen en la memoria como:
	* Instrucciones
	* Datos
* Desde el punto de vista físico, se utiliza una estructura jerárquica:
	* Registros
	* Memoria Cache
	* Memoria Principal
	* Almacenamiento Secundario

### Codificación de los datos

* Numeros enteros
	* Binario natural
	* Signo-Maginutd
	* Complemento
	* Exceso
* Número Reales:
	* Mantisa-exponente
	* IEEE 754
* Alfanumericos
	* ASCII
	* UNICODE

### Manejo de excepciones

Existen circunstancias especiales que requieren acciones inmediatas. 
	◦ Errores de cálculo (división por cero, etc.) 
	◦ Accesos erróneos a memoria 
	◦ Reloj en tiempo real 
	◦ Errores de bus 
	◦ Llamadas al sistema 
	◦ Ejecución de instrucciones especiales 
	◦ Excepciones externas (interrupciones)

### Gestión de entrada / salida

* La interacción con los periféricos debe hacerse con nieveles de prioridad y sincronización.
* Puede realizarse mediante consulta de estado o interrupciones
* Existen dispositivos especializados en transferencia de datos (DMA)

# Introducción al procesadorr ARM

* Simplicidad los convierte en omnipresentes

### Lenguaje de la máquina 

El lenguaje maquina se representa segú ncomo esté diseñado el procesaor. 
* Reflejo de la estructura del procesador a que pertenece. 
* Muy parecidos
* Objetivos:
	* Simplificar estructura de hardware
	* Simplificar la estructura del compilador
	* Obtener un elevado rendimiento del hadrware
	* Conseguir un coste reducido

Los compiladores y emsambladores facilitan la programacion traduciendo lenguajes de alto nivel a máquina:

``Lenguaje de alto nivel => Lenguaje Ensamblador => Código Máquina``

### Formato de una línea

Cada línea del ensamblador se compone de campos: 
``etiq: add · a,b,c __ @ a<- b+c``

* etiq: Etiqueta. Referencia la línea para dar un salto a esta.
* add. Instrucción. Mnemónico de una instrucción.
* a,b,c: Operandos, argumentos de la operación. Varía en número en ninguno o tres.
* @ . . . : Comentario. Legibilidad de código. '# . . . ' / /* (. . .) /

### Programación en ensamblador

El ensamblador también proporciona: 
* Directivas. Comandos propios del ensamblador. 
* Pseudo - instrucciones: Instrucciones adicionales que facilitan la programación. 

### Directivas

Definen ciertos aspectos que indican como se debe traducir el código. Son palabras reservadas comenzadas en punto. 

Se clasifican en: 
* [[#Directivas de inicio.]]
* [[#Directivas de reserva de espacio. ]]
* [[#Directivas de propósito variado. ]]

#### Directivas de inicio
| .data                                                                                             | .text                                                                                             |
| ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| Indica el comienzo de la zona de datos. Se espeficica por defecto la dirección ```0x2007 0000```. | Indica el comienzo de la zona de código. Se espeficica por defecto como: ```0x0001 0000```.|

#### Directivas de reserva de espacio

* .byte `b1 [, b2...]` : Reserva e inciizaliza los bytes del argumento.
* .hword: Reserva medias palabras (16 bits) indicadas en el argumento en direcciones pares. 
* .word `w1`: Reserva e incializa las palrbas (32 bits) indicadas en el argumento en direcciones múltiplos de 4. 
* .quad `d1`: Reserva a incializa doubles palabras (64 bits) indicadas en direccion mútlpilos de 8. 
* .space `n`: Reserva n bytes y los inicializa a 0. 
* .ascii ``cadena1 [, cadena2...]``: Almacena en memoria las cadenas de caracteres pasadas com oargumentos (deben estar entrecomillas).
* asciiz ``cadena1 [, cadena2...]``: igual que la anterior pero resevra un byte adicional al final de cada cadena y asigna el valor 0. 

#### Directivas de propósito variado
.global etiqueta:: Sirve para indicar que etiqueta tiene ámbito global (si una etiqueta ha sido declarada en un fichero y queremos utilizarla desde otro, haremos uso de esta directiva). 
 .extern etiqueta:: Indica que la etiqueta se encuentra declarada en otro fichero. Evita que se produzca un mensaje de error. 
 .equ etiqueta , (valor): Reemplaza todas las apariciones de etiqueta por valor en el código ensamblado. 
 etiqueta .req (registro): Asigna al registro el nombre etiqueta. 
 etiqueta .unreq: Deshace la asignación.

 .thumb: Avisa al ensamblador para que use el juego de instrucciones Thumb de ARM. 
 .end: Indica que se ha alcanzado el final del código. El ensamblador ignorará el contenido del fichero de código a partir de este punto. 
 .align N: Salta las posiciones de memoria que sea necesario para que el próximo dato se ubique en una posición de memoria múltiplo de 2 N . 
 .balign N: Salta las posiciones de memoria que sea necesario para que el próximo dato se ubique en una posición de memoria múltiplo de N.

### Pseudo-instrucciones
* Instrucciones adicionales dadas por el ensamblador. 
* Carga de una direccion en un registro:
	``ldr r0, =etiqueta`` 
* Cada instrucción ocupa 16 bits y cada etiqueta 32 bits, una instruccion no puede contener una etiqueta y esta instrucción vomo tal. 

	Ejemplo:
	* ``ldr r0, =direc --- # r0 <- (direc)
	Ensamblador Equivalente:
	``((([PC, #despl] <- direc # AUX <- direc)))
	``ldr r0, [PC, #despl] # r0 <- (contenido de AUX)
