Making diamonds with stars using loops in Java

import java.util.Scanner;
public class Odev24 {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        int n;

        System.out.print("Enter an integer: ");
        n = input.nextInt();

        for (int i=0; i < n; i++) {
            for (int j=0; j < (n - 1 - i); j++) {
                System.out.print(" ");
            }
            for (int k=0; k < (2*i - 1); k++) {
                System.out.print("*");
            }

            System.out.println("");
        }
        for (int i=n-2; 0 <= i; i--) {
            for (int j=0; j < (n - 1 - i); j++) {
                System.out.print(" ");
            }
            for (int k=0; k < (2*i - 1); k++) {
                System.out.print("*");
            }

            System.out.println("");
        }

    }
}
