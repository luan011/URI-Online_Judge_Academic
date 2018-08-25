```java
import java.io.IOException;
import java.util.Scanner;
 
public class Main {
    public static void main(String[] args) throws IOException {
	  int PROD = 0;
	  Scanner s = new Scanner(System.in);
	  int a = Integer.parseInt(s.next());
	  int b = Integer.parseInt(s.next());
	  PROD= a * b;
	  System.out.printf("PROD = %d\n",PROD);
    } 
}
```
