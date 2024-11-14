package ClassAssignment;

import java.util.Scanner;

public class CheckPositiveOrNegtive {

	public static void main(String[] args) {
		
		// Create a scanner object to read input from user
        Scanner scanner = new Scanner(System.in);
        
     // Prompt user to enter a number
        System.out.print("Enter a number: ");
        int number = scanner.nextInt();
        
     // Check if the number is positive, negative or zero
        if (number > 0) {
            System.out.println(number + " is a positive number.");
        } else if (number < 0) {
            System.out.println(number + " is a negative number.");
        } else {
            System.out.println("The number is zero.");
        }

        // Close the scanner
        scanner.close();
	}
}

Output
Enter a number: 4
4 is a positive number.
