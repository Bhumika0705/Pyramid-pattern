# Pyramid-pattern
pyramid pattern using java
import java.util.Scanner;

public class pyramid {
    public pyramid() {
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int r = sc.nextInt();

        for(int i = 1; i <= r; ++i) {
            int k;
            for(k = 1; k <= r - i; ++k) {
                System.out.print(" ");
            }

            for(k = 1; k <= 2 * i - 1; ++k) {
                System.out.print("*");
            }

            System.out.println();
        }

    }
}
