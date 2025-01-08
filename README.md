你好, Once you're done copying it, remove this tab from your browser. Happy coding! uwu

```
Just press the copy button >
```

1st ====== (1225_1.c)


```
NOT YET
```

2nd ====== (1225_2.c)

```
#include <stdio.h>
#include <stdlib.h>
#include <stdio.h> 
main()
{
	srand((unsigned)time(NULL));
	int A[10],i,B[10]={0},k=0;
	
	for(i=0;i<10;i++)
		A[i]=15;
	for(i=0;i<10;i++)
		printf(" %d ",A[i]);
		printf("\n");
	for(i=0;i<10;i++)
	{
		if(A[i]=60)
			printf("A[%d]=%d\n Pass\n",i,A[i]);
		else
			printf("A[%d]=%d\n \tFail\n",i,A[i]);
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
