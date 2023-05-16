$$\sum_{i=a}^{b} k = k(b-a+1)$$

$$\sum_{i=1}^{N} i = \frac{N(N+1))}{2} = \frac{N^2}{2} + \frac{N}{2} $$

**Calcular el coste computacional de los algoritmos de suma de matrices y de multiplicación de matrices, implementados mediante los siguientes métodos:**

```cs
        public int[,] SumaMatrices(int[,] a, int[,] b) {

            int[,] resultado = new int[a.GetLength(0), a.GetLength(1)];

            for (int i = 0; i < a.GetLength(0); i++)

                for (int j = 0; j < a.GetLength(1); j++)

                    resultado[i, j] = a[i, j] + b[i, j];

            return resultado;

        }
```

$$\sum^{N-1}_{i= 0}  \quad (\sum^{N-1}_{j=0}1) = N \rightarrow \sum^{N-1}_{i= 0}N = N * N = N^2$$
```cs
`        public int[,] ProductoMatrices(int[,] a, int[,] b) {

            if (a.GetLength(1) != b.GetLength(0)) return null;

            int[,] resultado = new int[a.GetLength(0), b.GetLength(1)];

            for (int i = 0; i < a.GetLength(0); i++)

                for (int j = 0; j < b.GetLength(1); j++) {

                    int aux = 0;

                    for (int k = 0; k < a.GetLength(1); k++)

                        aux += a[i, k] * b[k, j];

                    resultado[i, j] = aux;

                }

            return resultado;

        }`
```

$$\sum^{N-1}_{i=0} \quad \sum^{N-1}_{j=0} \quad \sum^{N-1}_{k=0} \quad 1 \space=\space \sum^{N-1}_{i=0} \quad \sum^{N-1}_{j=0} N = \sum^{N-1}_{i=0}N^2 = N*N^2 = N^3$$

----

```cs
int i = 0
While (i<a.Length){
    suma += a[i];
    i++;
}
```
$$\sum^{N-1}_{i=0}$$

```cs
int i = 0;
while (i<a.GetLength(0)){
    for (int j = 0; j<i;j++){
        a[i,j] *= a[i,j];
    }
    a[i,j] *= 2;
    i++;
}
```
$$\sum^{N-1}_{i=0} \space (1+\sum^{i-1}_{j=0}1)$$

Entregable 12 - Ej1
```cs
public void Ejemplo(int a, int[]x){
    if (a>0){
        for (int i = 0; i<n; i++)
        {
            x[i]++;
        }
    }
    else
    {
        for (int i = 0; i<n; i++)
        {
            x[i] = 0;
        }
    }
}
```


```cs
for (int = 0; i < N; i++)
{
    if (i == 0) x[i] = 8;
    else if (i == N-1) x[i] = 10;
    else x[i]++;
}
```


Este bucle es más eficiente que el anterior debido a que no se ejecutan *ifs* 
```cs
x[0] = 8;
for (int i = 1; i < N-1; i++) x[i]++;
x[N-1]=10;
```

###### Entregable 12 - Ej2

```cs
**

1.  Calcular la función de coste del siguiente método tomando como operación elemental la multiplicación: 

 public void Costoso(int[,] a, int[] b) {
       for(int i = 0; i < N-1; i++)
             if (a[i,i] != 0) 
                    for(int k = i+1; k < N; k++) {
                          int t = a[k,i] / a[i,i];
                          for(int j = 0; j < N; j++) 
                                 a[k,j] -= a[i,j] *  t;
                          b[k] -= b[i] * t;
                    }
  }

**
```

Mejor caso: *A* tiene la diagonal principal = 0 siempre
Peor caso: *A* no tiene en la diagonal principal ningún 0 

$$\sum^{N-2}_{i=0}\sum^{N-1}_{k = i + 1} (1+\sum^{N-1}_{j = 0}1) 

= \sum^{N-2}_{i=0} \sum^{N-1}_{k=i+1}(1+N)

=\sum^{N-2}_{i=0}\sum^{N-1}_{k=i+1}1\sum^{N-2}_{i=0}\sum^{N-1}_{k=i+1}N 

= \sum^{N-2}_{i=0}\sum^{N-1}_{k=i+1}1+N\sum^{N-2}_{i=0}\sum^{N-1}_{k=i+1}1 

=
$$
$$= (1+N)\sum^{N-2}_{i=0}\sum^{N-1}_{k=i+1}1
$$
