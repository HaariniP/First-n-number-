# First-n-number-
import java.util.Scanner;
public class FirstNNumbers {
 public static void main(String[] args) {
 Scanner scanner = new Scanner(System.in);
 System.out.print("Enter the value of n: ");
  int n = scanner.nextInt();
        System.out.println("The first " + n + " numbers are:");
        for (int i = 1; i <= n; i++) {
            System.out.print(i + " ");
        }
    }
}
Output 
The first 5 numbers are:
1 2 3 4 5
