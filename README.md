# Largest-of-three-numbers
## Aim:
To write a C# program to find the largest of three numbers

## Algorithm:
### Step1: 
Start
### Step2:
Create a class and declare three variable with integer datatype
### Step3:
Use if condition to check whether num1 is largest than num2 and num3
### Step4:
Use elif condition to check whether num2 is largest than num1 and num3
### Step5:
Use else condition to display that third variable is largest among all the variables
### Step6:
stop

## Program:
using System;
public class hello
{
    public static void Main()
    {
        int num1, num2, num3;
        Console.WriteLine("Find the largest of three numbers:\n");

        Console.WriteLine("Enter the first number :");
        num1 = Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Enter the second number :");
        num2 = Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Enter the third number :");
        num3 = Convert.ToInt32(Console.ReadLine());

        if (num1 > num2)
        {
            if (num1 > num3)
            {
                Console.WriteLine("The first Number is the greatest among three"+num1);
            }
            else
            {
                Console.WriteLine("The third Number is the greatest among three"+num3);
            }
        }
        else if (num2 > num3)
            Console.WriteLine("The second Number is the greatest among three"+num2);
        else
            Console.WriteLine("The third Number is the greatest among three"+num3);
    }
}

## Output:
![image](https://user-images.githubusercontent.com/75241366/165436884-4071f3b6-61c3-4b32-8256-b286b7c7d01e.png)


## Result:
Thus the C# program to find the largest of three numbers is executed successfully
