# Question 2: Stdin and Stdout 1

*Taking Inputs*
One popular way to read input from stdin is by using the [Scanner Class](https://docs.oracle.com/javase/8/docs/api/java/util/Scanner.html) and specifying the Input Stream as System.in. For example:

```java
Scanner scanner = new Scanner(System.in);
String myString = scanner.next();
int myInt = scanner.nextInt();
scanner.close();

System.out.println("myString is: " + myString);
System.out.println("myInt is: " + myInt);
```

now for different data types we have different functions of the scanner. That we will look in the further questions

The Scanner class is a part of the util package. We call in the main function by creating its object, and giving it the name "scanner" now the funtions of the Scanner class will be referenced using the name "scanner".

Alternatively, we can also use BufferedReader Class.