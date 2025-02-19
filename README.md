你好, Please refresh the page every time you want to copy a code, okay bye!

```
Just press the copy button >
```

1st ====== (0219_1.c)


```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int i,A[5],x;
while(1)
{
    printf("Input:");
    scanf("%d",&x);
    if(x<=100)
    {
    A[i]=x;
    i++
    }
if(i==5)
break;
}




#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int i=0,A[4],B[4]={0};
while(k<5)
{
    x=rand()%5%
    if(!B[x])
    {
    A[0]=x;
    i++
    B[x]=1;
    k++
    }
}

#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int i=0;
for(i=0,i<5,i++);
    printf("i=%d\n",i);
    while(i<5)
    {
    printf("i=%d\n",i);
    i++
    }
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
#include <time.h> 
main()
{
	srand((unsigned)time(NULL));
	int A[10],i,B[10]={0},even=0,odd=0;
	
	for(i=0;i<10;i++)
		A[i]=15+rand()%90;
	for(i=0;i<10;i++)
		printf(" %d ",A[i]);
		printf("\n");
	for(i=0;i<10;i++)
	{
		if((A[i]%2)==0)
			even++;
		else
			odd++;
	}
	printf("Even:%d odd:%d\n",even,odd);
}
```
