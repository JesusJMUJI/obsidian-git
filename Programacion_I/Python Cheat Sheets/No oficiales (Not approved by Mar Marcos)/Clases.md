#programacion_I #python [[Programación_I]]

----
Una clase define el comportamiento de un objeto y la información que ese objeto puede almacenar. La información de una clase se guarda en atributos, mientras que una función que pertenece a una clase se llama método. 
Una clase _hijo_ hereda sus atributos y métodos de la clase padre.

---

#### Creando la clase **Perro**

```python 
class Dog():
	"""Represent a Dog"""
	def __init__ (self, name):
		"""Initialize dog object"""
		self.name = name

	def sit (self):
		"""Simulate Sitting"""
		print(self.name + " is sitting.")

my_dog = Dog(`Peso`)

print(my_dog.name + " is a great dog!")
my_dog.sit()
```

---

#### Heredación

```python
class SARDog(Dog):
	"""Represent a search dog."""
	def __init__(self, name):
		"""Initialize the dog."""
		super().__init__(name)

	def search(self):
		"""Simulate searching."""
		print(self.name + " is searching.")

my_dog = SARDog('Willie')
print(my_dog.name + " is a search dog.")
my_dog.sit()
my_dog.search()
```
