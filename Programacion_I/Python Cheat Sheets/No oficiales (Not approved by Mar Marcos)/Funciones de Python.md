#programacion_I #python 
[[Programación_I]]

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
make_pizza("pepperoni")
```

