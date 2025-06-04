<h1>大家好</h1> - please refresh every time 🤭

```
ATTENTION TO COPY & PASTE >
```
一 (1)
===
```

```
二 (2)
===

```
#include <stdio.h>
#include <stdlib.h>
main()
{
int A[3][5],i,j;
for(i=0;i<3;i++);
{
    for(j=0;j<5;j++);
    {
        printf("A[%d][%d]:",i,j);
        scanf("%d",&A[i][j]);
        }
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
int A[3][5],i,j;
srand((unsigned)time(NULL));
for(i=0;i<3;i++);
{
    for(j=0;j<5;j++);
        printf("A[%d][%d]:%d",i,j);
        printf("\n");
    }
}
```
四 (4)
===
```
#include <stdio.h>
#include <stdlib.h>
main()
{
int A[3][5],i,j;
i=0;
while(i<3)
{
    j=0;
    while(j<5)
    {
        printf("A[%d][%d]:%d",i,j);
        scanf("%d",&A[i][j]);
        j++;
        }
    i++;
    }
}
```
五 (5)
===

```
#include <stdio.h>
#include <stdlib.h>
main()
{
int A[3][5],i,j;
i=0;
while(i<3)
{
    j=0;
    while(j<5)
    {
        printf("A[%d][%d]:%d",i,j,A[i][j]);
        j++;
        }
    printf("\n");
    i++;
    }
}
```
六 (6）
===
```
#include <stdio.h>
#include <stdlib.h>
main()
{
int x=80,y=60,z=50;
printf("Input x:");
scanf("%d",&x);
if(x>=60)
    printf("%d is pass.\n",x);
if(x<60)
    printf("%d is fail.\n",x);
}
```
七 (7）
===
```
#include <stdio.h>
#include <stdlib.h>
main()
{
int x=80,y=60,z=50;
printf("Input x:");
scanf("%d",&x);
if(x>=60)
    printf("%d is pass.\n",x);
else
    printf("%d is fail.\n",x);
}
```
八 (8）
===
```
#include <stdio.h>
#include <stdlib.h>
main()
{
int x=80,y=60,z=50;
printf("Input x:");
scanf("%d",&x);
if(x<60)
    printf("%d: C\n",x);
else if(x<80)
    printf("%d: B\n",x);
else
    printf("%d: A\n",x);
}
```
九 (9）
===
```
#include <stdio.h>
#include <stdlib.h>
main() 
{
    int x;
    printf("Input x: ");
    scanf("%d", &x);
    
    if (x < 60)
        printf("%d: C\n", x);
    else if (x >= 60 && x < 80)
        printf("%d: B\n", x);
    else if (x >= 80)
        printf("%d: A\n", x);

    return 0;
}
```
十 (10）
===
```
#include <stdio.h>
#include <stdlib.h>

main() 
{
    int x;
    printf("Input x: ");
    scanf("%d", &x);

    switch (x) {
        case 0:
        case 1:
        case 2:
        case 3:
        case 4:
        case 5:
        case 6:
        case 7:
        case 8:
        case 9:
        case 10:
        case 11:
        case 12:
        case 13:
        case 14:
        case 15:
        case 16:
        case 17:
        case 18:
        case 19:
        case 20:
        case 21:
        case 22:
        case 23:
        case 24:
        case 25:
        case 26:
        case 27:
        case 28:
        case 29:
        case 30:
        case 31:
        case 32:
        case 33:
        case 34:
        case 35:
        case 36:
        case 37:
        case 38:
        case 39:
        case 40:
        case 41:
        case 42:
        case 43:
        case 44:
        case 45:
        case 46:
        case 47:
        case 48:
        case 49:
        case 50:
        case 51:
        case 52:
        case 53:
        case 54:
        case 55:
        case 56:
        case 57:
        case 58:
        case 59:
            printf("C\n");
            break;

        case 60:
        case 61:
        case 62:
        case 63:
        case 64:
        case 65:
        case 66:
        case 67:
        case 68:
        case 69:
        case 70:
        case 71:
        case 72:
        case 73:
        case 74:
        case 75:
        case 76:
        case 77:
        case 78:
        case 79:
            printf("B\n");
            break;

        default:
            printf("A\n");
            break;
    }

    return 0;
}
```