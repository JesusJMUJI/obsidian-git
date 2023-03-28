```cs
public class Cliente {
	public Nonbre {get;}
	public Dirección {get; set;}
}
```

La herencia es heredar de otra clase sus parámetros y añadir otros especiales.

```cs
public class ClienteEspecial: Cliente{
	public int Crédito {get; set;}
	public String ConcertarCitaDirector (){
	}
}
```

*La herencia es la técnica de programación que define una nueva clase partiendo de otra ya creada*


Ejercicio:
Establecer de forma jerárquica las siguientes clases:
1.  Cánido, Herbívoro, Gacela, Tigre, Rumiante, Animal, Carnívoro, Gato, Lobo, Vaca, Felino,  Perro, Pantera.


2) Escaleno, Cuadrado, Forma, Triángulo, Pentágono, Agudo.

```cs
Forma -> Cuadrado
Forma -> Triángulo -> Escaleno
Forma -> Triángulo -> Agudo 
Forma -> Pentágono 
```

![[Pasted image 20230328163530.png]]

