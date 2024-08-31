import java.util.Scanner;

public class FactorialCalculator {

    // Method to calculate factorial of a number
    public static long factorial(int number) {
        long result = 1;
        for (int i = 1; i <= number; i++) {
            result *= i;
        }
        return result;
    }

    public static void main(String[] args) {
        // Create a Scanner object to get user input
        Scanner scanner = new Scanner(System.in);

        // Prompt the user for input
        System.out.print("Enter a positive integer: ");
        
        // Read the input from the user
        int number = scanner.nextInt();

        // Check if the input is a valid positive integer
        if (number < 0) {
            System.out.println("Please enter a positive integer.");
        } else {
            // Calculate the factorial
            long result = factorial(number);

            // Display the result
            System.out.println("The factorial of " + number + " is " + result + ".");
        }

        // Close the scanner
        scanner.close();
    }
}
