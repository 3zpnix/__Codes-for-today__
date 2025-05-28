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