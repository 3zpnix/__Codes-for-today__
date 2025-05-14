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
    int i = 0;
    int y;
    while (i <= 255) 
    {
        if (i <= 31) 
        {
            y = 0x80; 
            while (y > 0) 
            {
                if (i & y)
                    printf("1");
                else
                    printf("0");
                y >>= 1;
            }
            printf("\n");
        }
        i++;
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
    
    x=~x;
    y=0x80;
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
