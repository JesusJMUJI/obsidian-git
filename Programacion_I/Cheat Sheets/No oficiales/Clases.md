----
Una clase define el comportamiento de un objecto y la informacion que ese objeto puede almacenar. La información de una clase se gurda en atributos mientras que una función que pertenece a ujna clase se llama método. 
Una clase _hijo_ hereda sus atributos y metodos de la clase padre.

#### Creando la clase **Perro**

```python 

class Dog():
	"""Represent a Dog"""
	def __init__ (self, name):
		"""Initialize dog object"""
		self.name = name

	def sit (self):
		"""Simulate Sitting"""
		print(self,)
```