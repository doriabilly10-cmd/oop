import java.util.Scanner;

public class EmployeePayrollRecord {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Employee Name: ");
        String employeeName = input.nextLine();

        System.out.print("Employee ID: ");
        String employeeID = input.nextLine();

        System.out.print("Position: ");
        String position = input.nextLine();

        System.out.print("Hours Worked: ");
        double hoursWorked = input.nextDouble();

        System.out.print("Hourly Rate: ");
        double hourlyRate = input.nextDouble();

        System.out.println("\n--- Employee Payroll Record ---");
        System.out.println("Employee Name: " + employeeName);
        System.out.println("Employee ID: " + employeeID);
        System.out.println("Position: " + position);
        System.out.println("Hours Worked: " + hoursWorked);
        System.out.println("Hourly Rate: " + hourlyRate);
    }
}
