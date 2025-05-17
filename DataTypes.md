## Java Data Types: Primitive vs Non-Primitive

In Java, data types are broadly classified into two categories:

---

### ✅ Primitive Data Types

- Built-in types provided by the Java language.
- Store **simple values** (not objects).
- Fast and memory-efficient.
- Stored on the **stack**.

#### 🔹 Examples:

| Type     | Size     | Description                 |
|----------|----------|-----------------------------|
| `byte`   | 1 byte   | Small integer (−128 to 127) |
| `short`  | 2 bytes  | Medium integer              |
| `int`    | 4 bytes  | Standard integer            |
| `long`   | 8 bytes  | Large integer               |
| `float`  | 4 bytes  | Decimal (single precision)  |
| `double` | 8 bytes  | Decimal (double precision)  |
| `char`   | 2 bytes  | Single character (Unicode)  |
| `boolean`| ~1 bit   | `true` or `false`           |

---

### ✅ Non-Primitive Data Types

- Also called **reference types**.
- Can store **multiple values** and **methods** (like objects).
- Stored on the **heap**, with references on the stack.
- Can be `null`.
- Created using **classes**, **arrays**, **interfaces**, etc.

#### 🔹 Examples:
- `String`
- Arrays (`int[]`, `String[]`)
- User-defined classes (`MyClass`)
- Collections (`List`, `Map`, `Set`)
- Interfaces

---

### 🆚 Key Differences

| Feature             | Primitive           | Non-Primitive             |
|---------------------|---------------------|----------------------------|
| Memory              | Stack               | Heap                      |
| Nullability         | Cannot be `null`    | Can be `null`             |
| Methods             | No methods          | Can have methods          |
| Mutability          | Immutable           | Mutable (mostly)          |
| Example             | `int x = 10;`       | `String s = "Hello";`     |

---

> 🧠 **Tip**: Use primitives for performance-critical tasks, and non-primitives when you need objects or collections of data.




### 📊 Java Data Types Summary

| Type     | Size     | Typical Use Case               |
|----------|----------|--------------------------------|
| `byte`   | 1 byte   | Small numbers, binary data     |
| `short`  | 2 bytes  | Rare use, legacy or tight memory |
| `int`    | 4 bytes  | Default for integers           |
| `long`   | 8 bytes  | Large numbers, timestamps      |
| `float`  | 4 bytes  | Decimal numbers, less precision |
| `double` | 8 bytes  | Default for decimal numbers    |
| `boolean`| ~1 bit   | True/false flags               |
| `char`   | 2 bytes  | Single Unicode characters      |






## Why Choosing the Right Data Type Matters

Choosing the appropriate data type in Java (or any typed language) can significantly affect your application's performance, readability, and reliability.

---

### ✅ Memory Efficiency
- Using smaller types like `byte` or `short` reduces memory usage.
- Helps when dealing with large arrays or memory-constrained environments.
- Example: `byte` takes 1 byte vs `int` which takes 4 bytes.

---

### ✅ Performance
- Correct data types minimize type conversions and reduce runtime overhead.
- Prevents overflow and other arithmetic errors.
- Leads to faster execution in loops and calculations.
- Example: Using `long` instead of `int` for very large numbers avoids overflow.

---

### ✅ Code Clarity
- Data types express developer intent clearly (e.g., `boolean` for flags).
- Makes the code easier to read, understand, and maintain.
- Helps others quickly understand what kind of data is expected or stored.

---

### 🧠 Tip:
> Always use the smallest type that fits your data and use domain-appropriate types (e.g., `boolean` for true/false).



<a href="https://gist.github.com/igorbotian/ace3863672fb182c07ea88c57b355b98/">Click here for Java data types</a>

<a href="https://www.geeksforgeeks.org/data-types-in-java/">Click here for Java detailed data types</a>
