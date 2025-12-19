# Introduction to JavaScript

Modern JavaScript engines like **V8 (Chrome, Node.js)** do this:

- First: interpret your code
- Then: Just-In-Time (JIT) compile hot parts for speed

So technically:

- **Conceptually** : interpreted
- **Practically** : interpreted + JIT compiled
  
# Sever side JavaScript and Clint side JavaScript
## Sever side JavaScript
Browser sends a request to the server
Server responds with:

- HTML

- CSS

- JavaScript files

The JavaScript runs in the client’s browser
  e.g., app.js
 That app.js is downloaded from the server
 executed inside the browser

This is called client-side JavaScript.
 ## Clint side JavaScript
- JS does NOT run in the browser
- JS runs on the server itself
- Browser never sees that JS code
- This is server-side JavaScript.
Node.js and frameworks like Express.js are widely used for server-side JavaScript, enabling full-stack development.

## Limitations of JavaScript
- Security Risks : Can be used for attacks like Cross-Site Scripting (XSS), where malicious scripts are injected into a website to steal data by exploiting elements like 
  ```html
  <img>
  <object>
  <script> 
  tags
  ```
  
- Performance : Slower than traditional languages for complex tasks, but for simple tasks in a browser, performance is usually not a major issue.
- Complexity : To write advanced JavaScript, programmers need to understand core programming concepts, objects, and both client- and server-side scripting, which can be challenging.
- Weak Error Handling and Type Checking : Weakly typed, meaning variables don’t require explicit types. This can lead to issues as type checking is not strictly enforced

## JavaScript Versions

| Version | Year | Key Features |
|--------|------|--------------|
| ES5 | 2009 | strict mode, JSON, getters/setters |
| ES6 | 2015 | let/const, classes, arrow functions |
| ES7–ES13 | 2016–2022 | async/await, BigInt, optional chaining |
| ES14 | 2023 | toSorted, findLast, static blocks |

