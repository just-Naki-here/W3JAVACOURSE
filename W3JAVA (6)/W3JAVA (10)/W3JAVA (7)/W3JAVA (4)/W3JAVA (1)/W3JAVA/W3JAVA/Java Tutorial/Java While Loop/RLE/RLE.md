Java While Loop Examples
Real-Life Examples
To demonstrate a practical example of the while loop, we have created a simple "countdown" program:

Example
int countdown = 3;

while (countdown > 0) {
  System.out.println(countdown);
  countdown--;
}

System.out.println("Happy New Year!!");

To demonstrate a practical example of the while loop combined with an if else statement, let's say we play a game of Yatzy:

Example
Print "Yatzy!" If the dice number is 6:

int dice = 1;

while (dice <= 6) {
  if (dice < 6) {
    System.out.println("No Yatzy.");
  } else {
    System.out.println("Yatzy!");
  }
  dice = dice + 1;
}

If the loop passes the values ranging from 1 to 5, it prints "No Yatzy". Whenever it passes the value 6, it prints "Yatzy!".