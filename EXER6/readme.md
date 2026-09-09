import java.util.Scanner;

public class MovieInformation {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Movie Title: ");
        String title = input.nextLine();

        System.out.print("Director: ");
        String director = input.nextLine();

        System.out.print("Release Year: ");
        int year = input.nextInt();

        System.out.print("Runtime in Minutes: ");
        int runtime = input.nextInt();

        System.out.print("Rating: ");
        double rating = input.nextDouble();

        System.out.println("\n--- Movie Information ---");
        System.out.println("Title: " + title);
        System.out.println("Director: " + director);
        System.out.println("Year: " + year);
        System.out.println("Runtime: " + runtime + " minutes");
        System.out.println("Rating: " + rating);
    }
}

