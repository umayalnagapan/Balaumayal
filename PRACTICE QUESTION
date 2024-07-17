1.TO CHECK VOWEL IS PRESENT IN THE STRING:

import java.util.*;
class Main
{
    public static void main(String args[])
    {
        System.out.println(vowelcontains("dfghij"));
        System.out.println(vowelcontains("pjkfgt"));
    }
     public static boolean vowelcontains(String input)
     {
         input=input.toLowerCase();
         if(input.contains("a")||input.contains("e")||input.contains("i")||input.contains("o")||input.contains("u"))
         {
             return true;
         }
         else
         {
             return false;
         }
     }
}

OUTPUT:

TRUE
FALSE


2.Write a Java method that returns the sum of all the even numbers in the list.

Example:
Given the list: [3, 7, 2, 8, 5, 6]

The method should return: 16 (since 2 + 8 + 6 = 16)

import java.util.*;
class Main
{
    public static void main(String args[])
    {
        Scanner s=new Scanner(System.in);
        System.out.println("Enter the size of the array:");
        int n=s.nextInt();
        int arr[]=new int[n];
        int sum=0;
        for(int i=0;i<n;i++)
        {
            arr[i]=s.nextInt();
            
           
        if(arr[i]%2==0)
        {
            sum+=arr[i];
        }
        }
       System.out.println(sum);
       
    }
}

OUTPUT:

Enter the size of the array:
6
3
7
2
8
5
6
16

=== Code Execution Successful ===


3.SWAPPING USING THIRD VARIABLE:

import java.util.*;
class Main
{
    public static void main(String args[])
    {
     int a,b;
     Scanner s=new Scanner(System.in);
     System.out.println("Enter value for a:");
     a=s.nextInt();
     System.out.println("Enter value for b:");
     b=s.nextInt();
     System.out.println("Before swapping:");
     System.out.println("a="+a);
     System.out.println("b="+b);
     int temp=0;
    
         temp=a;
         a=b;
         b=temp;
     
     System.out.println("After swapping");
     System.out.println("a="+a);
     System.out.println("b="+b);
     
     
    }
}

OUTPUT:

Enter value for a:
10
Enter value for b:
12
Before swapping:
a=10
b=12
After swapping
a=12
b=10

=== Code Execution Successful ===

4.SWAPPING WITHOUT USING THIRD VARIABLE:


import java.util.*;
class Main
{
    public static void main(String args[])
    {
     int a,b;
     Scanner s=new Scanner(System.in);
     System.out.println("Enter value for a:");
     a=s.nextInt();
     System.out.println("Enter value for b:");
     b=s.nextInt();
     System.out.println("Before swapping:");
     System.out.println("a="+a);
     System.out.println("b="+b);
     a=a+b;
     b=a-b;
     a=a-b;
    
     System.out.println("After swapping");
     System.out.println("a="+a);
     System.out.println("b="+b);
     
     
    }
}

OUTPUT:

Enter value for a:
12
Enter value for b:
10
Before swapping:
a=12
b=10
After swapping
a=10
b=12

=== Code Execution Successful ===

prime number check:

import java.util.*;
class Main
{
    public static void main(String args[])
    {
     System.out.println(isprime(19));
     System.out.println(isprime(24));
    }
    public static boolean isprime(int digit)
    {
        if(digit==0||digit==1)
        {
            return false;
        }
        if(digit==2)
        {
            return true;
        }
        for(int i=2;i<=digit/2;i++)
        {
            if(digit%i==0)
            {
                return false;
            }
           
        }
        return true;
    }
}

OUTPUT:

true
false

=== Code Execution Successful ===
