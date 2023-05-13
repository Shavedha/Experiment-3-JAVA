# Experiment-4-JAVA
## AIM
To create a Java program that prints even numbers from 1 to 20
## PROCEDURE
1. Import the Scanner class from the java.util package.
2. Define a public class named "Main".
3. Declare the main method with the signature "public static void main(String[] args)".
4. Declare an integer variable "i" to use in the for loop.
5. Start a for loop from 1 to 20 using "for(i = 1; i <= 20; i++)".
6. Check if 'i' is an even number and print the same.
7. End the program.
## PROGRAM
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Even numbers from 1 to 20 are:");
        int i;
        for (i = 1; i <= 20; i++) {
            if (i % 2 == 0) {
                System.out.println(i);
            }
        }
    }
}
```
## OUTPUT
<img width="478" alt="image" src="https://github.com/Shavedha/Experiment-3-JAVA/assets/93427376/62d6198f-89c9-46c5-bc95-968b03a98574">

## RESULT
Hence even numbers from 1 to 20 are printed using Java Program.
