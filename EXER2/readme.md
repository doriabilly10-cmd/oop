
import java.util.Scanner;

public class BankAccountRecord {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Account Holder: ");
        String holder = input.nextLine();

        System.out.print("Account Number: ");
        String accountNumber = input.nextLine();

        System.out.print("Account Type: ");
        String accountType = input.nextLine();

        System.out.print("Balance: ");
        double balance = input.nextDouble();

        System.out.println("\n--- Bank Account Record ---");
        System.out.println("Account Holder: " + holder);
        System.out.println("Account Number: " + accountNumber);
        System.out.println("Account Type: " + accountType);
        System.out.println("Balance: PHP " + balance);
    }
}
