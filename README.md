# jubilant-potato
Hello World !

I have C# code How to make triangel pattern!

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace polabintang
{
    class Program
    {
        static void Main(string[] args)
        {
            int input;
            Console.Write("input : ");
            input = Convert.ToInt32(Console.ReadLine());
            for (int i = 1; i <= input; i++)
            {
                string x = "";
                Console.CursorLeft = input-i;
                for (int j = 1; j <= i; j++)
                    x += "*";
                Console.WriteLine("{0}", x);
            }
            Console.ReadKey();
                

        }
    }
}

