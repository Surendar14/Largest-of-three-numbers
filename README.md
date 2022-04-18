# Largest-of-three-numbers
## Aim:
Write a C# program to find the largest of three numbers.

## Algorith:

## Program:

using System;  
public class Exercise8  
{  
    public static void Main()
{
    int A, B, C;
    Console.Write("Input the value for A:");
    A = Convert.ToInt32(Console.ReadLine());
    Console.Write("Input the value for B:");
    B = Convert.ToInt32(Console.ReadLine());
    Console.Write("Input the value for C:");
    C = Convert.ToInt32(Console.ReadLine());
  if (A > B)
    {
        if (A > C)
        {
            Console.Write("A IS THE LARGEST OF ALL.. \n\n");
        }
        else
        {
            Console.Write("C IS THE LARGEST OF ALL.. \n\n");
        }
    }
    else if (B > C)
        Console.Write("B IS THE LARGEST OF ALL.. \n\n");
    else
        Console.Write("C IS THE LARGEST OF ALL.. \n\n");
}
}

## Output:
![Screenshot (49)](https://user-images.githubusercontent.com/75235759/163827174-d43abafd-315d-4a04-a1c3-bdd1cba2eae4.png)

## Result:
Thus, C# program to find the largest of three numbers was executed.
