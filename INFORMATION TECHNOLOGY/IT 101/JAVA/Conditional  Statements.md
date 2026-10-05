
## If, Else If, Else in Java

**1. `if`** — runs a block only if a condition is true.

java

```java
int age = 20;
if (age >= 18) {
    System.out.println("You are an adult.");
}
```

**2. `if-else`** — runs one block if true, another if false.

java

```java
int age = 15;
if (age >= 18) {
    System.out.println("You are an adult.");
} else {
    System.out.println("You are a minor.");
}
```

**3. `else if`** — checks multiple conditions in order.

java

```java
int score = 75;

if (score >= 90) {
    System.out.println("Grade: A");
} else if (score >= 75) {
    System.out.println("Grade: B");
} else if (score >= 60) {
    System.out.println("Grade: C");
} else {
    System.out.println("Grade: F");
}
```

#### Key rules

- Conditions must evaluate to `boolean` (`true`/`false`).
- Java checks conditions **top to bottom** and stops at the first `true` one.
- `else` is optional and always runs last, if nothing else matched.
- Curly braces `{}` are optional for single-line blocks but recommended for clarity.

#### Quick practice

java

```java
int num = 10;
if (num > 0) {
    System.out.println("Positive");
} else if (num < 0) {
    System.out.println("Negative");
} else {
    System.out.println("Zero");
}
```


java 
```java
public class HelloWorld {
	public static void main(String[] args){
	Systeem.out.println("Hello World!");
	}
}
```


## COVID TEST LOGIC-GATE

```java
import java.util.Scanner;

	public class cv19 {
		
	public static void main(String[] args){
		
	Scanner test = new Scanner(System.in);
		
	System.out.println("Testing for covid 19! PLEASE INPUT THE TEST RESULT: ");
		
	String bad = "positive";
		
	String good = "negative";
		
	String tested = test.nextLine().toLowerCase();
		
		
		
	if (tested.equals(good)) {
		
	System.out.println("Your test is negative further assistance is not required, please exit console.");
		
	} else if (tested.equals(bad)) {
		
	System.out.println("your test came back positive, further medical assistance access granted.");
		
	} else {
		
	System.out.println("Invalid Input.");
		
		}
	
	}
	
}
```


