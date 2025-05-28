<h1>大家好</h1> - sarap daw ng tae sabi ni geoven 🤭

```
ATTENTION TO COPY & PASTE >
```
一 (1)
===
```
#include <stdio.h>
#include <stdlib.h>
main()
{
    int i;
    for(i=0;i<=10;i++)
    {
        if(i==5)
            continue;
        else
            printf("%d",i);
    }
}
```
二 (2)
===

```
#include <stdio.h>
#include <stdlib.h>
main()
{
    int i;
    i=0;
    while(i<=10)
    {
        if(i==5)
            continue;
        else
            printf("%d",i);
        i++;
    }
}
```
三 (3) 
===

```
#include <stdio.h>
#include <stdlib.h>
main()
{
    int i;
    for(i=0;i<=10;i++)
    {
        if(i==5)
            break;
        else
            printf("%d",i);
    }
}
```
四 (4)
===
```
#include <stdio.h>
#include <stdlib.h>
main()
{
    int i;
    i=0;
ABC:
    if(i==10)
        goto XYZ;
    printf("%d",i);
    i++;
    goto ABC;
XYZ:
    return;
} 
```
五 (5)
===

```
#include <stdio.h>
#include <stdlib.h>
#include <windows.h>
#include <conio.h>

void clrscr() {
    system("cls");
}

void gotoxy(int x, int y) {
    COORD coord = { (SHORT)x, (SHORT)y };
    SetConsoleCursorPosition(GetStdHandle(STD_OUTPUT_HANDLE), coord);
}

main() {
    int k[5], j;

    srand(5678);
    clrscr();

    while (1) {
        k[0] = rand() % 9000 + 1000;

        k[1] = k[0] / 1000;
        k[2] = (k[0] % 1000) / 100;
        k[3] = (k[0] % 100) / 10;
        k[4] = k[0] % 10;

        gotoxy(10, 5);
        printf("%d%d%d%d", k[1], k[2], k[3], k[4]);

        for (j = 0; j < 10000000; j++) {
            int x = j * j;
        }
    }

    return 0;
}

```
===
DONT COPY DOWN BELOW
```
#include <stdio.h>
#include <stdlib.h>
#include <windows.h>
#include <conio.h>

void clrscr() {
    system("cls");
}

void gotoxy(int x, int y) {
    COORD coord = { (SHORT)x, (SHORT)y };
    SetConsoleCursorPosition(GetStdHandle(STD_OUTPUT_HANDLE), coord);
}

main() {
    int k[5], j;
    CONSOLE_SCREEN_BUFFER_INFO csbi;
    int screenWidth, screenHeight;
    int centerX, centerY;

    srand(5678);
    clrscr();

    // Get console screen size
    GetConsoleScreenBufferInfo(GetStdHandle(STD_OUTPUT_HANDLE), &csbi);
    screenWidth = csbi.srWindow.Right - csbi.srWindow.Left + 1;
    screenHeight = csbi.srWindow.Bottom - csbi.srWindow.Top + 1;

    centerY = screenHeight / 2;

    while (1) {
        k[0] = rand() % 9000 + 1000;

        k[1] = k[0] / 1000;
        k[2] = (k[0] % 1000) / 100;
        k[3] = (k[0] % 100) / 10;
        k[4] = k[0] % 10;

        // Format the number and get its length
        char buffer[10];
        sprintf(buffer, "%d%d%d%d", k[1], k[2], k[3], k[4]);

        // Center horizontally based on text width
        centerX = (screenWidth - strlen(buffer)) / 2;

        gotoxy(centerX, centerY);
        printf("%s", buffer);

        for (j = 0; j < 10000000; j++) {
            int x = j * j;
        }
    }

    return 0;
}
```