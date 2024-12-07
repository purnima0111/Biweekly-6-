# Biweekly-6-
using System;

namespace MyLabProgram
{
    class Program
    {
        static void Main(string[] args)
        {
            // Original variable and function call
            int result = AddNumbers(5, 10);
            Console.WriteLine("The result is: " + result);
        }

        // Function to add two numbers
       //Function takes two integers as input and returns their sum.
        static int AddNumbers(int num1, int num2)
        {
            return num1 + num2;
        }
    }
}
