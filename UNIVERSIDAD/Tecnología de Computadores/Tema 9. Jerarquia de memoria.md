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
* Memoria más cercana al procesador  === las más rápida
* Menor capcidad posible
* Debido a estructura de datos, a continuación puede acceder a los datos en direcciones próximas en memoria. 
* Debido a secuencialidad, es muy posible que se acceda a continuación se accede a la siguiente. 
* 