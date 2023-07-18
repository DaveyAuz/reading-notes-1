# Read: Class 07

## How do you inherit behavior from another class?

In Java, you can inherit behavior from another class by using the keyword "extends" in the class declaration. This establishes an "is-a" relationship between the derived class (subclass) and the base class (superclass). The subclass inherits all the non-private fields and methods of the superclass, allowing it to reuse and build upon the existing functionality.

Here's an example of how to inherit behavior from another class in Java:

```java
public class SuperClass {
    public void someMethod() {
        System.out.println("This is a method from the superclass.");
    }
}

public class SubClass extends SuperClass {
    // Additional methods and fields specific to the subclass
}

public class Main {
    public static void main(String[] args) {
        SubClass sub = new SubClass();
        sub.someMethod(); // Output: "This is a method from the superclass."
    }
}
```
In this example, the SubClass extends the SuperClass. As a result, the SubClass inherits the someMethod() from the SuperClass, and it can invoke that method using an instance of the subclass.





