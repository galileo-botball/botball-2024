# Challenge

### Description

You can create a variable for storing a number in C using the `int` keyword.

### Example Code:

```c
    /* Storing numbers in variables. */
    int x = 0;
    int y = 1;
    int z = 2;
```

### Instructions:

1. Open the [Botball Simulator](https://www.botballacademy.org/sim).
2. In the **Editor** tab, replace the code with this code:

```c
#include <stdio.h>
#include <kipr/wombat.h>

int main()
{
  /* Your code goes here. */

  printf(
      "The claw is on servo %d. \n"
      "Setting the servo position to %d opens the claw. \n"
      "Setting the servo position to %d closes the claw. \n",
      claw, open, closed
  );
}
```

3. Create an `int` variable called `claw` and store the value 3 in it.
4. Create a `int` variable called `open` and store the value 0 in it.
5. Create a `int` variable called `closed` and store the value 2048 in it.
6. Run the code and fix any errors.
7. Copy and paste your code into the Botball team's channel.

# References

- [C Datatypes](https://www.freecodecamp.org/news/data-types-in-c-integer-floating-point-and-void-explained/)
- [Format Specifiers](https://www.freecodecamp.org/news/format-specifiers-in-c/)
