```c
#include <stdio.h>
#include <kipr/wombat.h>

int main()
{
    // Defining a new integer variable named claw_servo and setting its value to 3.
    int claw_servo = 3;

    // Defining a new integer variable named open and setting its value to 0.
    int open = 0;

    // Defining a new integer variable named close and setting its value to 2048.
    int close = 2048;

    /*
        Calling the function printf.
        Passing two arguments to the function.
        The first argument is a string.
        The string contains a single format specificer for numbers and newline.
        The second argument is the integer stored in the variable `claw_servo`.
    */
    printf("The claw is on servo number %d. \n", claw_servo);

    /*
        Calling the function printf.
        Passing two arguments to the function.
        The first argument is a string.
        The string contains a single format specificer for numbers and newline.
        The second argument is the integer stored in the variable `open`.
    */
    printf("Setting servo position to %d open the claw. \n", open);

    /*
        Calling the function printf.
        Passing two arguments to the function.
        The first argument is a string.
        The string contains a single format specificer for numbers and newline.
        The second argument is the integer stored in the variable `close`.
    */
    printf("Setting servo position to %d closes the claw. \n", close);
}
```
