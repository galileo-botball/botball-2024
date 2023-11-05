**READ THIS ENTIRE CHALLENGE AND ALL THE CODE BEFORE YOU START CODING.**

# Challenge

### Description

You can define reusable code blocks called "functions" in C.

### Example Code:

```c
#include <stdio.h>

/*
  Defining a function.
  That takes two parameters, named x and y.
  Which returns an integer.
*/
int add(int x, int y) {
    // Creating a new integer variable called sum.
    int sum;

    /*
      Adding the variable x to the variable y.
      Storing the result of the addition in the variable named sum.
    */
    sum = x + y;

    // Returning the value stored in the variable sum.
    return sum;
}

// Defining a function called main that returns an integer. */
int main()
{
    // Calling a function named `add` with two arguments, the integers `1` and `2`.
    add(1, 2);

    // Calling the function and storing it's return value.
    int sum = add(1, 2);

    /*
      Calling the function `printf` with two arguments.
      The first argument is a string.
      The string contains the format specifier for an integer and a newline.
      The second argument is the variable named `sum`.
    */
    printf("%d \n", sum);

    /* Returning the integer 0. */
    return 0;
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

// Defining a new integer variable named `claw_servo` and set its value to `3`.
int claw_servo = 3;

// Defining a new integer variable named `open` and set its value to `0`.
int open = 0;

// Define a new integer variable named `closed` and set its value to `2048`.
int close = 2048;

// Defining a function named `open_claw`.
void open_claw() {
  // Calling the function `enabled_servos`.
  enable_servos();

  // Calling the function `set_servo_position`.
  set_servo_position(claw_servo, open);

  // Calling the function `msleep` with the argument `2000`.
  msleep(2000);
}

// TODO: Define a function to close the claw, named `close_claw`.

int main()
{
  // Calling the function named `open_claw`.
  open_claw();

  // TODO: Call your `close_claw` function.
}
```

8. Read all the code you just copied, to yourself, line by line.
9. Complete the code in the areas marked as `TODO`.
10. Run your code and fix any errors.
11. Send the completed code, via Microsoft Teams, to your coach.
12. Reply with the "thumbs up" emoji to the challenge post in Microsoft Teams.

# References

[Servo Functions](https://files.kipr.org/wallaby/wallaby_doc/group__servo.html)
