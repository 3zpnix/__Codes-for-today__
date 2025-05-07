<h1>你好</h1> - Please refresh the page every time you want to copy a code, okay bye! If there are any mistakes/wrong placement of code, please do tell me so I will fix it right away, thanks!

```
TO COPY & PASTE >
```
一 (1)
===
```
#include <stdio.h>
#include <stdlib.h>
#include <windows.h>
#include <conio.h>

void gotoxy(int xpos, int ypos); 

main() 
{
    int i = 0, j, k;
    gotoxy(15, 10);
    printf("gotoxy demo (press any key to continue)");
    getche(); 
    system("cls");
    gotoxy(20, 10);
    printf("hallo!");
    while(1); 
}

void gotoxy(int xpos, int ypos)
{
    COORD scrn;
    HANDLE hOutput = GetStdHandle(STD_OUTPUT_HANDLE); 
    scrn.X = xpos;
    scrn.Y = ypos;
    SetConsoleCursorPosition(hOutput, scrn);
}
```
二 (2)
===

```
#include <stdio.h>
#include <stdlib.h>
#include <windows.h>
#include <conio.h>

void gotoxy(int x, int y);

int main() {
    int x = 10, y = 10;
    char ch;

    while (1) {
        system("cls");
        gotoxy(x, y);
        printf("*");

        ch = getch(); 

        if (ch == 'w' || ch == 'W') y--;         // Move up
        else if (ch == 's' || ch == 'S') y++;    // Move down
        else if (ch == 'a' || ch == 'A') x--;    // Move left
        else if (ch == 'z' || ch == 'Z') x++;    // Move right
        else if (ch == 'c' || ch == 'C') system("cls");  // Clear screen
        else if (ch == 'q' || ch == 'Q') break;  // Quit
    }

    return 0;
}

void gotoxy(int x, int y) {
    COORD coord;
    coord.X = x;
    coord.Y = y;
    SetConsoleCursorPosition(GetStdHandle(STD_OUTPUT_HANDLE), coord);
}

```
三 (3) OPTIONAL LANG TO PO
===

```
#include <stdio.h>
#include <stdlib.h>
#include <windows.h>
#include <conio.h>

void gotoxy(int x, int y);

main() {
    int x, y;
    char ch;
    
    // Get console window size
    CONSOLE_SCREEN_BUFFER_INFO csbi;
    int columns, rows;
    GetConsoleScreenBufferInfo(GetStdHandle(STD_OUTPUT_HANDLE), &csbi);
    columns = csbi.srWindow.Right - csbi.srWindow.Left + 1;
    rows = csbi.srWindow.Bottom - csbi.srWindow.Top + 1;

    x = columns / 2;
    y = rows / 2;

    while (1) {
        system("cls");
        gotoxy(x, y);
        printf("*");

        ch = getch();  

        if (ch == 'w' || ch == 'W') y--;         // Move up
        else if (ch == 'z' || ch == 'Z') y++;    // Move down
        else if (ch == 'a' || ch == 'A') x--;    // Move left
        else if (ch == 'd' || ch == 'D') x++;    // Move right
        else if (ch == 'q' || ch == 'Q') break;  // Quit
        else if (ch == 'c' || ch == 'C') {  // Reset to center
        system("cls");
        x = columns / 2;
        y = rows / 2;
}
        }
    }

    return 0;
}

void gotoxy(int x, int y) {
    COORD coord;
    coord.X = x;
    coord.Y = y;
    SetConsoleCursorPosition(GetStdHandle(STD_OUTPUT_HANDLE), coord);
}
```
===
```
ang cute ni christian 🤭
```
===