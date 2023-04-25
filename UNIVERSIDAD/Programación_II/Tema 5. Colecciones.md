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

