```java
import java.io.IOException;
import java.util.Scanner;

public class Main {
 
    public static void main(String[] args) throws IOException {
			int DIFERENCA = 0;
	  		Scanner s = new Scanner(System.in);
	  		int A = Integer.parseInt(s.next());
	  		int B = Integer.parseInt(s.next());
	  		int C = Integer.parseInt(s.next());
	  		int D = Integer.parseInt(s.next());
	  		DIFERENCA = (A * B - C * D);
	  	  	System.out.printf("DIFERENCA = %d\n",DIFERENCA);
    }
 
}
```
