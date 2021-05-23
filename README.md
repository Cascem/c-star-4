# c-star-4
I used the (for) to take a picture of the star. ver4
#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>
int main() {
	int i, j, n, k = 0;;
	scanf("%d", &n);
	for (i = n * 2-1; i > 1; i -= 2) {
		for (j = 1; j <= k; j++) {
			printf(" ");
		}
		k++;
		for (j = 1; j <= i; j++) {
			printf("*");
		}
		printf("\n");
	}
	k = n - 1;
	for (i = 1; i <= n * 2; i += 2) {
		for (j = 1; j <= k; j++) {
			printf(" ");
		}
		k--;
		for (j = 1; j <= i; j++) {
			printf("*");
		}
		printf("\n");
	}
	return 0;
}
