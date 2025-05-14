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
    int x, i;
    printf("Input x: ");
    scanf("%d", &x);
    for (i = x; i <= 255; i++) 
    {
        int y = 0x80;

        while (y) {
            if (i & y)
                printf("1");
            else
                printf("0");
            y = y >> 1;
        }
        printf("\n");
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
    int x, y = 0x80,i=0;
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
===
```
8	9	C:\Users\Administrator\Documents\0514_2.c	[Error] 'for' loop initial declarations are only allowed in C99 or C11 mode
8	9	C:\Users\Administrator\Documents\0514_2.c	[Note] use option -std=c99, -std=gnu99, -std=c11 or -std=gnu11 to compile your code
```
===
