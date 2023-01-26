# Combining Strings

## Learning Goals

- Use the `+` operator to concatenate `String` values.

## Introduction

Earlier, we learned about the `+` operator in the context of numbers. Let's now
see how we can use the `+` operator with `String` values.

## Combining Operator

The `+` operator can apply to text in Java. For example:

```java
String greeting = "Hello, ";
String name = "Maggie";
String message = greeting + name;
```

This would result in the variable `message` holding the value "Hello, Maggie".
For variables of type `String`, the `+` operator concatenates both sides of the
operator.

Now consider the following statement:

```java
System.out.println(greeting + name);
```

The expression `greeting + name` returns the value "Hello, Maggie", which is
then passed to the `println()` method, which prints it on the screen.

## Comprehension Check

Consider the following code:
```java
public class Main {
    public static void main(String[] args) {
        String stringOne = "Hello!";
        String stringTwo = "My name is ";
        String name = "Tom";
        
        System.out.println(stringOne + stringTwo + name);
    }
}
```

<details>
  <summary>What does the above program print out?</summary>

  <p>Answer:<br><code>Hello! My name is Tom</code></p>

  <p>Java will concatenate the three Strings together by using the `+` operand.</p>

</details>