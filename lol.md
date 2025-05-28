```
#include <stdio.h>
#include <stdlib.h>
#include <conio.h>

int main() {
    int i, k[5];

    srand(1234);

    for (i = 0; i < 1000; i++) {
        k[0] = rand() % 9000 + 1000;

        k[1] = k[0] / 1000;
        k[2] = (k[0] % 1000) / 100;
        k[3] = (k[0] % 100) / 10;
        k[4] = k[0] % 10;

        printf("\r          ");  // clear previous number (overwrite with spaces)
        printf("\r          %d%d%d%d", k[1], k[2], k[3], k[4]);  // overwrite again
    }

    printf("\n\nPress any key to exit...");
    getch();

    return 0;
}
```