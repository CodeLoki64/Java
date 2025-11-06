# Question 4: Stdin and Stdout II

*Taking inputs again*
In the previous program, we can see that I did say that we use different function calls of the scanner object when taking input from the user, here are most of the commonly used ones
```java
Scanner in = new Scanner(System.in); //Initializing the Scanner object
String s = in.next(); //Takes input upto the first blankspace character (' ')
String s2 = in.nextLine(); //Takes input of the entire line of string
int n = in.nextInt(); //This we use for integers
double d = in.nextDouble(); //This we use for Double
float f = in.nextFloat(); //This we use for Float
char c = in.next.charAt(0); //This we use take for one character
```
remember to always use a .nextLine() if you are taking an integer as an input followed by a string for an input, the .nextLine() would consume the leftover new line character. 
