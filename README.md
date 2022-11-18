import java.io.File;
import java.util.*;
public class MainClass {
 public static void main(String[] args) throws Exception {
		Scanner sc=new Scanner(new File("menu.txt"));
	while(sc.hasNextLine())
			System.out.println(sc.nextLine());
Scanner scInput=new Scanner(System.in);
		System.out.println("Enter your choice");
		int i=scInput.nextInt();		
				
if(i==1)
		{
			Scanner sc1=new Scanner(new File("C:\\Users\\User\\Documents\\project\\indian.txt"));
			while(sc1.hasNextLine())
		        System.out.println(sc1.nextLine());
                            
		             System.out.println("Enter your choice");
		             int k=scInput.nextInt();
                                if(k==1){
                                    Scanner sc2=new Scanner(new File("C:\\Users\\User\\Documents\\project\\breakfast.txt")); 
                                    while(sc2.hasNextLine())
			            System.out.println(sc2.nextLine());}
                                else if(k==2){
                                    Scanner sc2=new Scanner(new File("C:\\Users\\User\\Documents\\project\\lunch.txt")); 
                                    while(sc2.hasNextLine())
			            System.out.println(sc2.nextLine()); }
                                else if(k==3){
                                     Scanner sc2=new Scanner(new File("C:\\Users\\User\\Documents\\project\\dinner.txt")); 
                                    while(sc2.hasNextLine())
			            System.out.println(sc2.nextLine());}
                               else if(k==4){
                                    Scanner sc2=new Scanner(new File("C:\\Users\\User\\Documents\\project\\dessert.txt")); 
                                    while(sc2.hasNextLine())
			            System.out.println(sc2.nextLine());}
else if(i==2)
		{
			Scanner sc1=new Scanner(new File("C:\\Users\\User\\Documents\\project\\mexican.txt"));
			while(sc1.hasNextLine())
				System.out.println(sc1.nextLine());
                                       System.out.println("Enter your choice");
		             int j=scInput.nextInt();
                                if(j==1){
                                    Scanner sc2=new Scanner(new File("C:\\Users\\User\\Documents\\project\\mbreakfast.txt")); 
                                    while(sc2.hasNextLine())
			            System.out.println(sc2.nextLine());}
                                else if(j==2){
                                    Scanner sc2=new Scanner(new File("C:\\Users\\User\\Documents\\project\\mfood.txt")); 
                                    while(sc2.hasNextLine())
			            System.out.println(sc2.nextLine()); }
                               else if(j==3){
                                    Scanner sc2=new Scanner(new File("C:\\Users\\User\\Documents\\project\\mdessert.txt")); 
                                    while(sc2.hasNextLine())
			            System.out.println(sc2.nextLine());}

		}
else if(i==3)
		{
			Scanner sc1=new Scanner(new File("C:\\Users\\User\\Documents\\project\\chinese.txt"));
			while(sc1.hasNextLine())
				System.out.println(sc1.nextLine());
                                    System.out.println("Enter your choice");
		             int k=scInput.nextInt();
                                if(k==1){
                                    Scanner sc3=new Scanner(new File("C:\\Users\\User\\Documents\\project\\cstarters.txt")); 
                                    while(sc3.hasNextLine())
			            System.out.println(sc3.nextLine());}
                                else if(k==2){
                                    Scanner sc3=new Scanner(new File("C:\\Users\\User\\Documents\\project\\cfood.txt")); 
                                    while(sc3.hasNextLine())
			            System.out.println(sc3.nextLine()); }
                               else if(k==3){
                                    Scanner sc3=new Scanner(new File("C:\\Users\\User\\Documents\\project\\cdessert.txt")); 
                                    while(sc3.hasNextLine())
			            System.out.println(sc3.nextLine());}
   
		} 
else if(i==4){
                  Scanner sc1=new Scanner(new File("C:\\Users\\User\\Documents\\project\\korean.txt"));
			while(sc1.hasNextLine())
				System.out.println(sc1.nextLine());
                            System.out.println("Enter your choice");
		             int l=scInput.nextInt();
                                if(l==1){
              Scanner sc4=new Scanner(new File("C:\\Users\\User\\Documents\\project\\food.txt")); 
                                    while(sc4.hasNextLine())
			            System.out.println(sc4.nextLine());}
                               else if(l==4){
          Scanner sc4=new Scanner(new File("C:\\Users\\User\\Documents\\project\\dessert.txt")); 
                                    while(sc4.hasNextLine())
			            System.out.println(sc4.nextLine());}
else if(i==5){
                  
                         Scanner sc2=new Scanner(new File("C:\\Users\\User\\Documents\\project\\american.txt"));
			 while(sc2.hasNextLine())
				System.out.println(sc2.nextLine());
                            System.out.println("Enter your choice");
		             int m=scInput.nextInt();
                                if(m==1){
                                    Scanner sc5=new Scanner(new File("C:\\Users\\User\\Documents\\project\\afood.txt")); 
                                    while(sc5.hasNextLine())
			            System.out.println(sc5.nextLine());}
                               else if(m==4){
                                    Scanner sc5=new Scanner(new File("C:\\Users\\User\\Documents\\project\\adessert.txt")); 
                                    while(sc5.hasNextLine())
			            System.out.println(sc5.nextLine());}
else if(i==6){
                     Scanner sc3=new Scanner(new File("C:\\Users\\User\\Documents\\project\\coffees.txt"));
			 while(sc3.hasNextLine())
				System.out.println(sc3.nextLine());
                              Scanner sc3Input=new Scanner(System.in);}
                              
                  
                        
               else if(i==7){
                        
                      Scanner sc4=new Scanner(new File("C:\\Users\\User\\Documents\\project\\juices and shakes.txt"));
			 while(sc4.hasNextLine())
				System.out.println(sc4.nextLine());
                           Scanner sc4Input=new Scanner(System.in);}
		

	}
}
}}
