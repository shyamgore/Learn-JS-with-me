# Scoping in javaScript
Scoping in JS refers to the accessibility of veriables, funtions, and objects in some particular part of your code during runtime.
## Types of Scope in JavaScript
1. **Global Scope:**
   - Variables declared outside any function or block have global scope. 
   - They can be accessed from anywhere in the code.
   - Example:
     ```javascript
     var globalVar = "I am global";

     function showGlobal() {
         console.log(globalVar); // Accessible here
     }

     showGlobal();
     console.log(globalVar); // Accessible here too
     ```
2. **Local Scope:**
    Local scope refers to variables declared within a function and block of code. So we have two types of local scope:
   - **Function Scope**
     Example:
     ```javascript
        function myFunction() {
            var functionVar = "I am local to this function";
            console.log(functionVar); // Accessible here
        }
        myFunction();
        console.log(functionVar); // Error: functionVar is not defined  
        ```
   - **block Scope**
        Example:
        ```javascript
            {
                let blockVar = "I am local to this block";
                console.log(blockVar); // Accessible here
            }
            console.log(blockVar); // Error: blockVar is not defined  
            ```
3. **Lexical Scope:**
   - Lexical scope means that a function's scope is determined by its physical location in the source code. This will we study in detail when we will learn about closures.