**READ THIS ENTIRE CHALLENGE AND ALL THE CODE BEFORE YOU START CODING.**

# Challenge

### Description

You can create a variable for storing a number in C using the `int` keyword.

### Example Code:

```c
    /* Creating a new variable named x, setting it equal to the integer 0. */
    int x = 0;

    /* Creating a new variable named y, setting it equal to the integer 1. */
    int y = 1;

    /* Creating a new variable named z, setting it equal to the integer 2. */
    int z = 2;
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

int main()
{
  /* TODO: Add variables claw_servo, open, and close. */

  printf(
      "The claw is on servo %d. \n"
      "Setting the servo position to %d opens the claw. \n"
      "Setting the servo position to %d closes the claw. \n",
      claw_servo, open, close
  );
}
```

9. Read all the code you just copied, to yourself, line by line.
10. Create an `int` variable called `claw_servo` and store the value `3` in it.
11. Create an `int` variable called `open` and store the value `0` in it.
12. Create an `int` variable called `close` and store the value `2048` in it.
13. Run your code and fix any errors.
14. Send the completed code, via Microsoft Teams, to your coach.
15. Reply with the "thumbs up" emoji to the challenge post in Microsoft Teams.

# References

- [C Datatypes](https://www.freecodecamp.org/news/data-types-in-c-integer-floating-point-and-void-explained/)
- [Format Specifiers](https://www.freecodecamp.org/news/format-specifiers-in-c/)
