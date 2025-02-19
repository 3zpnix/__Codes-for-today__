你好, Please refresh the page every time you want to copy a code, okay bye!

```
Just press the copy button >
```

1st ====== 
```
#include <stdio.h>
#include <stdlib.h>

main(){
int i=0;
for(i=0;i<5;i++)
    printf("i=%d\n",i);
    while(i<5)
    {
    printf("i=%d\n",i);
    i++;
    }
}
```

2nd ======
```
#include <stdio.h>
#include <stdlib.h>

main(){
int i=0;
for(i=0;i<5;i++);
    printf("i=%d\n",i);
    while(i<5)
    {
    printf("*");
    }
}
```
3rd ======

```
#include <stdio.h>
#include <stdlib.h>

main(){
int i=0;
while(1);
{
	printf("i=%d",i);
	i=i*i;
	if(i<15)
	i=i+2;
	}
}
```

4th ====== 

```
#include <stdio.h>
#include <stdlib.h>

main(){
int i;
do{
	printf("Input:");
	scanf("%d",&i);
	printf("i=%d\n",i);
	i++;
} while(i<5);
printf("***\n");
}
```

5th ====== 

```
#include <stdio.h>
#include <stdlib.h>

main(){
int i=0,A[5]={0},x;
do{
	printf("Input A[%d]= ",i);
	scanf("%d",&x);
	if(A[i]<=100)
	{
		A[i]=x; 
		i++;
	}
} while(i=5);
printf("**\n");
}
```

6th ====== 

```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

main(){
int i,A[5],x;
    printf("Input: ");
    scanf("%d",&x);
    for(i=0;i<5;i++);
    {
    printf("Input: ");
    scanf("%d",&x);
    if(x<=100)
    {
    	A[i]=x;
    	i++;
		}
	}
}
```

7th ====== 

```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

main(){
int i,A[5],x;
while(1)
{
    printf("Input: ");
    scanf("%d",&x);
    if(x<=100)
    {
    	A[i]=x;
    	i++;
    }
	if(i==5)
	break;
	}
}
```
