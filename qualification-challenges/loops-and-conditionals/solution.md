```c
#include <stdio.h>
#include <kipr/wombat.h>

int main() {
  // Define a new integer variable and set it equal to 0.
  int mat_color = 0;

  // Declaring a while loop.
  // For each turn of the loop.
  // If the expression "mat_color value less than 3000" evaluates to true.
  // Run the statements in the code block.
  while (mat_color < 3000) {
    // Calling the function motor with two arguments, 0 and 100.
    motor(0, 100);

    // Calling the function motor with two arguments, 0 and 100.
    motor(3, 100);

    // On the right we are calling the function analog with one argument, 0.
    // We are storing the result from calling analog in the variable mat_color.
    mat_color = analog(1);

    // We are calling the function printf with two arguments.
    // The first argument is a string with the %d format specificer and newline.
    // The second argument is the value of the variable mat_color.
    printf("%d\n", mat_color);
  }
}
```
