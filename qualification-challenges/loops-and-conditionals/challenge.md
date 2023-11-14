**READ THIS ENTIRE CHALLENGE AND ALL THE CODE BEFORE YOU START CODING.**

# Challenge

### Description

You can repeat code statements using a `while` loop in C.

### Example Code:

```c
  // Declaring a while loop.
  // For each turn of the loop.
  // If the expression "1 equals 1" evaluates to true.
  // Run the statements in the code block.
  while (1 == 1) {
    // Print the string with a newline character at the end.
    printf("This prints over and over, forever.\n");
  }
```

### Instructions:

1. Open the [Botball Simulator](https://www.botballacademy.org/sim).
2. Click on the `Editor` tab.
3. Resize your `Editor` to make it big by pulling on the `||` icon.
4. Select all the code in the `Editor` with `ctrl + a`.
5. Delete all the code in the `Editor` with `Backspace`.
6. Select the code below with your mouse.
7. Copy the code with `ctrl + c`.
8. Paste the code you copied into the `Editor` with `ctrl + v`.

```c
#include <stdio.h>
#include <kipr/wombat.h>

int main() {
  // Define a new integer variable, named mat_color, and set it equal to 0.
  int mat_color = 0;

  // Declaring a while loop.
  // For each turn of the loop.
  // If the expression "1 equals 1" evaluates to true.
  // Run the statements in the code block.
  while (1 == 1) {
    // TODO: Change the expression in the loop above to stop on black lines.

    // Calling the function motor with two arguments, 0 and 100.
    motor(0, 100);

    // Calling the function motor with two arguments, 3 and 100.
    motor(3, 100);

    // On the right we are calling the function analog with one argument, 1.
    // We are storing the result from calling analog in the variable mat_color.
    mat_color = analog(1);

    // We are calling the function printf with two arguments.
    // The first argument is a string with the %d format specificer and newline.
    // The second argument is the value of the variable mat_color.
    printf("%d\n", mat_color);
  }
}
```

9. Read all the code you just copied, to yourself, line by line.
10. Modify the loop to stop on black lines using the mat_color value.
11. Run your code and fix any errors.
