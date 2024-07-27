<h5>Check vowel words</h5>

```Java
import java.util.*;

public class Mian {

    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        System.out.print("Enter value: ");

        String input = scan.nextLine();

        input = input.toLowerCase();

        boolean hasVowel = input.contains("a") || input.contains("e") || input.contains("i") || input.contains("o") || input.contains("u");

        if (hasVowel) {
            System.out.println("This is Vowel");
        } else {
            System.out.println("Not vowel handling");
        }    
    }
}
```
