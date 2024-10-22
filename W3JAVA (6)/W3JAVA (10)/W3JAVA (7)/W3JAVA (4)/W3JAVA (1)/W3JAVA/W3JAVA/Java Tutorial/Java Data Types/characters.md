# Java Characters
## Characters
The ```char``` data type is used to store a **single** character. The character must be surrounded by single quotes, like 'A' or 'c':

Example
```
char myGrade = 'B';
System.out.println(myGrade);
```
Alternatively, if you are familiar with ASCII values, you can use those to display certain characters:

Example
```
char myVar1 = 65, myVar2 = 66, myVar3 = 67;
System.out.println(myVar1);
System.out.println(myVar2);
System.out.println(myVar3);
```
Tip: A list of all ASCII values can be found in our ASCII Table Reference.

Strings
The String data type is used to store a sequence of characters (text). String values must be surrounded by double quotes:

Example
String greeting = "Hello World";
System.out.println(greeting);

The String type is so much used and integrated in Java, that some call it "the special ninth type".

A String in Java is actually a non-primitive data type, because it refers to an object. The String object has methods that are used to perform certain operations on strings. Don't worry if you don't understand the term "object" just yet. We will learn more about strings and objects in a later chapter.