<h5>Logical Programming</h5>
<ol>
    <li>Number Programming</li>
    <li>String Programming</li>
    <li>Array Programming</li>
    <li>Pattern Programming</li>
</ol>
<h5>Number Programming</h5>
<p>1. Java program to check if the given number is  a odd or even number ?</p>
<p>Using Bitwise AND Operator</p>

```Java
public class Main {
    public static void main(String[] args) {
        int num = 23;
        if ((num & 1) == 0) {
            System.out.println("even number"); // 23 & 1 = 1, 1 == 0
        } else {
            System.out.println("odd number");
        }
    }
}
```
