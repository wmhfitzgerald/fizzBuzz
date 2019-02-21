# fizzBuzz

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;


namespace FizzBuzz
{
    class Program
    {
        static void Main(string[] args)
        {
          for(int i = 1; i <= 100; i++){
              
              var p = (i % 15 == 0) ? "FIZZ BUZZ" : 
                      (i % 3 == 0) ? "FIZZ" :
                      (i % 5 == 0) ? "BUZZ" : i.ToString();
              Console.WriteLine(p);
          }
        }
    }
}
