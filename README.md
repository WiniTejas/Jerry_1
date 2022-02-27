using System;
public class Reverse
{ public static void Main()
    {
        /*string A, str1 = "";
        int i, p;
        Console.Write("Print a string in reverse order:");
        Console.Write("Input  A String : ");
        A = Console.ReadLine();
        Console.WriteLine(A.ToLower());
        p = A.Length - 1;
        for (i = p; i >= 0; i--)
        {
            str1 = str1 + A[i];
        }
        Console.WriteLine("The string in Reverse  Order Is : {0}", str1);*/

        int A, B, X;
        Console.WriteLine("enter first num");
        A = Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("enter second num");
        B = Convert.ToInt32(Console.ReadLine());
        X = A;
        A = B;
        B = X;
        Console.WriteLine("after swap first num is " + A + " second num is " + B);
        
        
        /////////////////////////////
        
        new program for Q1 Assignment 27 feb 2022
        
            string a, b, temp;
            Console.WriteLine("enter first string");
            a = Console.ReadLine();
            Console.WriteLine("enter second string");
            b = Console.ReadLine();
            if (a == b)
            {
                Console.WriteLine("entered strings are same");
                temp = a;
                a = b;
                b = temp;
            }
            else
                Console.WriteLine("entered strings are not equal");
            Console.WriteLine("{0}  {1}", a, b);
        }
    }
}
        
        
 
    }
}
