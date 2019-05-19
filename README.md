# LambdaMethodReference

## Assignment

- Change the System.out.println method call to be a method reference

```
import java.util.Arrays;
import java.util.List;

public class Main {
    public static void main(String[] args) {

        List names =  Arrays.asList("Anna", "Bob", "Charlie");

        System.out.println("for loop\t");
        for (String name : names) {
            System.out.println(name);
        }

        System.out.println("for each using lambda");
        names.forEach((name) -> System.out.println(name));

        System.out.println("for each using lambda method reference\t");
        names.forEach(TODO use method reference);
    }
}
```