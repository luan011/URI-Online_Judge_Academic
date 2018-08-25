```java
import java.io.IOException;
import java.util.Scanner;

public class Main {
 
    public static void main(String[] args) throws IOException {
 	        double volume=0;
		Scanner ler= new Scanner(System.in);
		double raio = ler.nextDouble();
		double pi = 3.14159;
		volume = (4/3.0) * pi * (raio*raio*raio);
		System.out.printf("VOLUME = %.3f\n",volume);
    }
}
```
