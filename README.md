# poc-functional-interfaces

Proof of concept project demonstrating Java functional interfaces from `java.util.function` with practical examples.

## What this project covers

The application contains runnable examples of:

- Custom `@FunctionalInterface` (`DiscountPolicy`)
- `Predicate` and predicate chaining (`and`, `or`, `negate`, `Predicate.not`)
- `Function` composition (`andThen`, `compose`)
- `Supplier`
- `Consumer` and `andThen`
- `UnaryOperator`
- `BiFunction`
- `BinaryOperator`
- Streams pipeline using functional interfaces
- `Comparator` composition (`thenComparing`)
- `BiConsumer`
- `Optional` chaining

Main class: `com.michael.poc.Main`

## Requirements

- Java 21+
- Maven 3.9+

## Run

From the repository root:

```bash
mvn clean compile exec:java
```

## Build

```bash
mvn clean verify
```

## Project structure

```text
src/main/java/com/michael/poc/Main.java
```

## Notes

- Logging is done with SLF4J (`slf4j-simple` runtime).
- Examples print output to the console.
