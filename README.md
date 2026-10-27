import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter your age: ");
        int age = scanner.nextInt();
        int yearsUntil100 = 100 - age;

        if (yearsUntil100 > 0) {
            System.out.println("You have " + yearsUntil100 + " years until you are 100 years old.");
        } else {
            System.out.println("You are already 100 years old or older.");
        }

        scanner.close();
    }
}
