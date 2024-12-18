你好, Please delete this tab once you're done, thank you! from MJK <3

```
Just press the copy button ->
```

1st ====== (1218_1.c)


```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
main()
{
   int i=0,A[10];
   for(i=0;i<5;i++)
   {
        printf("Input A[%d]: ",i);
        scanf("%d",&A[i]);
        }
        for(i=0;i<10;i++)
        printf("A[%d]=%d\n",i,A[i]);
}
```

2nd ====== (1218_2.c)

```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
main()
{
   int i=0,A[10],B[10];
   for(i=0;i<10;i++)
       A[i]=rand()%10;
   for(i=0;i<10;i++)
       printf("A[%d]=%d\n",i,A[i]);
   for(i=0;i<10;i++)
       B[i]=A[i];    
   for(i=0;i<10;i++)
       printf("B[%d]=%d\n",i,B[i]); 
}
```

3rd ====== (1218_3.c)

```
#include <stdio.h> 
#include <stdlib.h> 
#include <time.h> 
main()
{
    srand((unsigned)time(NULL));
    int i=0,A[10],B[10],j=0;

    for(i=0;i<10;i++)
        A[i]=rand()%101;
        
    for(i=0;i<10;i++)
        printf("A[%d]=%d\n",i,A[i]);
        
    for(i=0;i<10;i++)
    {    if(A[i]>=60)
        {
            B[j]=A[i];
            j++;
        }    
    }
    printf("\nThe number of pass:%d\n",j);
    printf("-------------------------\n");
    for(i=0;i<j;i++)
        printf("B[%d]=%d\n",i,B[i]);
}
```

======
