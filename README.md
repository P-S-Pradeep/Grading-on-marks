# Grading-on-marks

## Aim:
To write a C# program to grade the marks

## Algorithm:
### Step1:
Start

### Step2:
Create a class and declare one variable with integer datatype

### Step3:
Get input(Marks) from the User

### Step4:
Use condition statement to check the grade of the user 

### Step5:
Print the grade for the given mark

### Step6:
Stop


## Program:
~~~
using System;
namespace Grade
{
    class program
    {
            static void Main(string[] args)
            {
            int marks;
            Console.WriteLine("ENTER THE MARK:");
            marks = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("\nYOUR GRADE IS:");
            if (marks>90)
                Console.WriteLine("O GRADE");
            else if (marks > 80)
                Console.WriteLine("A+ GRADE");
            else if (marks > 70)
                Console.WriteLine("A GRADE");
            else if (marks > 60)
                Console.WriteLine("B+ GRADE");
            else if (marks > 50)
                Console.WriteLine("B GRADE");
            else if (marks >= 40)
                Console.WriteLine("C GRADE");
            else
                Console.WriteLine("FAIL");
        }
    }
}
~~~

## Output:
![Screenshot (55)](https://user-images.githubusercontent.com/102652887/163917040-b7e5a9de-e646-4003-ab33-3f7ec5606ea5.png)

## Result:
Thus the C# program to grade the marks is executed successfully.
