# laba-2



using System;

namespace Laba_2
{
    class Program
    {
        int x; 

        Console.WriteLine("Введите аргумент x:");
            int x = Convert.ToInt32(Console.ReadLine());
            int[] mass = MassGenerate(x);
            foreach (var massElement in mass)
            {
                Console.WriteLine(massElement.ToString());
            }
            Console.ReadKey();
        }

        private static int[] MassGenerate(int x)
        {
            int xRes=x;
            int div = 10;
            int[] resultArray = new int[x.ToString().Length];
            for (int i = resultArray.Length-1; i >= 0; i--)
            {
                xRes =x % 10;
                resultArray[i] = xRes;
                x /= 10;
            }
            return resultArray;
    }
}
