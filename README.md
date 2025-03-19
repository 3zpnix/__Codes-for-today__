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
void stars();
main()
{
stars();
}
void stars()
{
int i=0;
while(i<10)
{
printf("*");
i++;
}
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
6th 
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
    printf("\n");
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
    for(i=0;i<n;i++)
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


```
===
9th 
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
10th
===
```

```
===
11th 
===
```

```
