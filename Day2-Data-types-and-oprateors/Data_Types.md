# JavaScript Data Types

```

                             Data Types in JavaScript
                                    |
          ┌─────────────────────────┴──────────────────────────┐
          |                                                    |
   Primitive Data Types                                  Non-Primitive Data Types
          |                                                    |
   ┌──────┴─────────┐                               ┌──────────┴───────────┐
   |                |                              |      |        |       |
Numeric Type   Non-Numeric Type                   Object Array Function Date Object RegExp
   |                |
 ┌─┴─┐      ┌───────┴───────┐
 |     |     |      |     |     |
Number BigInt String Boolean Null Undefined Symbol
````
## Primitive Data Type
Primitive data types in JavaScript represent simple, immutable values stored directly in memory, ensuring efficiency in both memory usage and performance.
### Types of Primitive Data Types
1. **Nuberic Type:**
   - **Number:** Represents both integer and floating-point numbers. Example: `42`, `3.14`
   - **BigInt:** Represents integers with arbitrary precision, allowing for very large numbers. Example: `9007199254740991n`
2. **Non-Numeric Type:**
   - **String:** Represents sequences of characters used for text. Example: `"Hello, World!"`
   - **Boolean:** Represents logical values, either `true` or `false`. Example: `true`
   - **Null:** Represents the intentional absence of any object value. Example: `null`
   - **Undefined:** Represents a variable that has been declared but not assigned a value. Example: `undefined`
   - **Symbol:** Represents a unique identifier, often used as object property keys. Example: `Symbol('description')`

## Non-Primitive Data Types
The data types that are derived from primitive data types are known as non-primitive data types. It is also known as derived data types or reference data types.
### Types of Non-Primitive Data Types
1. **Object:** A collection of key-value pairs, where keys are strings (or Symbols) and values can be of any data type. Example: `{ name: "Alice", age: 30 }`
2. **Array:** An ordered collection of values, which can be of any data type. Example: `[1, 2, 3, "four", true]`
3. **Function:** A block of code designed to perform a specific task, which can be invoked when needed. Example: `function greet() { return "Hello"; }`
4. **Date Object:** Represents dates and times, allowing for date manipulation and formatting. Example: `new Date()`
5. **RegExp:** Represents regular expressions, used for pattern matching within strings. Example: `/ab+c/`