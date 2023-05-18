using System;
using System.Runtime.InteropServices;
namespace Project
{
    class Test
    {
        public static void Main()
        {
            Console.WriteLine("please enter the sides of the cube :");
            Console.Write("x = ");
            int x = Convert.ToInt32(Console.ReadLine());
            Console.Write("y = ");
            int y = Convert.ToInt32(Console.ReadLine());
            Console.Write("z = ");
            int z = Convert.ToInt32(Console.ReadLine());
            double show = Calc(x, y, z);
            Console.WriteLine("volume = {0}", show);
        }
        private static double Calc(int num1, int num2, int num3)
        {
            double Result = num1 * num2 * num3;
            return Result;
        }
    }
}
