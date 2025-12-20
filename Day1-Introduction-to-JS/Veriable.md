## JavaScript Veriables
Declaring Variables in JavaScript
- Before ES6 (2015): Variables were declared only with var, which is **function-scoped** and **global-scoped**, causing issues like **hoisting** and **global pollution.**
- ES6 Introduction: **let** and **const** were introduced to provide safer alternatives for declaring variables.
- **Scope**: let and const are **block-scoped** (limited to { } block) JavaScript or **global-scoped**, reducing errors compared to var.
- var is **function scoped**: Can be accessed **outside block** if within the function.
- var can be redeclared in the same scope, but let and const cannot be

| Feature | var | let | const |
|------|-----|-----|-------|
| Scope | Function-scoped | Local-scoped | Local-scoped |
| Hoisting | Yes (initialized as `undefined`) | Yes (temporal dead zone) | Yes (temporal dead zone) |
| Redeclaration | Allowed | Not allowed | Not allowed |
| Reassignment | Allowed | Allowed | Not allowed |
| Initialization Required | No | No | Yes |
| Global Object Binding | Yes (`window.varName`) | No | No |
| Use Case | Legacy code | Mutable variables | Constants / fixed references |
