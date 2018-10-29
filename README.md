# java
import java.util.Scanner;
class Loc
{
	Scanner sc=new Scanner(System.in);
	System.out.println("Near locations/Towns are:");
	System.out.println("1.Nuzvid\n2.Vijayawada\n3.Junction\n4.Gudivada\n");
	System.out.println("Select your Town here::");
	int k=sc.nextInt();
}
class Theatres extends Mov
{
	Scanner sc=new Scanner(System.in);
	
	if(k=1)
	{	
		
		System.out.println("Available Theatres in Nuzvid::");
		System.out.println("1.King\n2.Satyanarayana\n3.Apsara\n4.mini\n");
		System.out.println("Select your Theare here::");
		int l=sc.nextInt();
	}
	if(k=2)
	{	
		
		System.out.println("Available Theatres in Vijayawada::\n");
		System.out.println("1.Murali\n2.Naveen\n3.Sai\n4.Bittu\n");
		System.out.println("Select your Theare here::\n");
		int l=sc.nextInt();
	}
	if(k=3)
	{	
		
		System.out.println("Available Theatres in Junction::\n");
		System.out.println("1.Kumar\n2.Sana\n3.MNB\n4.Nav\n");
		System.out.println("Select your Theare here::\n");
		int l=sc.nextInt();
	}
	if(k=4)
	{	
		
		System.out.println("Available Theatres in Gudivada::\n");
		System.out.println("1.Geetha\n2.Kishore\n3.Nataraj\n4.Padmalaya\n");
		System.out.println("Select your Theare here::\n");
		int l=sc.nextInt();
	}
	System.out.println("Theatres in ")
}
class Mov extends Loc
{
	Scanner sc=new Scanner(System.in);
	if(l==1)
	{
		System.out.println("In the Given theatre Available Movies are::\n");
		System.out.println("1.Bahubali\n2.Dangal\n3.Aravinda Sametha\n4.Hello\n");
		System.out.println("Select your movie here::\n");
		int c=sc.nextInt();	
	}
	if(l==2)
	{
		System.out.println("In the Given theatre Available Movies are::\n");
		System.out.println("1.Bahubali\n2.Dangal\n3.Aravinda Sametha\n");
		System.out.println("Select your movie here::\n");
		int c=sc.nextInt();	
	}
	if(l==3)
	{
		System.out.println("In the Given theatre Available Movies are::\n");
		System.out.println("1.Bahubali\n2.Dangal\n");
		System.out.println("Select your movie here::\n");
		int c=sc.nextInt();	
	}
	if(l==4)
	{
		System.out.println("In the Given theatre Available Movies are::\n");
		System.out.println("1.Bahubali\n2.Dangal\n3.Aravinda Sametha\n4.Hello\n");
		System.out.println("Select your movie here::\n");
		int c=sc.nextInt();	
	}
}
class Seats
{
	int a=40,e=40,i=20,t=0;
	Scanner sc=new Scanner(System.in);
	if(c==1)
	{
		System.out.println("In this theatre Arrangement of Seats are 100 a-j::\n");
		System.out.println("cost for seats are like this bottom to up \n1.a,b,c,d rows 50$\n2.e,f,g,h rows 100 $\n3.i,j rows 150$::\n");
		System.out.println("Select your row By selecting above coices\n");
		int m=sc.nextInt();
		if(m==1)
		{
			if(a>0)
			{
				System.out.println("enter the number of tickets \n");
				int n=sc.nextInt();
				System.out.println("You have to pay money",n*50);
				while(n>=0)
				{
					if(a>0)
					{
						System.out.println("Your seat numbes are",a--);
						n--;
						t++;
					}
					else
					{
						System.out.println("these many seats are only available",t);
					}
				}
			}
			else
			{
				System.out.println("In this row tickets are not available sorry\n");
			}
		if(m==2)
		{
			
			if(e>0)
			{
				t=0;
				System.out.println("enter the number of tickets \n");
				int n=sc.nextInt();
				System.out.println("You have to pay money",n*100);
				while(n>=0)
				{
					if(e>0)
					{
						System.out.println("Your seat numbes are",e--);
						n--;
						t++;
					}
					else
					{
						System.out.println("these many seats are only available",t);
					}
				}
			}
			else
			{
			
				System.out.println("In this row tickets are not available sorry\n");
			}	
		if(m==3)
		{
			t=0;
			if(i>0)
			{
				System.out.println("enter the number of tickets \n");
				int n=sc.nextInt();
				System.out.println("You have to pay money",n*150);
				while(n>=0)
				{
					if(i>0)
					{
						System.out.println("Your seat numbes are",i--);
						n--;
						t++;
					}
					else
					{
						System.out.println("these many seats are only available",t);
					}
				}
			}
			
		}
		else
		{
			System.out.println("In this row tickets are not available sorry\n");
		}	
	}
	if(c==2)
	{
		System.out.println("In this theatre Arrangement of Seats are 100 a-j::\n");
		System.out.println("cost for seats are like this bottom to up \n1.a,b,c,d rows 50$\n2.e,f,g,h rows 100 $\n3.i,j rows 150$::\n");
		System.out.println("Select your row By selecting above coices\n");
		int m=sc.nextInt();
		if(m==1)
		{
			if(a>0)
			{
				System.out.println("enter the number of tickets \n");
				int n=sc.nextInt();
				System.out.println("You have to pay money",n*50);
				while(n>=0)
				{
					if(a>0)
					{
						System.out.println("Your seat numbes are",a--);
						n--;
						t++;
					}
					else
					{
						System.out.println("these many seats are only available",t);
					}
				}
			}
			else
			{
				System.out.println("In this row tickets are not available sorry\n");
			}
			
		}
		if(m==2)
		{
			
			if(e>0)
			{
				t=0;
				System.out.println("enter the number of tickets \n");
				int n=sc.nextInt();
				System.out.println("You have to pay money",n*100);
				while(n>=0)
				{
					if(e>0)
					{
						System.out.println("Your seat numbes are",e--);
						n--;
						t++;
					}
					else
					{
						System.out.println("these many seats are only available",t);
					}
				}
			}
		}
		else
		{
		
			System.out.println("In this row tickets are not available sorry\n");
		}	
		if(m==3)
		{
			t=0;
			if(i>0)
			{
				System.out.println("enter the number of tickets \n");
				int n=sc.nextInt();
				System.out.println("You have to pay money",n*150);
				while(n>=0)
				{
					if(i>0)
					{
						System.out.println("Your seat numbes are",i--);
						n--;
						t++;
					}
					else
					{
						System.out.println("these many seats are only available",t);
					}
				}
			}
			
		}
		else
		{
			System.out.println("In this row tickets are not available sorry\n");
		}
	}
	if(c==3)
	{
		System.out.println("In this theatre Arrangement of Seats are 100 a-j::\n");
		System.out.println("cost for seats are like this bottom to up \n1.a,b,c,d rows 50$\n2.e,f,g,h rows 100 $\n3.i,j rows 150$::\n");
		System.out.println("Select your row By selecting above coices\n");
		int m=sc.nextInt();
		if(m==1)
		{
			if(a>0)
			{
				System.out.println("enter the number of tickets \n");
				int n=sc.nextInt();
				System.out.println("You have to pay money",n*50);
				while(n>=0)
				{
					if(a>0)
					{
						System.out.println("Your seat numbes are",a--);
						n--;
						t++;
					}
					else
					{
						System.out.println("these many seats are only available",t);
					}
				}
			}
			else
			{
				System.out.println("In this row tickets are not available sorry\n");
			}
			
		}
		if(m==2)
		{
			
			if(e>0)
			{
				t=0;
				System.out.println("enter the number of tickets \n");
				int n=sc.nextInt();
				System.out.println("You have to pay money",n*100);
				while(n>=0)
				{
					if(e>0)
					{
						System.out.println("Your seat numbes are",e--);
						n--;
						t++;
					}
					else
					{
						System.out.println("these many seats are only available",t);
					}
				}
			}
		}
		else
		{
		
			System.out.println("In this row tickets are not available sorry\n");
		}	
		if(m==3)
		{
			t=0;
			if(i>0)
			{
				System.out.println("enter the number of tickets \n");
				int n=sc.nextInt();
				System.out.println("You have to pay money",n*150);
				while(n>=0)
				{
					if(i>0)
					{
						System.out.println("Your seat numbes are",i--);
						n--;
						t++;
					}
					else
					{
						System.out.println("these many seats are only available",t);
					}
				}
			}
			
		}
		else
		{
			System.out.println("In this row tickets are not available sorry\n");
		}
	}
	if(c==4)
	{
		System.out.println("In this theatre Arrangement of Seats are 100 a-j::\n");
		System.out.println("cost for seats are like this bottom to up \n1.a,b,c,d rows 50$\n2.e,f,g,h rows 100 $\n3.i,j rows 150$::\n");
		System.out.println("Select your row By selecting above coices\n");
		int m=sc.nextInt();
		if(m==1)
		{
			if(a>0)
			{
				System.out.println("enter the number of tickets \n");
				int n=sc.nextInt();
				System.out.println("You have to pay money",n*50);
				while(n>=0)
				{
					if(a>0)
					{
						System.out.println("Your seat numbes are",a--);
						n--;
						t++;
					}
					else
					{
						System.out.println("these many seats are only available",t);
					}
				}
			}
			else
			{
				System.out.println("In this row tickets are not available sorry\n");
			}
			
		}
		if(m==2)
		{
			
			if(e>0)
			{
				t=0;
				System.out.println("enter the number of tickets \n");
				int n=sc.nextInt();
				System.out.println("You have to pay money",n*100);
				while(n>=0)
				{
					if(e>0)
					{
						System.out.println("Your seat numbes are",e--);
						n--;
						t++;
					}
					else
					{
						System.out.println("these many seats are only available",t);
					}
				}
			}
		}
		else
		{
		
			System.out.println("In this row tickets are not available sorry\n");
		}	
		if(m==3)
		{
			t=0;
			if(i>0)
			{
				System.out.println("enter the number of tickets \n");
				int n=sc.nextInt();
				System.out.println("You have to pay money",n*150);
				while(n>=0)
				{
					if(i>0)
					{
						System.out.println("Your seat numbes are",i--);
						n--;
						t++;
					}
					else
					{
						System.out.println("these many seats are only available",t);
					}
				}
			}
			
		}
		else
		{
			System.out.println("In this row tickets are not available sorry\n");
		}
	}
}
class Main
{

}
