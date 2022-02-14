# result
using System;
using System.IO;
using System.Linq;
using System.Collections.Generic;

namespace CSharp_Shell
{

    public class Program 
    {
        public static void Main()
        {
			 int per;
			 Console.WriteLine("Percentage of student is: ");
			 per=Convert.ToInt32(Console.ReadLine());
			 if(per>=70&&per<=80)
			 {
			 	Console.WriteLine("passed with Distinction");
			 }
			 else if(per>=60&&per<=70)
			 {
			 	Console.WriteLine("passed with first class");
			 }
			 else if(per>=40&&per<=60)
			 {
			 	Console.WriteLine("pass");
			 }
			 else
			 {
			 	Console.WriteLine("fail");
			 }
        }
    }
}
