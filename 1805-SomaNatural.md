```java
import java.io.IOException;
import java.util.Scanner;

public class Main {
 
    public static void main(String[] args) throws IOException {
		long res=0;
		Scanner ler = new Scanner(System.in);
		long A = Long.parseLong(ler.next());
		long B = Long.parseLong(ler.next());
		
		while(A <= B){
			res+=A;
			A++;
		}	
		System.out.println(res);		
    }
}
```
