
--- 
#### Lista de dígitos a partir de texto

```python

num_input = int(input("..."))
lista = [];resto = 0

while num_input > 0:
	resto = num_input % 10
	nump_input = num_input // 10
	lista = [resto] + lista

print(lista) 
```