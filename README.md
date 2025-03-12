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

int my_add(int,int);
main() 
    {
    printf("%d",my_add(2,3));
    }
    int my_add(int x, int y)
    {
        return(x+y);
    }
```
===
2nd 
===
```
#include <stdio.h>
#include <stdlib.h>

int my_add(int x, int y)
    {
    return(x+y);
    printf("%d",my_add(2,3));
    }
    main()
    {
    printf("%d",my_add(2,3));
    }
```
===
3rd
===

```
#include <stdio.h>
#include <stdlib.h>

void stars();
main()
{
stars();
}
void stars()
{
int i=0;
while(i<10)
{
printf("*");
i++;
}
}
```
===
4th 
===

```
#include <stdio.h>
#include <stdlib.h>

void stars(int);
main()
{
stars(10);
}
void stars(int n)
{
int i=0;
while(i<n)
{
printf("*");
i++;
}
}
```
===
5th
===

```
#include <stdio.h>
#include <stdio.h>
#include <stdlib.h>

void my_stars(int);
main()
{
int n;
printf("Input n:");
scanf("%d",&n);
my_stars(n);
}
void my_stars(int k)
{
int i=0;
while(i<k)
{
printf("*");
i++;
}
}
```
===
6th 
===
```
#include <stdio.h>
#include <stdlib.h>

void my_stars(char, int);  

main() {
    char c;
    int n;

    printf("Input a char:");
    scanf(" %c", &c);  
    printf("Input a number:");
    scanf("%d", &n);
    my_stars(c, n);

    printf("\nInput a char:");
    scanf(" %c", &c);  
    printf("Input a number:");
    scanf("%d", &n);
    my_stars(c, n);

    return 0;
}

void my_stars(char x, int n) {
    int i = 0;
    while (i < n) {
        printf("%c", x);
        i++;
    }
}
```
===
7th (UPDATED)
===

```
#include <stdio.h>
#include <stdlib.h>

void my_stars (char,int);
main()
{
my_stars('*', 5);
my_stars ('$', 10);
my_stars('#', 7);
}
void my_stars (char c, int n)
{
int i=0;
while(i<n)
{
printf("%c",c);
i++;
}
}
```
===
8th 
===

```
#include <stdio.h>
#include <stdlib.h>

void my_stars(char, int);  

main() 
{
    char c;
    int i, n;

    printf("Input integer: ");
    scanf("%d", &n);
    for(i = 0; i < n; i++) {
    }

    printf("\nInput an integer: ");
    scanf("%d", &n);  

    printf("Input a char: ");
    scanf(" %c", &c);  
    
    my_stars(c, n);

    return 0;
}    

void my_stars(char c, int n) {
    int i;
    for(i = 0; i < n; i++) {
        printf("%c", c);
    }
}
```
===
