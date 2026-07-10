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
