<h1>大家好</h1> - you can double check for reference 🤭

```
COPY & PASTE BUTTON GUYS >
```
一 (1)
===
```
#include <stdio.h>
#include <stdlib.h>
main()
{
	int A[10],i,max=-1,min=99999;
	for(i=0;i<10;i++)
	{
		printf("Input A[%d]:",i);
		scanf("%d",&A[i]);
	}
	i=0;
	while (i < 10) 
	{
    printf("A[%d]=%d\n", i, A[i]);
    i++;
	}
	for(i=0;i<10;i++)
	{
		if(A[i]>max)
		max=A[i]; 
	} 
	for(i=0;i<10;i++)
	{
		if(A[i]<min)
		min=A[i];
	}
	printf("max=%d min=%d\n", max,min);
} 
```
二 (2)
===

```
#include <stdio.h>
#include <stdlib.h>

int A[10],i,max=-1,min=99999;
void my_init()
{
	for(i=0;i<10;i++)
	{
		printf("Input A[%d]:",i);
		scanf("%d",&A[i]);
	}
}
void my_print()
{
	i=0;
	while (i < 10) 
	{
    printf("A[%d]=%d\n", i, A[i]);
    i++;
	}
}

int my_max()
{
	int i;
	for(i=0;i<10;i++)
	{
		if(A[i]>max)
		max=A[i]; 
	} 
	return max;
} 

int my_min()
{
	for(i=0;i<10;i++)
	{
		if(A[i]<min)
		min=A[i];
	}
	printf("max=%d min=%d\n", max,min);
	return min;
}

void my_init();
void my_print();
int my_max();
int my_min();
int A[10],max,min,i;

main()
{ 
	my_init();
	my_print();
	printf("max=%d min=%d\n",my_max(),my_min());
} 
```
