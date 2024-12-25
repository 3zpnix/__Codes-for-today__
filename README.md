你好, Once you're done copying it, remove this tab from your browser. Happy coding! uwu

```
Just press the copy button >
```

1st ====== (1218_1.c)


```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
main()
{
   int A[10], i;
   int num_3=0, num_4=0,B[5]={0};
   srand((unsigned)time(NULL));
   for (i=0; i<10; i++)
       A[i] = rand()%5;
   for (i=0; i<10; i++)
       printf("%3d", A[i]);
   printf("\n");
   for(i=0; i<10; i++)
{
    if (A[i]==0) B[0]++;
    else if (A[i]==1) B[1] ++;
        else if ( A[i]==2) B[2]++;
            else if (A[i]==3) B[3]++;
                else B[4]++;
}
for (i=0; i<5; i++)
printf("B[%d] = %d\n",i,B[i]);
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
