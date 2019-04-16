```java
import java.io.IOException;
import java.util.Scanner;

public class Main {
 
    public static void main(String[] args) throws IOException {
        Scanner sc = new Scanner(System.in);
        int notas = sc.nextInt();

        System.out.printf("%d\n", notas);
        System.out.printf("%d nota(s) de R$ 100,00\n", notas/100);
        notas = (notas%100);

        System.out.printf("%d nota(s) de R$ 50,00\n", notas/50);
        notas = (notas%50);

        System.out.printf("%d nota(s) de R$ 20,00\n", notas/20);
        notas = (notas%20);

        System.out.printf("%d nota(s) de R$ 10,00\n", notas/10);
        notas = (notas%10);

        System.out.printf("%d nota(s) de R$ 5,00\n", notas/5);
        notas = (notas%5);

        System.out.printf("%d nota(s) de R$ 2,00\n", notas/2);
        notas = (notas%2);

        System.out.printf("%d nota(s) de R$ 1,00\n", notas/1);
    }
}
