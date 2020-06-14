
import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
		Scanner s = new Scanner(System.in);
		System.out.println("Enter the Number");
		int n = s.nextInt();
int flag = 0;
		int i;
		if(n == 0)
		{
		    System.out.println("It is not a Prime Number");
		}
		else if(n == 1)
		{
		    System.out.println("It is a Prime Number");
		}
		for(i=2; i<n; i++)
		{
		    if(n%i==0)
		    {
		         flag = 1;
		    }
		}
		if(flag == 0)
		{
		    System.out.println("The Number is a Prime Number");
		}
		else if(flag == 1)
		{
		    System.out.println("The Number is not a Prime Number");
		}
	}
}
