```java
import java.io.IOException;
import java.util.Scanner;

public class Main {
 
    public static void main(String[] args) throws IOException {
        Scanner ler = new Scanner(System.in);
        int dias = ler.nextInt();

        System.out.printf("%d ano(s)\n", dias / 365);
        dias = (dias % 365);
        System.out.printf("%d mes(es)\n", dias / 30);
        dias = (dias % 30);
        System.out.printf("%d dia(s)\n", dias / 1);
        dias = (dias % 1);
    }
}
