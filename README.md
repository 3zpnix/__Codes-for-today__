======


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

======

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

======

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