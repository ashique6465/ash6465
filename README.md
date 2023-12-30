using System;

// Define a struct named Number
public struct Number
{
    // Property "Amount" of data type decimal
    public decimal Amount { get; set; }
}

class Program
{
    static void Main()
    {
        // Create an object of data type Number and initialize it
        Number myNumber = new Number();

        // Assign an amount to the Number object
        myNumber.Amount = 42.56M;

        // Print the amount to the console
        Console.WriteLine($"Amount: {myNumber.Amount}");

        // Wait for user input before closing the console
        Console.ReadLine();
    }
}
