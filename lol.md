```
#include <stdio.h>
#include <stdlib.h>
#include <conio.h>
#include <windows.h>

int main()
{
    int i, num;

    srand(12345);  // Fixed seed (no time.h needed)
    clrscr();      // Clear screen

    for (i = 0; i < 100; i++) {
        num = rand() % 9000 + 1000;

        gotoxy(0, 0);      // Move cursor to top-left
        printf("%d  ", num);

        Sleep(200);        // Pause 200ms
    }

    gotoxy(0, 1);
    printf("Done! Press any key to exit...");
    getch();              // Wait for keypress

    return 0;
}
```