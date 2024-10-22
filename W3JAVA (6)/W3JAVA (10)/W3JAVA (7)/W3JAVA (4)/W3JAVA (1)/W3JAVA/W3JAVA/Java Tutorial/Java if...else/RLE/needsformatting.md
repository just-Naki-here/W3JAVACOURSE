Java If ... Else Examples
Real-Life Examples
This example shows how you can use if..else to "open a door" if the user enters the correct code:

Example
int doorCode = 1337;

if (doorCode == 1337) {
  System.out.println("Correct code. The door is now open.");
} else {
  System.out.println("Wrong code. The door remains closed.");
}

This example shows how you can use if..else to find out if a number is positive or negative:

Example
int myNum = 10; // Is this a positive or negative number?

if (myNum > 0) {
  System.out.println("The value is a positive number.");
} else if (myNum < 0) {
  System.out.println("The value is a negative number.");
} else {
  System.out.println("The value is 0.");
}

Find out if a person is old enough to vote:

Example
int myAge = 25;
int votingAge = 18;

if (myAge >= votingAge) {
  System.out.println("Old enough to vote!");
} else {
  System.out.println("Not old enough to vote.");
}

Find out if a number is even or odd:

Example
int myNum = 5;

if (myNum % 2 == 0) {
  System.out.println(myNum + " is even");
} else {
  System.out.println(myNum + " is odd");
} 