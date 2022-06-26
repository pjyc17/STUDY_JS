```
/******************************************************************************

                            Online C# Compiler.
                Code, Compile, Run and Debug C# program online.
Write your code in this editor and press "Run" button to execute it.

*******************************************************************************/

using System;
public class HelloWorld {
  static void Main(string[] args) 
  {
    int[] i = new int[0];
    Console.WriteLine(i[0]);
  }
}

using System;
public class HelloWorld 
    {
        public static void Main(string[] args) 
        {
            int[] arr = new int[2];
            arr[1] = 10;
            Object o = arr;
            int[] arr1 = (int[])o;
            arr1[1] = 100;
            Console.WriteLine(arr[1]);
            ((int[])o)[1] = 1000;
            Console.WriteLine(arr[1]);
            
        }
    }

using System;
using System.Collection.Generic;
namespace KohYoung
public class HelloWorld 
    {
        public static void Main(string[] args) 
        {
            char x = 'A';
            int i = 0;
            Console.WriteLine(true ? x : 0);
            
            Console.WriteLine(false ? i : x);
            
        }
    }


// using System;
// using System.Collections.Generic;
// namespace Ky
//     {
//         public delegate void sampleDelegate(int num);
//         public class testDelegate
//         {
//             public void checkEven(int num)
//             {
//                 if(num%2 == 0)
//                 Console.WriteLine("This number is an even number");
//                 else
//                 Console.WriteLine("This number is an odd number");
//             }
//             public void squareNumber(int num)
//             {
//                 Console.WriteLine("Square of this number is: {0}", num*num);
//             }
//         }
//         class sample
//         {
//             public static void Main()
//             {
//                 testDelegate obj = new testDelegate();
//                 sampleDelegate delegateObj = new sampleDelegate(obj.checkEven);
//                 delegateObj += new sampleDelegate(obj.squareNumber);
//                 delegateObj(25);
//             }
//         }
//     }

// using System;
// public class Problem
// {
//     public static void Main()
//     {
//         classA a = new classC();
//         Console.WriteLine(a.Print());
//     }
    
//     public class classA
//     {
//         public virtual string Print()
//         {
//             return "classA";
//         }
//     }
    
//     public class classB : classA
//     {
//         public override string Print()
//         {
//             return "classB";
//         }
//     }
    
//     public class classC : classB
//     {
//         public new string Print()
//         {
//             return "classC";
//         }
//     }
    
    
// }
// using System;
// public class Problem{
//     public static void Main(string[] args)
//     {
//         {
//             try
//             {
//                 throw new NullReferenceException("C");
//                 Console.WriteLine("A");
//             }
//             catch (ArithmeticException e)
//             {
//                 Console.WriteLine("B");
//             }
//             Console.ReadLine();
//         }
//     }
// }
// using System;
// class Problem
// {
//     public static void Main()
//     {
//         var test = SingletonB.Test;
//     }
// }
// class SingletonB
// {
//     static readonly SingletonB _instance = new SingletonB();
//     public static SingletonB Test { get { return _instance; } }
//     private SingletonB()
//     {
//         Console.WriteLine("default constructor");
//     }
//     static SingletonB()
//     {
//         Console.WriteLine("Static constructor");
//     }
// }
// using System;
// public class Problem
// {
//     public static void Main(string[] args)
//     {
//         try
//         {
//             Console.WriteLine("wir");
//             Environment.Exit(0);
//         }
//         finally
//         {
//             Console.WriteLine("totheworld");
//         }
//     }
// }
// using System;
// public class Calculation
// {
//     int sum = 0;
//     int count = 0;
//     float average;
//     public void CalAverage()
//     {
//         if (count == 0)
//         throw(new CountisZeroException ("Zero count in DoAverage"));
//         {
//             average = sum / count;
//             Console.WriteLine("program executed successfully");
//         }
//     }
// }
// public class CountisZeroException : ApplicationException
// {
//     public CountisZeroException ( string message) : base (message)
//     {
        
//     }
// }
// class Program
// {
//     static void Main (string[] args)
//     {
//         Calculation c = new Calculation();
//         try
//         {
//             c.CalAverage();
//         }
//         catch(CountisZeroException e)
//         {
//             Console.WriteLine("CountisZeroException : {0}",e);
//         }
//         Console.ReadLine();
//     }
// }
// using System;
// public class Program
// {
//     static void Main(string[] args)
//     {
//         Derived d = new Derived();
//         int i = 10;
//         d.Func(i);
//         Console.ReadKey();
//     }
// }
// public class Base
// {
//     public virtual void Func(int x)
//     {
//         Console.WriteLine("Base.Func(int)");
//     }
// }
// public class Derived : Base
// {
//     public override void Func(int x)
//     {
//         Console.WriteLine("Derived.Func(int)");
//     }
//     public void Func(object o)
//     {
//         Console.WriteLine("Derived.Func(object)");
//     }
// }
using System;

// public class Problem
// {
//     struct Person
//     {
//         // public int id {get; set;}
//         // public string first_name {get; set;}
//         // public string last_name {get; set;}
//         public int id;
//         public string first_name;
//         public string last_name;
//     }
//     static void Main(string[]args)
//     {
//         Person p = new Person();
//         p.id = 10;
//         p.first_name = "park";
//         p.last_name = "juyoon";
//     }

//         Console.WriteLine(Person);
    
// }
public struct Person
{
    public int id;
    public string first_name;
    public string last_name;
    public void setId(int x)
    {
        id = x;
    }
    // public void setFirst_name(string y);
    // {
    //     first_name = y;
    // }
    // public void setLast_name(string z);
    // {
    //     last_name = z;
    // }
    public int getId()
    {
        return id;
    }
    public string getFirst_name()
    {
        return first_name;
    }
    public string getLast_name()
    {
        return last_name;
    }
    
}

```

