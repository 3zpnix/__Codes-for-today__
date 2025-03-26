你好 - Please refresh the page every time you want to copy a code, okay bye! If there are any mistakes/wrong placement of code, please do tell me so I will fix it right away, thanks!
```
Quick Copy & Paste >
```
===
1st 
===
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

#define N 4
void my_rand(int A[][N], int, int);
void my_print(char, int A[][N], int, int);
void my_print_1(char, int A[][N], int, int);
void my_copy(int A[][N], int B[][N], int, int);

main() 
{
    int A[3][N], B[3][N], m = 3, n = 4;
    my_rand(A, m, n);
    my_print('A', A, m, n);
    my_print_1('A', A, m, n);
    my_copy(A, B, m, n);
}

void my_rand(int A[][N], int m, int n)
{
    int i = 0, j;
    while (i < m)  
    {
        j = 0;  
        while (j < n)
        {
            A[i][j] = rand() %101;  
            j++;
        }
        i++;
    }
}

void my_print(char c, int A[][N], int m, int n)
{
    int i = 0, j;
    while (i < m)
    {
        j = 0;  
        while (j < n)
        {
            printf("%c[%d][%d]:%d\n", c, i, j, A[i][j]);
            j++;
        }
        i++;
    }
    printf("\n");  
}

void my_print_1(char c, int A[][N], int m, int n)
{
    int i = 0, j;
    puts("A:");
    while (i < m)
    {
        j = 0;
        while (j < n)
        {
            printf("%4d", A[i][j]);
            j++;
        }
        printf("\n");  
        i++;
    }
}

void my_copy(int A[][N], int B[][N], int m, int n)
{
    int i = 0, j;
    while (i < m)
    {
        j = 0;
        while (j < n)
        {
            B[i][j] = A[i][j];
            j++;
        }
        i++;
    }
}
```
===
2nd
===

```
wo bu zhidao, send me pic
```
===
3rd
===

```
Wo bu zhidao, send me pic
```
===
4th 
===

```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

#define N 4
void my_rand(int A[][N], int, int);
void my_print(char, int A[][N], int, int);
void my_print_1(char, int A[][N], int, int);
void my_copy(int A[][N], int B[][N], int, int);

int p;
int k = 0;

main() 
{
    int m = 3, n = 4;
    int A[3][N], B[3][N];

    my_rand(A, m, n);
    my_print('A', A, m, n);
    my_print_1('A', A, m, n);
    my_copy(A, B, m, n);
}

void my_rand(int A[][N], int m, int n)
{
    int i, j;
    for (i = 0; i < m; i++)
    {
        for (j = 0; j < n; j++)
        {
            A[i][j] = rand() % 101;  
        }
    }
}

void my_print(char c, int A[][N], int m, int n)
{
    int i, j;
    for (i = 0; i < m; i++)
    {
        for (j = 0; j < n; j++)
            printf("%c[%d][%d]:%d\n", c, i, j, A[i][j]);
    }
    printf("\n");
}

void my_print_1(char c, int A[][N], int m, int n)
{
    int i = 0, j;
    puts("A:");
    while (i < m)
    {
        j = 0;
        while (j < n)
        {
            printf("%4d", A[i][j]);  
            j++;  
        }
        printf("\n");
        i++;  
    }
}

void my_copy(int A[][N], int B[][N], int m, int n)
{
    int i = 0, j;
    while (i < m)
    {
        j = 0;
        while (j < n)
        {
            B[i][j] = A[i][j];
            j++;
        }
        i++;
    }
}
```
===
5th
===

```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

#define N 4

void my_rand(int A[][N], int, int);
void my_print(int A[][N], int, int);
void find_max_min(int A[][N], int B[2], int, int);

main() 
{   
    int A[3][N], B[2]; 
    srand((unsigned)time(NULL));

    my_rand(A, 3, N);
    my_print(A, 3, N);
    
    find_max_min(A, B, 3, N);  

    printf("max: %d min: %d\n\n", B[0], B[1]);

    return 0;
}

void my_rand(int A[][N], int m, int n)
{
    int i, j;
    for (i = 0; i < m; i++)
        for (j = 0; j < n; j++)
            A[i][j] = rand() % 101;  
}

void my_print(int A[][N], int m, int n)
{
    int i, j;
    for (i = 0; i < m; i++)
    {
        for (j = 0; j < n; j++)
            printf("%4d", A[i][j]);
        printf("\n");
    }
    printf("\n");
}

void find_max_min(int A[][N], int B[2], int m, int n)
{
    int i, j, max = -1, min = 101;
    for (i = 0; i < m; i++)
    {
        for (j = 0; j < n; j++)
        {
            if (A[i][j] > max)
                max = A[i][j];
            if (A[i][j] < min)  
                min = A[i][j];    
        }
    }
    B[0] = max;
    B[1] = min;
}
```