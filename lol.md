```
#include <stdio.h>
#include <stdlib.h>
#include <conio.h>

void clrscr() {
    system("cls");
}

void gotoxy(int x) {
    int i;
    for (i = 0; i < x; i++) {
        printf(" ");
    }
}

int main() {
    int i, k[5];
    srand(1234);

    for (i = 0; i < 5; i++)  // print 5 newlines once to go down to line 5
        printf("\n");

    for (i = 0; i < 100000; i++) {
        k[0] = rand() % 9000 + 1000;
        k[1] = k[0] / 1000;
        k[2] = (k[0] % 1000) / 100;
        k[3] = (k[0] % 100) / 10;
        k[4] = k[0] % 10;

        clrscr();

        for (i = 0; i < 5; i++)  // move cursor down again after clearing
            printf("\n");

        gotoxy(10);

        printf("%d%d%d%d", k[1], k[2], k[3], k[4]);
    }

    printf("\n\nPress any key to exit...");
    getch();
    return 0;
}
```