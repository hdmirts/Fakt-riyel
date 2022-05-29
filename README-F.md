```java
import java.util.Scanner;

public class faktoriyel {
    public static void main(String[] args) {
        Scanner giris = new Scanner(System.in);
        System.out.print("Faktöriyel Sayısını Giriniz :");
        int m = giris.nextInt();        
        int bir = 1;

        for(int h = 1; h<=m; h++){
            bir = bir*h;
        }
        System.out.println(m +".Faktöriyel :" + bir);
    }
}

```

