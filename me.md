0219

1st
```
#include <stdio.h>
#include <stdlib.h>

main() {
    int i;
    for(i=0;i<5;i++)
        printf("i=%d\n",i);
    while(i<5)
    {
    printf("i=%d\n",i);
    i++;
    }
}
```

3rd
```
#include <stdio.h>
#include <stdlib.h>

main() {
    int i=0;
    while(1)
    {
    printf("i=%d\n",i);
    i=i*i;
    if(i<15)
        i=i+2;
    }
}
```

4th
```
#include <stdio.h>
#include <stdlib.h>

main() {
    int i;
    do{
        printf("Input: ");
        scanf("%d",&i);
        printf("i=%d\n",i);
        i=i++;
    } while (i<5);
    printf("***\n");
}
```

5th
```
#include <stdio.h>
#include <stdlib.h>

main() {
    int i=0,A[5]={0},x;
    do{
        printf("Input A[d]= ",i);
        scanf("%d",&x);
        if(A[i]<=100);
        {
            A[i]=x;
            i++;
        }
    } while(i==5);
    printf("***\n");
}
```
