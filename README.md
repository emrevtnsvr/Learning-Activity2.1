
using System;

class Program
{
    static void Main(string[] args)
    {
        LearningActivity21();
    }

    static void LearningActivity21()
    {
        // Welcome message
        Console.WriteLine("Welcome to the Legend of Zelda adventure!");

        // Prompt the player to enter their name
        Console.Write("Please enter your name: ");
        string playerName = Console.ReadLine();

        // Greet the player with their name
        Console.WriteLine($"Hello {playerName}, ready to embark on your quest?");
    }
}

