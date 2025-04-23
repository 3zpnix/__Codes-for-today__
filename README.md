<h1>你好</h1> - Please refresh the page every time you want to copy a code, okay bye! If there are any mistakes/wrong placement of code, please do tell me so I will fix it right away, thanks!

```
TO COPY & PASTE >
```
一 (1)
===
```
#include <stdio.h>
#include <stdio.h>
#include <stdlib.h> 
#include <time.h> 

int my_add(int, int);
void my_input();
void my_output();

int x, y, sum = 0;

main()
{
    int z;
    my_input();
    z = my_add(x, y);
    sum = z;  
    my_output();
}

void my_input()
{
    printf("Input x:");
    scanf("%d", &x);
    printf("Input y:");
    scanf("%d", &y);
}

int my_add(int a, int b)
{
    int c;
    c = a + b;
    return c;
}

void my_output()
{
    printf("%d+%d=%d\n", x, y, sum);
}
```
二 (2)
===

```
#include <stdio.h>
#include <stdlib.h> 
#include <time.h> 

void my_add();
void my_input();
void my_output();

int x, y, sum = 0;

main()
{
    int z;
    my_input();
    my_add();
    my_output();
}

void my_input()
{
    printf("Input x:");
    scanf("%d", &x);
    printf("Input y:");
    scanf("%d", &y);
}

void my_add(int a, int b)
{
    sum = x + y;
}

void my_output()
{
    printf("%d+%d=%d\n", x, y, sum);
}
```
三 (3)
===

```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int my_add(int, int);
void my_input();
void my_output(int, int, int);
int x, y;
main()
{
    int sum = 0;
    my_input();
    sum = my_add(x, y);
    my_output(x, y, sum);
}

void my_input()
{
    printf("Input x: ");
    scanf("%d", &x);
    printf("Input y: ");
    scanf("%d", &y);
}

int my_add(int a, int b)
{
    int c;
    c= a + b;
    return c;
}

void my_output(int a, int b, int c)
{
    printf("%d + %d = %d\n", a, b, c);
}
```
四 (4)
===

```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

void my_add();
void my_input();
void my_output();
int A[2], sum=0;
main()
{
    my_input();
    my_add();
    my_output();
}

void my_input()
{
    printf("Input x: ");
    scanf("%d", &A[0]);
    printf("Input y: ");
    scanf("%d", &A[1]);
}

void my_add()
{
    sum= A[0] + A[1];
}

void my_output()
{
    printf("%d + %d = %d\n", A[0], A[1], sum);
}
```
五 (5)
===

```
#include <stdio.h>
#include <stdlib.h>

void my_add();
void my_input();
void my_output();

int x, y, sum = 0;

main()
{
    my_input();
    my_add();
    my_output();
}

void my_input()
{
    printf("Input x: ");
    scanf("%d", &x);
    printf("Input y: ");
    scanf("%d", &y);
}

void my_add()
{
    int i;
    for (i = x; i <= y; i++)
    {
        sum = x+y;
    }
}

void my_output()
{
    printf("sum: %d\n", sum);
}
```
六 (6)
===

```
#include <stdio.h>
#include <stdlib.h>

void my_add();
void my_input();
void my_output();
int x, y, sum = 0;
main()
{
    my_input();
    my_add();
    my_output();
}
void my_input()
{
    printf("Input x: ");
    scanf("%d", &x);
    printf("Input y: ");
    scanf("%d", &y);
}
void my_add()
{
    int i;
    i=x;
    while(i<=y)
    {
        sum = x+y;
        i++;
    }
}
void my_output()
{
    printf("sum: %d\n", sum);
}
```
七 (7)
===

```

```
八 (8)
===

```

```
九 (end)
===

```

```

===
```
uwu
```
===
