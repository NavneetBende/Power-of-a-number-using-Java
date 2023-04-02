# Power-of-a-number-using-Java

Power of a number using Java
factorial of number using java
Find the Power of a Number in Java
Given two integer inputs as number and the power, the objective is to raise the number to a power given. Therefore, we’ll write a Code to Find the Power of a Number in Java Language.

Example
Input : 2 3
Output : 8
Find the Power of a Number in Java Language
Given two integers as the number and power inputs, the objective is to raise the number input to the power input and print the value. To do so we’ll use the concepts of loops and recursion. Here are few methods to Find the Power of a Number in Java Language,

Method 1: Without While Loop
Method 2: With While Loop
We’ll discuss the above mentioned methods in depth in the upcoming sections.

Method 1: Without While Loop
Java Code
Run
public class Main
 {
 	public static void main(String[] args) {
	    
 	double base = 1.5;
     double expo1 = 2.5;
     double expo2 = -2.5;
     double res1, res2;
    
     // calculates the power
     res1 = Math.pow(base, expo1);
     res2 = Math.pow(base, expo2);
 	System.out.println(base + " ^ " + expo1 + " = " + res1 );
 	System.out.println(base + " ^ " + expo2 + " = " + res2 );
 	}
 }
Output
2.0 ^ 2.0 = 4.0
Method 2: With While Loop
Java Code
Run
public class Main
{
	public static void main(String[] args) {
	    
	double base = 1.5;
    // Works only when exponent is positive integer
    int expo = 2;
    double res = 1.0;
    
    while (expo != 0) {
        res *= base;
        expo--;
    }
    
    System.out.println("Result = " + res); 
	}
}
Output
Result = 2.25
