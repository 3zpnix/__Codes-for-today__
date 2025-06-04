<h1>大家好</h1> - please refresh every time 🤭

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
二 (2)
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
三 (3) 
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
        printf("A[%d][%d]:%d",i,j,A[i][j]);
        j++;
        }
    printf("\n");
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
int x=80,y=60,z=50;
printf("Input x:");
scanf("%d",&x);
if(x>=60)
    printf("%d is pass.\n",x);
if(x<60)
    printf("%d is fail.\n",x);
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
else
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
if(x<60)
    printf("%d: C\n",x);
else if(x<80)
    printf("%d: B\n",x);
else
    printf("%d: A\n",x);
}
```
八 (8）
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
九 (9）
===
```

```
十 (10）
===
```

```