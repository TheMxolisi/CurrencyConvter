import java.util.*;

public class Main
{
	public static void main(String[] args)
	{
		try{
			System.out.println("1.USD-ZAR");
			System.out.println("2.ZAR-USD");
			System.out.println("3.EURO-ZAR");
			System.out.println("4.ZAR-EURO");
			System.out.println("5.USD-EURO");
			System.out.println("6.EURO-USD");
            
			
			Scanner input=new Scanner(System.in);
			System.out.print("\nChoose :");
			int option1=input.nextInt();

			System.out.println("\n\nVerify your selection");
            
			
			mainMenu(option1);
			while(option1!=0){
			 if(option1==1){
				 
				 System.out.println("Enter 0 to return to main Menu");
				usdToZar();
				}
				
			}
			
			

		 if(option1==2){
				zarToUsd();
		}
		if(option1==3){
			euroTozar();
		}
		else if(option1==4){
			
			zarToEuro();
		
		}
		}catch(Exception e){

			System.out.println("Something went wrong :(");


		}
		}
	

	public static void mainMenu(int option){

		System.out.println("\n1.USD-ZAR");
		System.out.println("2.ZAR-USD");
		System.out.println("3.EURO-ZAR");
		System.out.println("4.ZAR-EURO");
		System.out.println("5.USD-EURO");
		System.out.println("6.EURO-USD");


		Scanner input=new Scanner(System.in);
		System.out.print("\nChoose :");
		option=input.nextInt();

	}
	public static void usdToZar(){

		Scanner input=new Scanner(System.in);
		System.out.print("Enter amount :$");
		double amount=input.nextInt();

		double dolla=17.49;
		if(amount==0){
			mainMenu1();
		}

		double zar=amount*dolla;

		System.out.println("$"+amount +" is R" +zar);
	}

	public static void zarToUsd(){

		Scanner input=new Scanner(System.in);
		System.out.print("Enter amount :R");
		double amount=input.nextDouble();

		double oneDolla=17.40;

		double zar=(amount/oneDolla);

		System.out.println("R"+amount +" is $" +zar);
	}

	public static void euroTozar(){
		
		Scanner input=new Scanner(System.in);
		System.out.print("Enter amount :£");
		double amount=input.nextDouble();

		double oneEuro=20.97;

		double zar=(amount*oneEuro);

		System.out.println("£"+amount +" is R" +zar);
		
	}
	
	public static void zarToEuro(){
		
		Scanner input=new Scanner(System.in);
		System.out.print("Enter amount :R");
		double amount=input.nextDouble();

		double oneEuro=20.97;

		double zar=(amount/oneEuro);

		System.out.println("£"+amount +" is R" +zar);
		
	}
	
	public static void mainMenu1(){
		
		System.out.println("\n1.USD-ZAR");
		System.out.println("2.ZAR-USD");
		System.out.println("3.EURO-ZAR");
		System.out.println("4.ZAR-EURO");
		System.out.println("5.USD-EURO");
		System.out.println("6.EURO-USD");


		Scanner input=new Scanner(System.in);
		System.out.print("\nChoose :");
		int option=input.nextInt();
	}
}
