# Sıralama 

## Code 
```java 
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int a, b, c;
        Scanner inp = new Scanner(System.in);

        System.out.println("1. sayıyı gir:");
        a = inp.nextInt();

        System.out.println("2. sayıyı gir:");
        b = inp.nextInt();

        System.out.println("3. sayıyı gir:");
        c = inp.nextInt();

        if ((a > b) && (a > c)) {
            if (b > c) {
                System.out.println("b > a > c");
            } else {
                System.out.println("b > c > a");

            }
        } else {
            if (a > b) {
                System.out.println("c > a > b");
            } else {
                System.out.println("c > b > a");
            }
        }

    }
}
```
