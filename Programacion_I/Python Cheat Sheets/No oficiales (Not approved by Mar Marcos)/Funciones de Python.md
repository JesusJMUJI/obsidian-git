#programacion_I #python [[Programación_I]]

---

Las funciones son bloques de código que se dedican a realizar una función en específico.
La información pasada A UNA función se llama *argumento* y la información recibida por una función *parámetro*.

---

La primera línea de una función es su definición, marcada por la palabra *def*. 
El nombre de la función la sigue los paréntesis y un doble punto. 
El cuerpo de una función se indenta un nivel.
		Para llamar una función, escribe el nombre de esta con paréntesis al final. 

## Funciones sencillas

```python
def greet_user():
	"""Display a simple greeting"""
	print("Hello!")
greet_user()
```

#### Pasar un argumento

```python
def greet_user(username):
	"""Display string personalizado."""
	print("Hello, " + username + "!")
greet_user('jesse')
```

#### Valores predeterminados

```python
def make_pizza(topping = 'bacon'):
	"""Make a single-topping pizza."""
	print("Have a " + topping + " pizza!")

make_pizza() 
# Puede cambiarse por input de usuario con make_pizza(input())
make_pizza("pepperoni")
```

## Devolver un valor

#### Usando un valor por defecto
```python
def describe_pet(name, animal = 'dog')
	"""Display info about pet"""
	print("\nI have a "+ animal + ".")
	print("Its name is " + name + ".")

describe_pet('harry', 'hamster')
describe_pet('willy')
```

#### Usar *None* para hacer un argumento opcional

```python
def describe_pet(animal, name=None)
	print("\nI have a " + animal + ".")
	if name:
		print("Its name is " + name + ".")

describe_pet('hamster', 'harry')
describe_pet('snake')
```

## Argumentos de palabras clave (*keywords*) y posicionales

Los dos tipos principales de argumentos son los posicionales y *keywords*. 
Cuando usas argumentos posicionales, Python enlaza el primer argumento de la función con el primer parámetro de esta. 

Con argumentos *keyword*, tu específicas que argumento debe ser asignado al llamar a la función. 