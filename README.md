# Pattern
Microsoft Visual Studio 2022.
## Aim:
To write a C# program for a pascal's triangle.
## Equipment Required:

## Algorithm:
1.Start the program.

2.Get the limit from the user,use for loop to print the rows ,columns and space.

3.Use condition inside the loop to print the values.

4.Print the Pascal's triangle.

5.End the program.
## Program:
```
Name: Varsha Ajith
Reg no: 212221230118
```
```
using System;
namespace PascalTriangleDemo
{


    class Program
    {
        public static void Main() 
        {
            Console.Write("Enter the number of rows for Pascal's Triangle: \n");
            int rows=5, c = 1;
            for (int i = 0; i < rows; i++)
            {
                for (int s = 0; s < rows - i; s++)
                    Console.Write(" ");
                for (int j = 0; j <= i; j++)
                {
                    if (i == 0 || j == 0)

                        c = 1;


                    else

                        c = c * (i - j + 1) / j;
                    Console.Write(c + " ");



                }
                Console.WriteLine();

            }
        }
    }
}

```

## Output:
<img width="877" alt="Screenshot 2023-08-22 095816" src="https://github.com/VarshaAjith1110/C-Pattern/assets/94222288/28258c5a-5b6c-4bce-a40c-ace9267738dd">

## Result:
A C# program for a pascal's triangle is executed successfully.
