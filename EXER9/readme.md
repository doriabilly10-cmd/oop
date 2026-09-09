import java.util.Scanner;

public class OnlineGamePlayer {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Username: ");
        String username = input.nextLine();

        System.out.print("Character Name: ");
        String characterName = input.nextLine();

        System.out.print("Level: ");
        int level = input.nextInt();

        System.out.print("Experience Points: ");
        long experience = input.nextLong();

        input.nextLine();

        System.out.print("Rank: ");
        String rank = input.nextLine();

        System.out.println("\n--- Player Profile ---");
        System.out.println("Username: " + username);
        System.out.println("Character Name: " + characterName);
        System.out.println("Level: " + level);
        System.out.println("Experience Points: " + experience);
        System.out.println("Rank: " + rank);
    }
}
