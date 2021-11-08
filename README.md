# famcs-acquisition-and-rendering-information-structure-of-the-algorithm
## Получение и визуализация информационной структуры алгоритма

```
for(i=1;i<N;i=i+1)
{
   for(j=1;j<N;j=j+1)
   {
       r=0
       for(k=0;k<N;k=k+1)
       {
           r=r+a[i][k]*b[k][j]
       }
       c[i][j]=r
    }
}
```
