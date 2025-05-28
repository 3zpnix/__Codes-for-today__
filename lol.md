```
#include <stdio.h>
#include <stdlib.h>
#include <windows.h>
#include <conio.h>  // For getch only

void gotoxy(int x, int y) {
    COORD coord = { (SHORT)x, (SHORT)y };
    SetConsoleCursorPosition(GetStdHandle(STD_OUTPUT_HANDLE), coord);
}

void clrscr() {
    system("cls");
}

main() {
    int i, num;

    srand(12345);  // fixed seed to avoid time.h
    clrscr();

    for (i = 0; i < 100; i++) {
        num = rand() % 9000 + 1000;

        gotoxy(0, 0);
        printf("%d  ", num);

        Sleep(200);
    }

    gotoxy(0, 1);
    printf("Done! Press any key to exit...");
    getch();

    return 0;
}
```