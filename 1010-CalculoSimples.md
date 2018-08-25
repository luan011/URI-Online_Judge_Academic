```java
import java.io.IOException;
import java.util.Scanner;

public class Main {
 
    public static void main(String[] args) throws IOException {
		double total=0;
		Scanner ler= new Scanner(System.in);
		for(int i =0;i<2;i++) {
			int codigo= ler.nextInt();
			int quantidade= ler.nextInt();
			double valor= ler.nextDouble();
			total+= quantidade * valor;
		}
		System.out.printf("VALOR A PAGAR: R$ %.2f\n",total);
 
    }
 
}
```
