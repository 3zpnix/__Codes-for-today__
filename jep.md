<h1>你好</h1> - Please refresh the page every time you want to copy a code, okay bye! If there are any mistakes/wrong placement of code, please do tell me so I will fix it right away, thanks!

```
TO COPY & PASTE >
```
一 (1)
===
```
// C program to show function
// call and definition
#include <stdio.h>

// Function that takes two parameters 
// a and b as inputs and returns 
// their sum
int sum(int a, int b) 
{ 
  return a + b; 
}

// Driver code
int main()
{
  // Calling sum function and 
  // storing its value in add variable
  int add = sum(10, 30);
  
  printf("Sum is: %d", add);
  return 0;
}
```
二 (2)
===

```
// C program to implement
// the above approach
#include <math.h>
#include <stdio.h>

// Driver code
int main()
{
  double Number;
  Number = 49;

  // Computing the square root with 
  // the help of predefined C 
  // library function
  double squareRoot = sqrt(Number);
  
  printf("The Square root of %.2lf = %.2lf", 
          Number, squareRoot);
  return 0;
}
```
三 (3)
===

```
// C program to show 
// user-defined functions
#include <stdio.h>

int sum(int a, int b) 
{ 
  return a + b; 
}

// Driver code
int main()
{
  int a = 30, b = 40;
 
  // function call
  int res = sum(a, b);

  printf("Sum is: %d", res);
  return 0;
}
```
四 (4)
===

```
// C program to show use 
// of call by value
#include <stdio.h>

void swap(int var1, int var2)
{
  int temp = var1;
  var1 = var2;
  var2 = temp;
}

// Driver code
int main()
{
  int var1 = 3, var2 = 2;
  printf("Before swap Value of var1 and var2 is: %d, %d\n",
          var1, var2);
  swap(var1, var2);
  printf("After swap Value of var1 and var2 is: %d, %d",
          var1, var2);
  return 0;
}
```
五 (5)
===

```
// C program to show use of 
// call by Reference
#include <stdio.h>

void swap(int *var1, int *var2)
{
  int temp = *var1;
  *var1 = *var2;
  *var2 = temp;
}

// Driver code
int main()
{
  int var1 = 3, var2 = 2;
  printf("Before swap Value of var1 and var2 is: %d, %d\n",
          var1, var2);
  swap(&var1, &var2);
  printf("After swap Value of var1 and var2 is: %d, %d",
          var1, var2);
  return 0;
}
```
六 (6)
===

```
#include <stdio.h>

void rec(int n)
{
    if(n == 6) return; 
    printf("Recursion Level %d\n", n);
    rec(n+1);
}

int main()
{
    rec(1);
    return 0;
}
```
七 (7)
===

```
#include <stdio.h>

void rec(int n)
{
    if(n == 0) return; 
    printf("Recursion Level %d\n", n);
    rec(n-1);
}

int main()
{
    rec(6);
    return 0;
}
```
八 (8)
===

```
#include <stdio.h>
int power(int n, int m)
{
    if(m == 0) return 1; 
    
    return n * power(n, m - 1);
}

int main()
{
    int n = 2, m = 3;
    int result = power(n,m);
    printf("%d raised to the power of %d is: %d\n", n, m, result);
    return 0;
}
```
九 (9)
===

```
// C program to find factorial of given number
#include <stdio.h>
 
// ----- Recursion -----
// method to find factorial of given number
int factorialUsingRecursion(int n)
{
    if (n == 0)
        return 1;
 
    // recursion call
    return n * factorialUsingRecursion(n - 1);
}
 
// ----- Iteration -----
// Method to find the factorial of a given number
int factorialUsingIteration(int n)
{
    int res = 1, i;
 
    // using iteration
    for (i = 2; i <= n; i++)
        res *= i;
 
    return res;
}
 
// Driver method
int main()
{
    int num = 5;
    printf("Factorial of %d using Recursion is: %d\n", num,
           factorialUsingRecursion(5));
 
    printf("Factorial of %d using Iteration is: %d", num,
           factorialUsingIteration(5));
 
    return 0;
}
 
// This code is contributed by mits
```

===
```
tulog tayo guys
```
===
