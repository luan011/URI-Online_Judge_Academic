```java
import java.io.IOException;
import java.util.Scanner;

public class Main {
 
    public static void main(String[] args) throws IOException {
		double resultado = 0;
		Scanner ler= new Scanner(System.in);
		double x1 =ler.nextDouble();
		double y1 =ler.nextDouble();
		double x2 =ler.nextDouble();
		double y2 =ler.nextDouble();
		resultado = Math.sqrt(((x2-x1)*(x2-x1)) + ((y2-y1)*(y2-y1)));
		System.out.printf("%.4f\n",resultado);
    }
 
}
```
