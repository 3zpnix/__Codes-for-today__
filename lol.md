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
    int i, k[5];

    srand(5678);
    clrscr();

    for (i = 0; i < 100; i++) {
        k[0] = rand() % 9000 + 1000;   

        k[1] = k[0] / 1000;
        k[2] = (k[0] % 1000) / 100;
        k[3] = (k[0] % 100) / 10;
        k[4] = k[0] % 10;

        gotoxy(10, 5);                
        printf("%d%d%d%d", k[1], k[2], k[3], k[4]);

        Sleep(200);                    
    }

    gotoxy(10, 6);
    printf("Done! Press any key...");
    getch();

    return 0;
}