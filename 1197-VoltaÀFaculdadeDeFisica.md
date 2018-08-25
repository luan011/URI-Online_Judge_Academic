```java
import java.io.IOException;
import java.util.Scanner;

public class Main {
 
    public static void main(String[] args) throws IOException {
                int resultado = 0;
		Scanner ler= new Scanner(System.in);
		do{
		  int v =ler.nextInt();
		  int t =ler.nextInt();
		  resultado=(v*2)*t;
		  System.out.println(resultado);
		}while(ler.hasNext());
    }
 
}
```
