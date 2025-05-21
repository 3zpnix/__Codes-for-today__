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
    int i,j,k;
    j=0;
    for(j=0;j<256;j++)
    {
        for(k=128;k;k>>=1)
        printf(k&j?"1":"0");
    printf("\n");
    }
}
```
四 (4)
===
```
#include <stdio.h>
#include <stdlib.h>
void print_binary(int x);
int get_hex_H(int);
int get_hex_L(int);

main()  
{
    int x;
    printf("Input x:");
    scanf("%x", &x);
    printf("x's Hex: %X \n", x);
    print_binary(x);
    printf("\n");
    printf("X's H: %2X\n", get_hex_H(x));
    printf("X's L: %2X\n", get_hex_L(x));
}

void print_binary(int x)
{
    int y = 0x80;
    while (y)
    {
        if (x & y)
            printf("1");
        else
            printf("0");  
        y = y >> 1;
    }
}

int get_hex_H(int x)
{
    return (x >> 8) & 0xFF;  
}

int get_hex_L(int x)
{
    return x & 0xFF;      
}
```
五 (5)
===

```


```
===
