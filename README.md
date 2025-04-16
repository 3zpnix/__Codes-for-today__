<h1>你好</h1> - Please refresh the page every time you want to copy a code, okay bye! If there are any mistakes/wrong placement of code, please do tell me so I will fix it right away, thanks!

```
TO COPY & PASTE >
```
一 (1)
===
```
#include <stdio.h>
#include <stdlib.h> 
void my_input();
int a,b,c;
main()
{
	int x;
	my_input();
	x=my_output(a,b,c);
	printf("result:%d\n",x);
}
void my_input()
{
	printf("Input a:");
	scanf("%d",&a);
	printf("Input b:");
	scanf("%d",&b);
	printf("Input c:");
	scanf("%d",&c);
}
int my_output(int x, int y, int z)
{
	return(x*y*z);
}
```
二 (2)
===

```
#include <stdio.h>
#include <stdlib.h> 
#include <time.h> 
void my_input(int A[][5]);
void my_output(int A[][5]);
int my_max(int A[][5], int, int);
int A[3][5];
main()
{
	int x;
	my_input(A);
	my_output(A);
	printf("max:%d\n",my_max(A,3,5));
}
void my_input(int A[][5])
{
	int m=3,n=5,i,j;
	for(i=0;i<3;i++)
		for(j=0;j<5;j++)
			A[i][j]=rand()%101;
}
void my_output(int A[][5])
{
	int m=3,n=5,i,j;
	for(i=0;i<3;i++)
		for(j=0;j<5;j++)
			printf("%5d",A[i][j]);
		printf("\n");
}
int my_max(int A[][5],int m, int n)
{
	int i,j,max=-1;
	for(i=0;i<3;i++)
		for(j=0;j<5;j++)
			if(A[i][j]>max)
				max=A[i][j];
		return max;
}
```
三 (3)
===

```

```
四 (4)
===

```

```
五 (5)
===

```

```
六 (6)
===

```

```
七 (7)
===

```

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
