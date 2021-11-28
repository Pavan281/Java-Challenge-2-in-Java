# Java-Challenge-2-in-Java

//Java Program to print Fibonacci series

public class test
{
    public static void main(String[] args) 
    {
        //Take input from the user
        //Create instance of the Scanner class
        int a=0,b=1,c;
        System.out.print(a+" "+b);
        //Print the fibonacci series
        for (int i = 1; i <= 10; i++)
        {
            c=a+b;
	          System.out.print(" "+c);
            a=b;
	          b=c;
        }
    }
}
