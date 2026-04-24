# Day 1 - Student Grade Calculator (Java)
"A simple Java program to calculate student grades based on input marks using conditional statements."

## 📌 Description
This program takes student marks as input and assigns a grade.

## 🧠 Concepts Used
- If-else statements
- User input (Scanner)

## 💻 Code

```java
import java.util.Scanner;

public class GradeCalculator {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int marks = sc.nextInt();

        if (marks >= 90)
            System.out.println("A");
        else
            System.out.println("B");

        sc.close();
    }
}
```

## ▶️ Sample Output
Enter marks: 85  
Grade: B
