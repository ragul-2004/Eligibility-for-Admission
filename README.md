# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithnm:
## Step 1:
Declare variables for maths, physics, chemistry, and totalMarks.

## Step 2:
Use the Console.ReadLine() to get the inputs from the user.

## Step 3:
Calculate totalMarks as per the elegibility is mentioned.

## Step 4:
Check whether the student is eligible for admission using if else condition wth the given eligibility criteria.

## Step 5:
Use the Console.WriteLine() to display the eligibility status of the student.

## Program:
~~~
NAME : RAGUL A C
REG NO :212221240042
~~~
~~~
using System;
class EligibilityforAdmission
{
    static void Main(string[] args)
    {
        int maths, physics, chemistry, totalMarks1 ,totalMarks2;
        string name;
        Console.Write("Enter the student name: ");
        name = Console.ReadLine();

        Console.Write("Enter the marks obtained in maths: ");
        maths = Convert.ToInt32(Console.ReadLine());

        Console.Write("Enter the marks obtained in physics: ");
        physics = Convert.ToInt32(Console.ReadLine());

        Console.Write("Enter the marks obtained in chemistry: ");
        chemistry = Convert.ToInt32(Console.ReadLine());

        totalMarks1 = maths + physics + chemistry;
        totalMarks2 = maths + physics;
        if (maths >= 65 && physics >= 55 && chemistry >= 50 && totalMarks1 >= 180 || totalMarks2 >= 140)
        {
            Console.WriteLine(name+" you are eligible for admission.");
        }
        else
        {
            Console.WriteLine(name+" you are not eligible for admission.");
        }
        Console.ReadLine();
    }
}
~~~




## Output:
![3](https://user-images.githubusercontent.com/94367917/225675855-6ff6adc5-7b21-4cfc-ae4d-62a53df454ac.png)
![4](https://user-images.githubusercontent.com/94367917/225675915-178d4a2a-8bfa-49a3-9988-02ad974960de.png)




## Result:
Thus, C# program to find the eligibility for admission to an engineering course has been executed successfully.


