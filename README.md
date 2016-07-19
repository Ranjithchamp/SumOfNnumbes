# SumOfNnumbes
import java.util.Scanner;

public class SumOfNumbers {

	public static void main(String[]arg)
	{
		Scanner get=new Scanner(System.in);
		long n=get.nextInt();
		long sum=0;
		for(long i=1;i<=n;i++)
		{
			sum=sum+i;
		}
		System.out.println("sum = "+sum);
	}
}
