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

```
九 (9)
===

```

```

===
```
uwu
```
===
