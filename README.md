#include <stdio.h>

int main() {
    int a, b, temp;

    // Input two numbers
    printf("Enter the first number: ");
    scanf("%d", &a);
    printf("Enter the second number: ");
    scanf("%d", &b);

    // Swapping logic using a temporary variable
    temp = a;
    a = b;
    b = temp;

    // Output the swapped numbers
    printf("After swapping:\n");
    printf("First number: %d\n", a);
    printf("Second number: %d\n", b);

    return 0;
}
