public class ABC 
{
	
public static void main(String[]args)
{
	Scanner sc=new Scanner(System.in);
	System.out.println("enter a number");
	int a=sc.nextInt();
        if(a<=9)
	{
		System.out.println("the number is one digit");
	}
	if(a>9 && a<=99)
	{
		System.out.println("the number is two digit");
	}
	else if(a>=100 && a<=999)
	{
		System.out.println("the number is three digit");
	}
	else if(a>=1000)
	{
		System.out.println("it is four digit number");
	}
}
}
