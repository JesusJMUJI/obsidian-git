#programacion_I #python [[Programación_I]]

---

Las funciones son bloques de código que se dedican a realizar una función en específico.
La información pasada A UNA función se llama *argumento* y la información recibida por una función *parámetro*.

---

#### Función sencilla
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

#### Devolver un valor
```python
def add_numbers (x,y):
	"""Add two numbers and return the sum."""
	return x + y

sum = add_numbers(3,5)
print(sum)
```
