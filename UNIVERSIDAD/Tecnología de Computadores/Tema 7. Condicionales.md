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

