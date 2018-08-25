
```java
import java.io.IOException;
import java.util.Scanner;
 
public class Main {
    public static void main(String[] args) throws IOException {
        double area = 0;
	Scanner s = new Scanner(System.in);
	double raio = Double.parseDouble(s.next());
	area = 3.14159*(raio*raio);
	System.out.printf("A=%.4f\n",area);
	}
}
```
