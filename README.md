你好, Once you're done copying it, remove this tab from your browser. Happy coding! uwu

```
Just press the copy button >
```

1st ====== (1225_1.c)


```
#include <stdio.h>
#include <stdlib.h>
#include <time.h> 
main()
{
	srand((unsigned)time(NULL));
	int A[10],i,B[10]={0},k=0;
	
	for(i=0;i<10;i++)
		A[i]=10+rand()%11;
	for(i=0;i<10;i++)
		printf(" %d ",A[i]);
		printf("\n");
	for(i=0;i<10;i++)
	{
		if((A[i]%2)==0)
		{
			B[k]=A[i];
			k++;
		}
	}
	for(i=0;i<k;i++)
		printf(" %d ",B[i]);
}
```

2nd ====== (1225_2.c)

```
#include <stdio.h>
#include <stdlib.h>
#include <time.h> 
main()
{
	srand((unsigned)time(NULL));
	int A[10],i,B[10]={0},k=0;
	
	for(i=0;i<10;i++)
		A[i]=rand()%101; 
	for(i=0;i<10;i++)
		printf(" %d ",A[i]);
		printf("\n");
	for(i=0;i<10;i++)
	{
		if(A[i]>=60)
			printf("A[%d]=%d Pass\n",i,A[i]);
		else
			printf("A[%d]=%d      Fail\n",i,A[i]);
	}
}
```

3rd ====== (1225_3.c)

```
#include <stdio.h>
#include <stdlib.h>
#include <stdio.h> 
main()
{
	srand((unsigned)time(NULL));
	int A[10],i,B[10]={0},even=0,odd=0;
	
	for(i=0;i<10;i++)
		A[i]=15+rand()%96;
	for(i=0;i<10;i++)
		printf(" %d ",A[i]);
		printf("\n");
	for(i=0;i<10;i++)
	{
		if((A[i]%2)==0)
			even++;
		else
			odd;
	}
	printf("Even:%d odd:%d\n",even,odd);
}
```
