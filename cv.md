# Andrey Vasylyuk

## Contacts
E-mail:  AndreyVasylyuk@gmail.com
Discord: AndreyVasylyuk#8579

## About me


## Skills
* HTML
* CSS
* JavaScript
* Java
* SQL
* GitHub, GitLab
* Windows, Linux
* Intellij IDEA, VS Code, Eclipse IDE

## Code example
```
import java.util.HashMap;
import java.util.Map;
import java.util.Scanner;

class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String line = scanner.nextLine();

        Map<String, Integer> map = new HashMap<>();
        map = countWords(line);
        map.forEach((k, v) -> System.out.println(k + " " + v));
    }

    public static Map<String, Integer> countWords(String line) {
        Map<String, Integer> map = new HashMap<>();
        String[] stringLineArray = line.toLowerCase().split("\s+");
        for (String word : stringLineArray) {
            map.merge(word, 1, Integer::sum);
        }
        return map;
    }
}
```

## Courses
* CS50
* Hyperskill: SQL

## Education
Bachelor of Mathematics

## Languages
English - B2 (Intermediate level)
Polish - Basic
Ukrainian - Native