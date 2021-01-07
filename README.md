# BestBabyNames.Java
// Program prints the best baby names based on the input of an alphabet.


/* 
Sidney Beatty
March 29, 2019
File BestBabyNames.java
Source References: 
* File: RolePlayingGame.java
* Author: Dr. Robertson
* Date: January 1, 2015

*/


import java.util.Scanner;

 class BestBabyNames  {	
    public static void main(String[] args)  { 	

	//* Greeting Display *//
       System.out.println("Best Names for Your Baby Begin With S, B, G, C ");

	//* Variables to hold values *//
	char name = 'S';
		
	//* Use the Scanner class to input data *//
        Scanner scannerIn = new Scanner(System.in);

	System.out.println("Enter the letter you want your babies name to start with:");
	// the next() method scans the next String value
	// the charAt(0) method takes the first character
        name = scannerIn.next().charAt(0);

	//* Verify the letter that was entered *//
	System.out.println("The following letter was entered " + name);

	
	switch (name) {
	  case 'S': case 's':
		//* Print out all the names that begin with S*//
		System.out.println("Girl names: Shaliyah, Sara, Susan, Syndee");
        System.out.println("Boy names: Sidney, Samson, Sean, Saul ");    
		System.out.println("Do you like these names?");
		break;
	case 'B': case 'b': 
		//* Print out all the names that begin with B*//
		System.out.println("Girl names: Brittany, Barbra, Brianne, Brochel");
		System.out.println("Boy names: Billy, Bronson, Bradley, Britian");
		System.out.println("Do you like these names?");
		break;
	case 'G': case 'g':
		//* Print out all the names that begin with G*//
		System.out.println("Girl names: Gabriel, Gayia, Gaezele, Galania");
		System.out.println("Boy names: George, Gus, Gumbyo, Geezy");
		System.out.println("Do you like these names?");
		break;		
	case 'C': case 'c':
		//* Print out all the names that begin with C*//
		System.out.println("Girl names: Camilia, Charlene, Casaundra, Chassy");
		System.out.println("Boy names: Carl, Covan, Cawai, Capone");
		System.out.println("Do you like these names?");
		break;	
	default:
		System.out.println("Enter one of the following letters to receive the best baby names (S,B,G, and C)");
	}
		
	//* Output *// 
	System.out.println("Thanks for entering one of the letters to recieve the best baby names " + names);	


    }
}
