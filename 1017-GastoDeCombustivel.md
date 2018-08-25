```java
import java.io.IOException;
import java.util.Scanner;

public class Main {
 
    public static void main(String[] args) throws IOException {
	        double res= 0;
		Scanner ler= new Scanner(System.in);
		int tempo= ler.nextInt();
		int velocidade= ler.nextInt();
		res= (velocidade/12.0)*tempo;
		System.out.printf("%.3f\n",res);	
    }
 
}
```
