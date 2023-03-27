----
Ejemplo p-then-else

```
if (x==y)
{
	z = x+y
}
else
	z = x+5
```

```
		.text
			r0,r1,r2 ya tienen values
		cmp r0,r1
		bne else
		add r2,r0,r1
else:   add r2, r0,#5
seguir: 
```

## Bucle for 

```
g -> r1         dir v       V[0]
h -> h2         dir v + 4   V[1]
				dir v + 8   V[2]
				dir v + 12  V[3]
				dir v + 16  V[4]
				dir v + 20  V[5]

}
direccion 
comienzo vector V    } -> r3

for i = 1 to 20 step 2 
	g ? g + V[i]
}
```