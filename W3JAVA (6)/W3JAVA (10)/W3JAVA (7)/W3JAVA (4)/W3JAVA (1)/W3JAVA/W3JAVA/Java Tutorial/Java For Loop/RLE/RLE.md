Real-Life Examples
To demonstrate a practical example of the for loop, let's create a program that counts to 100 by tens:

Example
for (int i = 0; i <= 100; i += 10) {
  System.out.println(i);
} 

In this example, we create a program that only print even values between 0 and 10:

Example
for (int i = 0; i <= 10; i = i + 2) {
  System.out.println(i);
}

And in this example, we create a program that prints the multiplication table for a specified number:

Example
int number = 2;

// Print the multiplication table for the number 2
for (int i = 1; i <= 10; i++) {
  System.out.println(number + " x " + i + " = " + (number * i));
} 