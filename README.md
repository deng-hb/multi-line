## Multi-line

So easy

### Maven
```xml
<dependency>
    <groupId>com.denghb</groupId>
    <artifactId>multi-line</artifactId>
    <version>1.0.2</version>
</dependency>
```

### Example
```java
public class MultiLineTest {

    private static String A = ""/*{
        Hello World!
    }*/;

    public static void main(String[] args) {
        String a = ""/*{
            I'm multi-line
        }*/;
        System.out.println(A);
        System.out.println(a);
    }
}

```

### Test 
IntelliJ IDEA 2019.1.2 (Community Edition)

