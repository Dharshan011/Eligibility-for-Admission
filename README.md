# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithnm:
## Step 1:
Create a New project or class.

## Step 2:
Declare the variable and read the input from the user.

## Step 3:
Find the total1 and total2.

## Step 4:
Check the given condition using nested if statement.

## Step 5:
Display the output whether the student is eligible or not.

## Program:
```
using System;

public class ConsoleApp1
{
    public static void Main(string[] args)
    {
        int phy, chem, mat, tot1, tot2;
        string name;
        Console.WriteLine("Enter the Phy mark:");
       phy = Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Enter the chem mark:");
       chem= Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Enter the mat mark:");
        mat= Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Enter a Name of the student");
        name = Console.ReadLine();
        tot1 = phy + chem + mat;
        tot2 = phy + mat;
        if(phy>=55 && chem>=50 && mat>=65)
        {
            if(tot1>=180 || tot2>=140)
            {
                Console.WriteLine("{0} is eligible for engineering admission",name);
            }
            else
            {
                Console.WriteLine(name + " is not eligible for engineering admission");

            }
        }
        else
        {
            Console.WriteLine("{0} is not eligible for engineering admission",name);
        }

    }
}
```
## Output:

![Screenshot 2023-08-18 210921](https://github.com/Dharshan011/Eligibility-for-Admission/assets/113497491/c07462ae-fc5c-4c84-95b8-f3191d8aa509)


## Result:
Thus the C# program to check the eligibility of a student on engineering admission is successfully executed.
