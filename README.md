<h1>你好</h1> - Please refresh the page every time you want to copy a code, okay bye! If there are any mistakes/wrong placement of code, please do tell me so I will fix it right away, thanks!

```
TO COPY & PASTE >
```
一 (1)
===
```
#include <stdio.h>
#include <stdlib.h>
main() 
{
    char x;
    char y;
    
    for (x = 0; x <= 31; x++) 
    {  
        y = 0x80; 
        while (y) {
            if (x & y)
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
    char x, y = 0x80,i=0;

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

main()
{
    char x;
    int i = 0;

    while (i <= 255) 
    {
        char y = 0x80; 
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
        i++;
    }
}

```
===
```
sarap daw ng tae sabi ni geoven 🤭
```
===