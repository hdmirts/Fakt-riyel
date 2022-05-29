```java
import java.util.Scanner;

public class kombinasyon {
    public static void main(String[] args) {
        //C(n,r) = n! / (r! * (n-r)!)
        int a, b;
        int p = 1, k = 1, z = 1;
        Scanner inp = new Scanner(System.in);

        System.out.print("Birinci Sayıyı Giriniz :");
        a = inp.nextInt();

        System.out.print("İkinci Sayıyı Giriniz :");
        b = inp.nextInt();

        for(int x = 1; x <= a; x++){
            p = p*x; 
        }
        for(int y = 1; y <= b; y++){
            k = k*y;
        }
        for(int i = 1; i <= (a - b); i++){
            z = z*i;
        }
        // (p/(k*z))
     
        System.out.print("C(" + a + "," + b + ")=" + p/(k*z));
        
               
    }
    
    
}

```

