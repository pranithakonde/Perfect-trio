# Perfect-trio
import java.util.*;
import java.lang.*;
import java.io.*;

/* Name of the class has to be "Main" only if the class is public. */
class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
			Scanner s = new Scanner(System.in);
		    int t = s.nextInt();
		    for(int i =0;i<t;i++)
		    {    
		        int a = s.nextInt();
		        int b = s.nextInt();
		        int c = s.nextInt();
		        if(a==(b+c)||b==(a+c)||c==(a+b))
		                System.out.println("YES");
		        else
		                System.out.println("NO");
		    }
	}
}
