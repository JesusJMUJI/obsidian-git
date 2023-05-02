```csharp
public Object DameProximo(ArrayList arrayList, Object objeto)
{
    if (!arrayList.Contains(objeto)) return null;
    int aux = arrayList.IndexOf(objeto);

    if (aux > 0) return arrayList[aux - 1];
    if (arrayList.Count > 1) return arrayList[aux + 1];
    return arrayList[aux];
}
```

```cs
public void EliminarPares(List<int> l){
    for (int = 0; i < l.Count; i++)
    {
        if (l[i] % 2 == 0) l.Remove(l[i]);
    }
}
```

```cs
public class Cancion(T t){
    
}
```


