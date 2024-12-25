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
   int A[10],i,num_0=0,num_1=0,num_2=0;
   int num_3=0,num_4=0;
   srand((unsigned)time(NULL));
   for(i=0; i<10; i++)
       A[i]=rand()%5;
   for(i=0; i<10; i++)
       printf("%3d", A[i]);
   printf("\n");
   for(i=0;i<10;i++)
{
   if(A[i]==0)num_0++;
   else if (A[i]==1)num_1++;
        else if (A[i]==2)num_2++;
            else if (A[i]==3)num_3++;
                else num_4++;   
}
    printf("num_0:%d\n", num_0);
    printf("num_1:%d\n", num_1);
    printf("num_2:%d\n", num_2);
    printf("num_3:%d\n", num_3);
    printf("num_4:%d\n", num_4);
}
```

2nd ====== (1225_2.c)

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

3rd ====== (1225_3.c)

```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
main()
{
   int A[10], i;
   int B[5]={0};
   srand((unsigned)time(NULL));
   for (i=0; i<10; i++)
       A[i] = rand()%5;
   for (i=0; i<10; i++)
       printf("%3d", A[i]);
   printf("\n");
   for(i=0; i<10; i++)
{
    switch(A[i])
    {
    	case 0:
    		B[0]++;
			break; 
		case 1:
    		B[1]++;
			break; 
		case 2:
    		B[2]++;
			break; 
		case 3:
    		B[3]++;
			break; 
		case 4:
    		B[4]++;
			break; 
		default:
			printf("Error\n");
		}
	}
}
```

4th ====== (1225_4.c)
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
main()
{
   int A[10],i,B[5]={0};
   srand((unsigned)time(NULL));
   for(i=0; i<10; i++)
       A[i] = rand()%5;
   for(i=0; i<10; i++)
       printf("%3d",A[i]);
       printf("\n");
   for(i=0; i<10; i++)
       B[A][i]]++;
   for(i=0;i<10;i++)
       printf("B[%d]=%d\n",i,B[i]);
}
```
