# laba-2
using System;

namespace Laba_2
{
    public class Program
    {
        int x; 

        static void Main(string[] args)
        {
           
            Console.WriteLine("Введите аргумент x:");
            int x = Convert.ToInt32(Console.ReadLine());
            int s = 0; //счётчик количества цифр в числе
            int ch = x; 
            if (ch!= 0)
            {
                s = s + 1;
                ch = ch / 10;
            }
            private int Massive (int i)
            {
                var mass = new int [i];
            }
        }


        static int Massive(string[] args)
        {
            int[] nums = new int[s];
            foreach (int i in nums)

                nums[0] = x % 10;
                nums[i] = nums[i - 1]%10;
        }
    }
}
