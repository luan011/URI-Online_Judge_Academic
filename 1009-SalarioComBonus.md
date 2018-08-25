```java
import java.io.IOException;
import java.util.Scanner;

public class Main {
 
    public static void main(String[] args) throws IOException {
		double total = 0;
		Scanner s= new Scanner(System.in);
		String nome = s.next();
		double slfixo = Double.parseDouble(s.next());
		double montante=Double.parseDouble(s.next());
		total = slfixo + (montante*0.15);
		System.out.printf("TOTAL = R$ %.2f\n", total );
		
    }
}
```
