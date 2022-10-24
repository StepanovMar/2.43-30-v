using System;
public class Program
{
    public static void Main()
    {
        Console.WriteLine("Введите символ a");
        int a = int.Parse(Console.ReadLine());
        Console.WriteLine("Введите символ b");
        int b = int.Parse(Console.ReadLine());
        a = (a % b) * (b % a) + 1;
        Console.WriteLine(a);
    }
}
