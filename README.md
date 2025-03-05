你好, Please refresh the page every time you want to copy a code, okay bye!

```
Just press the copy button >
```
===
1st 
===
```
#include <stdio.h>
#include <stdlib.h>

main() {
    char A[5][10]={"APPLE","JOHN"};
    char B[20]={"PETER"};
    int i=0;
    while(i<2)
    {
    printf("A[%d]: %s\n",i,A[i]);
    i++;
    }
    puts(B);
}
```
===
2nd 
===
```
#include <stdio.h>
#include <stdlib.h>

main() {
    char A[]="ABCBBAACB";
    int i=0;
    int count_A=0,count_B=0,count_C=0;
    while(A[i]!= '\0')
    {
    if(A[i]=='A')
        count_A++;
    else if (A[i]=='B')
        count_B++;
    else
        count_C++;
    i++;
    }
    printf("count_A: %d\ncount_B: %d\ncount_C: %d\n",count_A,count_B,count_C);
}
```
===
3rd
===

```
#include <stdio.h>
#include <stdlib.h>

main() {
    char A[]="ABCBBAACB";
    int i=0, Length=0;
    for(;;)
    {
    if(A[i]!='\0')
        {
        Length++;
        i++;
        }
        else
            break;
    }
    printf("Length:%d\n",Length);
}
```
===
4th 
===

```
#include <stdio.h>
#include <stdlib.h>

main() {
    char A[]="ABCBBAACB";
    int i=0, Length=0;
    for(;;)
    {
    if(A[Length]!='\0')
        Length++;
        else
            break;
	}
	printf("Length:%d\n",Length);
}
```
===
5th
===

```
#include <stdio.h>
#include <stdlib.h>

main() {
    char A[]="ABCBBAACB";
    int i=0, Length=0;
    int count_A=0,count_B=0,count_C=0;
    for(i=0;i<Length;i++)
    {
    if(A[i]=='A')
        count_A++;
    else if (A[i]=='B')
        count_B++;
    else
        count_C++;
    }
    printf("count_A: %d\ncount_B: %d\ncount_C: %d\n",count_A,count_B,count_C);
}
```
===
6th 
===
```
#include <stdio.h>
#include <stdlib.h>

main() {
    char A[20];
    int i=0, B[5]={0};
    printf("Input string:");
    scanf("%s",A);
    while(A[i]!='\0')
    {
        if(A[i]=='A')
            B[0]++;
        else if (A[i]=='B')
            B[1]++;
        else
            B[2]++;
        i++;
    }
}
```
===
7th
===

```
#include <stdio.h>
#include <stdlib.h>

main() {
    char A[20],B[5];
    int i=0;
    {
    printf("%c:%d\n",'A'+i,A[i]);
    i++;
	}
    printf("A:%d B:%d C:%d\n",B[0],B[1],B[2]);
}
```
===
8th 
===

```
#include <stdio.h>
#include <stdlib.h>

main() {
    char A[5][20];
    int i=0;
    while(i<5)
    {
        printf("Input A[%d]:",i);
        scanf("%s",A[i]);
        i++;
    }
    i=0;
    while(i<5)
    {
    puts(A[i]);
    i++;
    }
}
```
===











DONT COPY BELOW, THANK YOU
extra:
```
#include <stdio.h>
#include <stdlib.h>

main() {
    char A[20];
    int i = 0, B[3] = {0};
    printf("Input string: ");
    scanf("%s", A);

    while (A[i] != '\0') {
        if (A[i] == 'A') {
            B[0]++;
        } else if (A[i] == 'B') {
            B[1]++;
        } else {
            B[2]++;
        }
        i++;
    }
    i=0;
    while(i<3)
    {
    printf("A:%d B:%d C:%d\n", B[0], B[1], B[2]);
    i++;
    }
}
```
extra
```
#include <stdio.h>
#include <stdlib.h>

main() {
    char A[20];
    int i = 0, B[3] = {0};
    printf("Input string: ");
    scanf("%s", A);

    while (A[i] != '\0') {
        if (A[i] == 'A') {
            B[0]++;
        } else if (A[i] == 'B') {
            B[1]++;
        } else {
            B[2]++;
        }
        i++;
    }
    i=0;
    while(i<3)
    {
    printf("%c:%d\n",'A'+i,A[i]);
    i++;
    }
    printf("A:%d B:%d C:%d\n", B[0], B[1], B[2]);
}
```
