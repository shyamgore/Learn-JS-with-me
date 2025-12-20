## JavaScript Operators

1. **Arithmetic Operators**: Used for mathematical calculations.
   - `+` (Addition)
   - `-` (Subtraction)
   - `*` (Multiplication)
   - `/` (Division)
   - `%` (Modulus)
   - `++` (Increment)
   - `--` (Decrement)
2. **Comparison Operators**: Used to compare two values.
   - `==` (Equal to)    
   - `===` (Strict equal to checks value and type)
   - `!=` (Not equal to)
   - `!==` (Strict not equal to checks value and type)
   - `>` (Greater than)
   - `<` (Less than)
   - `>=` (Greater than or equal to)
   - `<=` (Less than or equal to)
   - `? :` (Ternary operator)

3. **Logical Operators**: Used to combine multiple conditions.
   - `&&` (Logical AND)
   - `||` (Logical OR)
   - `!` (Logical NOT)
4. **Assignment Operators**: Used to assign values to variables.
   - `=` (Assignment)
   - `+=` (Add and assign)
   - `-=` (Subtract and assign)
   - `*=` (Multiply and assign)
   - `/=` (Divide and assign)
   - `%=` (Modulus and assign)
5. **Bitwise Operators**: Used to perform bit-level operations.
   - `&` (AND)
   - `|` (OR)
   - `^` (XOR)
   - `~` (NOT)
   - `<<` (Left shift)
   - `>>` (Right shift)
   - `>>>` (Unsigned right shift)
6. **Comma Operator**: Used to separate multiple expressions.
   - `,` (Comma)
   - Comma Operator (,) mainly evaluates its operands from left to right sequentially and returns the value of the rightmost operand. 



    ```js
    let n1, n2
    const res = (n1 = 1, n2 = 2, n1 + n2);
    console.log(res);
    ```
    ### Output:
    ```
    3
    ```
 
   - Each expression is evaluated from left to right.
   - The final result of the expression is the rightmost value.
  
7.**unary Operators:**
   
Operate on a single operand.

    - `typeof` (Returns the type of a variable)
    - `void` (Evaluates an expression and returns undefined)
    - `delete` (Deletes a property from an object)
