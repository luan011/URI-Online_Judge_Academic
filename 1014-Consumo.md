```java
import java.io.IOException;
import java.util.Scanner;

public class Main {
 
    public static void main(String[] args) throws IOException {
                double resultado = 0;
		Scanner ler= new Scanner(System.in);
		int distancia =ler.nextInt();
		double combustivel =ler.nextDouble();
		resultado=distancia/combustivel;
		System.out.printf("%.3f km/l\n",resultado);
    }
 
}
```
