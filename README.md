#include <stdio.h>
int main() {
    int arr[] = {10, 20, 30, 40, 50};
    int *ptr;
    ptr = arr;
    printf("Pointer Arithmetic Demonstration:\n\n");
    for(int i = 0; i < 5; i++) {
        printf("Value at ptr + %d = %d\n", i, *(ptr + i));
    }
    printf("\nIncrementing Pointer:\n");
    ptr++;                                             printf("Value after ptr++ = %d\n", *ptr);
    printf("\nDecrementing Pointer:\n");
    ptr--;  
    printf("Value after ptr-- = %d\n", *ptr);
    return 0;
}
