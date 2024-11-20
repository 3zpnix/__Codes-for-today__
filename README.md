#include <stdio.h>

int main() {
    int i, j, k;

    printf("Enter the number of rows: ");
    scanf("%d", &k);

    // Upper half of the diamond
    for (i = 1; i <= k; i++) {
        // Print spaces
        for (j = 1; j <= k - i; j++) {
            printf(" ");
        }
        // Print asterisks
        for (j = 1; j <= 2 * i - 1; j++) {
            printf("*");
        }
        printf("\n");
    }

    // Lower half of the diamond (excluding the middle row)
    for (i = k - 1; i >= 1; i--) {
        // Print spaces
        for (j = 1; j <= k - i; j++) {
            printf(" ");
        }
        // Print asterisks
        for (j = 1; j <= 2 * i - 1; j++) {
            printf("*");
        }
        printf("\n");
    }

    return 0;
}
