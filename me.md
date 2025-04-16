你好 - Please refresh the page every time you want to copy a code, okay bye! If there are any mistakes/wrong placement of code, please do tell me so I will fix it right away, thanks!
```
Quick Copy & Paste >
```
===
1st 
===
```
#include <stdio.h>
#include <stdlib.h>
void my_print(int);
main()
{
my_print(5);
}
void my_print(int n)
{
int i;
for (i=0;i<n;i++)
    printf("%d\n",i);
}
```
===
2nd 
===
```
#include <stdio.h>
#include <stdlib.h>
void my_print(int n)
{
int i;
for (i=0;i<n;i++)
    printf("%d\n",i);
}
main()
{
my_print(5);
}
```
===
3rd
===

```
#include <stdio.h>
#include <stdlib.h>
int my_sum(int, int);
main()
{
int x,i=2,j=5;
x=my_sum(i,j);
printf("x:%d\n",x);
}
int my_sum(int a, int b)
{
int k;
k=a+b;
return k;
}
```
===
4th 
===

```
#include <stdio.h>
#include <stdlib.h>
void print_stars();
main()
{
    print_stars();
    printf("------\n");
    print_stars();
}
void print_stars()
{
int i;
for (i=0;i<10;i++)
    printf("*");
printf("\n");
}
```
===
5th
===

```
#include <stdio.h>
#include <stdlib.h>
void my_rand(int A[],int);
void my_print(int A[],int);
main()
{
    int A[10],n;
    printf("Input a digit: ");
    scanf("%d",&n);
    my_rand(A,n);
    my_print(A,n);
    printf("\n");
}
void my_rand(int A[],int n)
{
    int i;
    for(i=0;i<n;i++)
        A[i]=rand()%101;
}
void my_print(int A[],int n)
{
    int i;
    for(i=0;i<n;i++)
    printf("A[%d]:%d\n",i,A[i]);
}
```
===
6th (UPDATED)
===
```
#include <stdio.h>
#include <stdlib.h>
void my_rand_i(int A[],int,int);
void my_print_i(int A[],int,int);
main()
{
    int B[10],m,n;
    printf("Input m: ");
    scanf("%d",&m);
    printf("Input n: ");
    scanf("%d",&n);
    my_rand_i(B,m,n);
    my_print_i(B,0,10);
}
void my_rand_i(int A[],int m,int n)
{
    int i;
    for(i=0;i<n;i++)
        A[i]=rand()%101;
}
void my_print_i(int A[],int m,int n)
{
    int i;
    for(i=m;i<n;i++)
    printf("B[%d]:%d\n",i,A[i]);
}
```
===
7th 
===

```
#include <stdio.h>
#include <stdlib.h>
void my_rand(int A[],int);
void my_print(int A[],int,char);
void my_copy(int A[],int B[], int);
main()
{
    int A[5],B[5];
    my_rand(A,5);
    my_print(A,5,'A');
    my_copy(A,B,5);
    my_print(B,5,'B');
}
void my_rand(int A[],int n)
{
    int i;
    for(i=0;i<n;i++)
        A[i]=rand()%101;
}
void my_print(int A[],int n,char c)
{
    int i;
    for(i=0;i<n;i++)
    printf("%c[%d]:%d\n",c,i,A[i]);
}
void my_copy(int A[], int B[], int n)
{
    int i;
    for(i=0;i<n;i++)
    B[i]=A[i];
}
```
===
8th 
===
```
#include <stdio.h>
#include <stdlib.h>
int my_sum(int,int);
main()
{
    int i,m=1,n=5,sum;
    sum=my_sum(m,n);
    printf("sum=%d\n",sum);
}
int my_sum(int a,int b)
{
    int k=0,i;
    for(i=a;i<b;i++)
        k=k+i;
    return k;
}
```
===
9th
===
```
#include <stdio.h>
#include <stdlib.h>
void my_print(char,int,int);
main()
{
    my_print('#',2,10);
}
void my_print(char c,int m,int n)
{
    int i;
    for(i=0;i<n;i++)
        printf("%c",c);
}
```
===
10th 
===
```
#include <stdio.h>
#include <stdlib.h>
void my_print(char,int,int);
main()
{
    my_print('@',2,10);
}
void my_print(char c,int m,int n)
{
    int i;
    for(i=m;i<n;i++)
        printf("%c",c);
}
```

<h1>你好</h1> - Please refresh the page every time you want to copy a code, okay bye! If there are any mistakes/wrong placement of code, please do tell me so I will fix it right away, thanks!

```
TO COPY & PASTE >
```
一 (1)
===
```
#include <stdio.h>
#include <stdlib.h>

void my_func_1(); 

main() 
{
    my_func_1();
}
void my_func_1()
{
    int i;
    for(i = 0; i < 10; i++)
        printf("#");
    printf("\n");    
}
```
二 (2)
===

```
#include <stdio.h>
#include <stdlib.h>

void my_func_2(char, int); 

main() 
{
    char c;
    int n;
    printf("Input char:");
    scanf("%c",&c);
    printf("Input n:");
    scanf("%d",&n);
    my_func_2(c,n);
}
void my_func_2(char c, int n)
{
    int i;
    for(i = 0; i < n; i++)
        printf("%c",c);
    printf("\n");    
}
```
三 (3)
===

```
#include <stdio.h>
#include <stdlib.h>
int my_func_3(int, int);

main() 
{
    int x, y, sum;
    printf("Input x:");
    scanf("%d", &x);
    printf("Input y:");
    scanf("%d", &y);
    sum = my_func_3(x, y);
    printf("sum:%d\n", sum);
}

int my_func_3(int a, int b)
{
    int c;
    c = a + b;
    return c;
}
```
四 (4)
===

```
#include <stdio.h>
#include <stdlib.h>
main() 
{
    int x, y, sum;
    printf("Input x:");
    scanf("%d", &x);
    printf("Input y:");
    scanf("%d", &y);
    sum = x+y;
    printf("sum:%d\n", sum);
}
```
五 (5)
===

```
#include <stdio.h>
#include <stdlib.h>
main() 
{
    int A[50],i,n;
    printf("Input n:");
    scanf("%d", &n);
    for(i=0;i<n;i++);
    {
    printf("Input A[%d]:");
    scanf("%d", &A[i]);
    }
    for(i=0;i<n;i++);
        printf("A[%d]:%d\n", i,A[i]);
}
```
六 (6)
===

```
#include <stdio.h>
#include <stdlib.h>
void my_input ( int A[], int);
void my_output( int A[], int);
main() 
{
    int A[50],i,n;
    printf("Input n:");
    scanf("%d", &n);
    my_input(A,n);
    my_output(A,n);
    }
    void my_input(int A[], int n)
    {
    int i;
    for(i=0;i<n;i++);
    {
    printf("Input A[%d]:",i);
    scanf("%d", &A[i]);
        }
    }
    void my_output(int A[], int n)
    {
    int i;
    for(i=0;i<n;i++);
        printf("A[%d]:%d\n", i,A[i]);
}
```
七 (7)
===

```
#include <stdio.h>
#include <stdlib.h>
void my_input ( int A[], int);
void my_output( int A[], int);
main() 
{
    int A[50],B[50],C[50],i,n,n1,n2;
    printf("Input n:");
    scanf("%d", &n);
    printf("Input n1:");
    scanf("%d", &n1);
    printf("Input n2:");
    scanf("%d", &n2);
    my_input(A,n);
    my_output(A,n);
    my_input(B,n1);
    my_output(B,n1);
    my_input(C,n2);
    my_output(C,n2);
    }
    void my_input(int A[], int n)
    {
    int i;
    for(i=0;i<n;i++);
    {
    printf("Input A[%d]:",i);
    scanf("%d", &A[i]);
        }
    }
    void my_output(int A[], int n)
    {
    int i;
    for(i=0;i<n;i++);
        printf("A[%d]:%d\n", i,A[i]);
}
```
八 (8)
===

```
#include <stdio.h>
#include <stdlib.h>
void my_input ( int A[], int);
void my_output( int A[], int);
void my_input_output( int A[], int);
main() 
{
    int A[50],B[50],C[50],n1,n2,n3;
    printf("Input n1:");
    scanf("%d", &n1);
    printf("Input n2:");
    scanf("%d", &n2);
    printf("Input n3:");
    scanf("%d", &n3);
    my_input_output(A,n1);
    my_input_output(B,n2);
    my_input_output(C,n3);
    }
    void my_input(int A[], int n)
    {
    int i;
    for(i=0;i<n;i++);
    {
    printf("Input A[%d]:",i);
    scanf("%d", &A[i]);
        }
    }
    void my_output(int A[], int n)
    {
    int i;
    for(i=0;i<n;i++);
        printf("A[%d]:%d\n", i,A[i]);
    }
    void my_input_output(int A[],int n)
    {
        my_input(A,n);
        my_output(A,n);    
}
```
九 (9)
===

```
#include <stdio.h>
#include <stdlib.h>

void my_input(char c, int A[], int n);
void my_output(char c, int A[], int n);
void my_input_output(char c, int A[], int n);

main() 
{
    int A[50], B[50], C[50], n1, n2, n3;
    printf("Input n1: ");
    scanf("%d", &n1);
    printf("Input n2: ");
    scanf("%d", &n2);
    printf("Input n3: ");
    scanf("%d", &n3);

    my_input_output('A', A, n1);
    my_input_output('B', B, n2);
    my_input_output('C', C, n3);
}

void my_input(char c, int A[], int n)
{
    int i;
    for (i = 0; i < n; i++)
    {
        printf("Input %c[%d]: ", c, i);
        scanf("%d", &A[i]);
    }
}

void my_output(char c, int A[], int n)
{
    int i;
    for (i = 0; i < n; i++)
    {
        printf("%c[%d]: %d\n", c, i, A[i]);
    }
}

void my_input_output(char c, int A[], int n)
{
    my_input(c, A, n);
    my_output(c, A, n);    
}
```

===
```
9 lang po, tamad kasi ako sa number 10 hehehe
```
===
