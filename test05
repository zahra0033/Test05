using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApplication13
{
    class Program
    {
        static void Main(string[] args)
        {
            int n = int.Parse(Console.ReadLine());
            int[] ar = new int[n];
            for (int i = 0; i < n; i++)
            {
                ar[i] = int.Parse(Console.ReadLine());
            }
            //max
            int j = ar[0];
            for (int i = 1; i < n; i++)
            {
                if (j < ar[i])
                    j = ar[i];
            }
            Console.WriteLine(j);
            {
                //min
                int z = ar[0];
                for (int i = 1; i < n; i++)
                {
                    if (z > ar[i])
                        z = ar[i];
                }
                Console.WriteLine(z);
                //average
                int a = ar[0];
                for (int i = 0; i < n; i++)
                {
                    a += ar[i];
                }
                Console.WriteLine(a / n);
                Console.ReadKey();
            }
        }
    }
}
