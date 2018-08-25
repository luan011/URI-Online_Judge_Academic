```java
import java.io.IOException;
import java.util.Scanner;
public class Main {
 
    public static void main(String[] args) throws IOException {
 		Scanner ler= new Scanner(System.in);
		int a = ler.nextInt();
		int b = ler.nextInt();
		int c = ler.nextInt();
		
		if(a > b && a > c) {
			System.out.printf("%d eh o maior\n",a);
		}
		else if(b > a && b > c) {
			System.out.printf("%d eh o maior\n",b);
		}
		else if(c > b && c > a) {
			System.out.printf("%d eh o maior\n",c);
		}
    }
 
}
```
