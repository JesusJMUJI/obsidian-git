#programacion_I #python [[Programación_I]]

Tus programas se pueden leer desde archivos y escribir archivos. Los archivos se abren en modo lectura ***(R)*** por defecto, pero se pueden abrir en modo lectura con **(W)** y en modo append (adición) con **(A)**.

#### Leer un archivo y guardar líneas 

```python
filename = 'siddhartha.txt'
with open(filename) as file_object:
	lines = file_object.readlines()
for line in lines:
	print(line)
```

#### Escribir un archivo

```python
filename = journal.txt
with open(filename, 'w') as file object:
	file_object.write("I love programming.")
```

#### Añadir a un archivo
```python
filename = journal.txt
with open(filename, 'a') as file object:
	file_object.write("\nI love making games.")
```
