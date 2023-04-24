### Propiedades de la memoria
* Volatilidad
* Reescritura
* Capacidad
* Tiempo de Accesos
* Coste por bit 
* Modos de Accesos
	* Secuencial
	* Directo
	* Aleatorio 
	* Por contenido

### Clasificación de memorias

Por funcionalidad:
* Caché
* Central o Principal
	* RAM 
	* ROM
* Almacenamiento Secundario

Por tecnología: 
* Obsoletas
* Semiconductores
* Magnética
* Óptica
    * Reescribile
    * Escribible
    * ROM

### Jerarquía de la memoria
**Dado un sistema de almacenamiento, hay tres parámetros del mismo que dependen entre sí:**
* Tiempo de acceso / tasa trasferencia
* Capacidad 
* Coste por bit

**Esta dependencia impide que un computador tenga gran cantidad de memoria a alta velocidad y coste razonable.** 

**Esto obliga a implementar una jerarquía de memoria con varios niveles de capacidad creciente y velocidad decreciente**

### Memoria caché
* Memoria más cercana al procesador === la más rápida
* Menor capacidad posible
* Debido a estructura de datos, a continuación puede acceder a los datos en direcciones próximas en memoria. 
* Debido a secuencialidad, es muy posible que se acceda a continuación se accede a la siguiente. 
* Debido a los bucles, es posible que vuelvan a ejecutarse instrucciones recientemente ejecutadas. 
* Por otro lado, los condicionales provocan alteraciones en la secuencialidad. 

## Organización 2D
* Se organiza mediante:
    * Buses
    * Direcciones 
    * Datos
* EL primero determina la direccion de memoria que el procesador quiere acceder y el segundo transporta los datos a la memoria. 
* Estructura en filas y columnas (dos dimensiones)
* Cada fila de la matriz de celdas de bit contiene una palabra. 
* Se necesita un descodificador que activa la fila correspondiente a la dirección accedida.
* Cada bit constituye una columna de matriz de celdas de bit. 

