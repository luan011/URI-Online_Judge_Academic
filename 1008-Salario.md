```java
import java.io.IOException;
import java.util.Scanner;

public class Main {
 
    public static void main(String[] args) throws IOException {
	  		Scanner s = new Scanner(System.in);
	  		int A = Integer.parseInt(s.next());
	  		int B = Integer.parseInt(s.next());
	  		double c = Double.parseDouble(s.next());
	  	  	System.out.printf("NUMBER = %d\n",A);
	  	  	System.out.printf("SALARY = U$ %.2f\n",B*c);
    }
 
}
```
