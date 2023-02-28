----

**Ley de Hofstadter modificada**: tiempo necesario para estudiar la técnica de recursividad en programación es mayor a del que se espera. 

*¿Como tomar un plato de sopa de forma recursiva?*

* Tomar(Sopa) si:
	* Si el plato está vacío, sopa acabada 😊
	* En otro caso tomar cucharada y Tomar(SOPA)

`factorial (n) = 
`* Si n=0 entonces 1
`* en otro caso es n*factorial(n-1)```

```cs
factorial(3) = 3*factorial(2) = 3*2*factorial(1) = 3*2*1*factorial(0) = 3*2*1*0
```

* Un método es recursivo cuando puede llamar a sí mismo o llamar a otro dsde se puede invocar al primero. 
* Un méotod recursivo SIEMPRE tiene que acabar la ejecución en algún momento.
* Se distinguen dos apartados:
	* Condición de parada: Solución del problema
	* Llamada recursivo: Relación entre la solución actual y la solución de un problema de tamaño menor. 