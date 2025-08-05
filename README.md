#include <stdio.h>

// Void function definition
void hello() {
    printf("GeeksforGeeks\n");
}

// Return-type function definition
int square(int x) {
    return x * x;
}

int main() {
    
    // Calling the void function
    hello();

    // Calling the return-type function
    int result = square(5);
    printf("Square of 5 is: %d", result);

    return 0;
}
