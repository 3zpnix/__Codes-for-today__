<h1>大家好</h1> - sarap daw ng tae sabi ni geoven 🤭

```
ATTENTION TO COPY & PASTE >
```
一 (1)
===
```
#include <stdio.h>
#include <stdlib.h>
main() 
{
    int i,j,k;
    j=0;
    while (j<256) 
    {
        k=0x80;
        while(k)
        {
            if (k & j)
                printf("1");
            else
                printf("0");
        k = k >> 1;
        }
    printf("\n");
    j++;
    }
}
```
二 (2)
===

```
#include <stdio.h>
#include <stdlib.h>
main() 
{
    int i,j,k;
    j=0;
    for(j=0;j<256;j++)
    {
        k=128;
        for(i=0;i<8;i++)
        {
            if (k & j)
                printf("1");
            else
                printf("0");
        k = k >> 1;
        }
    printf("\n");
    j++;
    }
}
```
三 (3) 
===

```
#include <stdio.h>
#include <stdlib.h>
main() 
{
    int y = 0x01; 
    int i;  
    while (y <= 0x80) 
    {
        for (i = 0; i < 8; i++) 
        {
            if (y == (1 << i))
                printf("1");
            else
                printf("0");
        }
        printf("\n");
        y = y << 1;
    }
    return 0;
}
```
四 (4)
===
```
#include <stdio.h>
#include <stdlib.h>
main() 
{
    int y = 0x80;  
    int i;  
    while (y > 0) 
    {
        for (i = 0; i < 8; i++)  
        {
            if (y == (1 << i))
                printf("1");
            else
                printf("0");
        }
        printf("\n");
        y = y >> 1; 
    }
    return 0;
}
```
五 (5)
===

```
#include <stdio.h>
#include <stdlib.h>
main() 
{
    int x, y = 0x80;
    printf("Input x: ");
    scanf("%d", &x); 

    while (y) 
    {
        if (x & y)
            printf("1");
        else
            printf("0");
        y = y >> 1;
    }
    printf("\n");
}

```
===
