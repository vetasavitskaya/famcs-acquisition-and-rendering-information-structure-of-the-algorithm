# famcs-acquisition-and-rendering-information-structure-of-the-algorithm
## Получение и визуализация информационной структуры алгоритма
```
№ 17

       do  i = 1, N
           do  j = 1, N
                S1:  r =0
                do  k = 1, N
                       S2:  r = r + a(i,k) b(k,j)
                enddo
                S3:  c(i, j) = r
            enddo
       enddo

```
```
for(i=1;i<N;i=i+1)
{
   for(j=1;j<N;j=j+1)
   {
       r=0
       for(k=1;k<N;k=k+1)
       {
           r=r+a[i][k]*b[k][j]
       }
       c[i][j]=r
    }
}
```
