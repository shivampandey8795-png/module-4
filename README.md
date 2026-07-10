import java.util.Scanner;

public class sequenceOfn {
    public static void main(String[] args) {
        System.out.println("enter the required n");
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        for (int i = 1; i <= n; i++) {
            System.out.print(i);
        }
    }
}
//problem 2
import java.util.Scanner;

public class sumOFSequence {

    public static void main(String[] args) {
        System.out.println("enter the required n");
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int sum = 0;
        for (int i = 1; i <= n; i++) {

            sum = sum + i;

        }
        System.out.println(sum);
    }
}
