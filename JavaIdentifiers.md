
# Java Identifiers

## ✅ What is an Identifier?

An **identifier** is the name used for:
- Classes
- Methods
- Variables
- Packages
- Interfaces
- Enums, etc.

---

## 🎯 Rules for Valid Identifiers

| Rule | Description |
|------|-------------|
| 1    | Must begin with a **letter (A–Z or a–z)**, **dollar sign `$`**, or **underscore `_`** |
| 2    | Subsequent characters can be **letters**, **digits (0–9)**, `$`, or `_` |
| 3    | **Cannot begin with a digit** (e.g., `1name` is invalid) |
| 4    | **Cannot be a Java keyword or reserved word** (e.g., `class`, `int`, `static`) |
| 5    | **No spaces** or special characters like `@`, `#`, `%`, etc. |
| 6    | Java identifiers are **case-sensitive** (`Variable` ≠ `variable`) |

---

## ✅ Examples of Valid Identifiers

- `myVar`
- `_name`
- `$amount`
- `employee123`
- `MAX_SIZE`

---

## ❌ Examples of Invalid Identifiers

| Identifier    | Reason                      |
|---------------|-----------------------------|
| `123name`     | Starts with a digit         |
| `void`        | Java keyword                |
| `user-name`   | Contains invalid character `-` |
| `first name`  | Contains a space            |

---

## 💡 Best Practices

- Use **camelCase** for variables and methods: `myVariable`, `calculateSum()`
- Use **PascalCase** for class names: `EmployeeDetails`
- Avoid starting identifiers with `_` or `$` unless required by conventions or frameworks
- Choose **meaningful names** that describe purpose

---

## 📌 Reserved Keywords (Cannot Be Used)

Some Java keywords include:  
`class`, `public`, `void`, `static`, `int`, `if`, `else`, `new`, `return`, `try`, `catch`, `final`, etc.

---
