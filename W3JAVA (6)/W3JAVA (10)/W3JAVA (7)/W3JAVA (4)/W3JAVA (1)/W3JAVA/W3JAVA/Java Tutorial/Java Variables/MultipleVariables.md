# Java Declare Multiple Variables

## Declare Many Variables

To declare more than one variable of the **same type**, you can use a comma-separated list:

Example
Instead of writing:

```java
int x = 5;
int y = 6;
int z = 50;
System.out.println(x + y + z);
```

You can simply write:

```java
int x = 5, y = 6, z = 50;
System.out.println(x + y + z);
```

## One Value to Multiple Variables

You can also assign the **same value** to multiple variables in one line:

Example

```java
int x, y, z;
x = y = z = 50;
System.out.println(x + y + z);
```
