# AP-1402_2_18
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp16
{
    internal class Program
    {
        static void Main(string[] args)
        {
            int x = Convert.ToInt32(Console.ReadLine());
            int y = Convert.ToInt32(Console.ReadLine());
            if (x != 0)
            {
                double z = Math.Pow(x, 2) * Math.Pow(y, 5) * Math.Sqrt(Math.Sin(x * y)) / x;
                       
                Console.WriteLine(z);
                Console.ReadKey();
            }


        }
    }
}
