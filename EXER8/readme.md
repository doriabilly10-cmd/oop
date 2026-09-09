import java.util.Scanner;

public class CourseEnrollment {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Student Name: ");
        String studentName = input.nextLine();

        System.out.print("Subject Code: ");
        String subjectCode = input.nextLine();

        System.out.print("Subject Title: ");
        String subjectTitle = input.nextLine();

        System.out.print("Units: ");
        int units = input.nextInt();

        System.out.print("Section Letter: ");
        char section = input.next().charAt(0);

        System.out.println("\n--- Course Enrollment Record ---");
        System.out.println("Student Name: " + studentName);
        System.out.println("Subject Code: " + subjectCode);
        System.out.println("Subject Title: " + subjectTitle);
        System.out.println("Units: " + units);
        System.out.println("Section: " + section);
    }
}
