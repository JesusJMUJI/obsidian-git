#programacion_I
#python 
#mar_marcos_approved

--- 
#### Lista de dígitos a partir de texto

```python

num_input = int(input("..."))
lista = [];resto = 0

while num_input > 0:
	resto = num_input % 10
	nump_input = num_input // 10
	lista = [resto] + lista

print(lista) // print(lista es {0} es {1}.format(num_input,lista))
# 
```