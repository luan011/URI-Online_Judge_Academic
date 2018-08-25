```java
import java.io.IOException;
import java.util.Scanner;

public class Main {
 
    public static void main(String[] args) throws IOException {
 
        Scanner s= new Scanner(System.in);
		do{
	 		long resultado = 1;
			long resultado2 = 1;
			long m = Long.parseLong(s.next());
			long n = Long.parseLong(s.next());
	
			for(int i=1; i <= m; i++) {
				resultado*=i;
			}
			for(int j=1; j <= n; j++) {
				resultado2*=j;
			}
			System.out.println(resultado+resultado2);
		}while(s.hasNext());
    } 
}
```
