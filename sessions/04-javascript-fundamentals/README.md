# Instructor Guide: Session 04 - JavaScript Fundamentals

## Session Overview
- **Module:** JavaScript Fundamentals
- **Topics:** Variables, Data Types, Control Flow (Logic), and Functions
- **Duration:** 3 Hours (180 Minutes)
- **Goal:** Move from static "markup" to dynamic "programming."

---

## Hour 1: The "Engine" (Variables & Data Types)
**Focus:** Memory, storage, and the building blocks of data.

### Key Concepts
1. **Declaration Keywords:**
   - `const`: For values that stay the same (Default).
   - `let`: For values that change (Counters, toggles).
2. **Primitive Data Types:**
   - `String`: Text (wrapped in quotes).
   - `Number`: Integers and decimals.
   - `Boolean`: `true` or `false`.
3. **Complex Data Types:**
   - `Array`: Ordered lists `[item1, item2]`.
   - `Object`: Key-value pairs `{ name: "Gemini", age: 1 }`.



### Live Demo (15-20m)
- Open Chrome DevTools (`Inspect` > `Console`).
- **Activity:** Create a "User Profile" variable that stores a Name (String), Age (Number), and isStudent (Boolean).
- **Check:** Use `typeof` to show the browser identifying these types.

---

## Hour 2: The "Brain" (Control Flow & Logic)
**Focus:** Decisions and repetition.

### Key Concepts
1. **Strict Equality (`===`):** Explain that `==` is "loose" (converts types) while `===` is "strict" (checks type and value). Always use `===`.
2. **Conditionals:**
   - `if / else if / else` structure.
3. **Logical Operators:**
   - `&&` (AND): Both must be true.
   - `||` (OR): One must be true.
4. **Loops:**
   - The `for` loop: `for (let i = 0; i < 10; i++)`.



### Live Demo (15-20m)
- **Activity:** Write a "Ticket Price" logic. 
  - If age < 12, price = $5.
  - If age > 65, price = $7.
  - Else, price = $10.
- **Loop Challenge:** Use a for-loop to print numbers 1 to 5 to the console.

---

## Hour 3: The "Factory" (Functions & Scope)
**Focus:** Reusability and organized code.

### Key Concepts
1. **The Function Anatomy:**
   - `Parameters`: The "inputs" (ingredients).
   - `Body`: The "logic" (the recipe).
   - `Return`: The "output" (the finished dish).
2. **Arrow Functions:** Introduce the modern syntax: `const myFunc = () => { ... }`.
3. **Scope:** Explain that variables created inside a `{}` block are invisible outside of it.



### Final Lab: The "Smart Greeting App" (30m)
**Instructions for Students:**
1. Create a function called `getGreeting`.
2. It should take two parameters: `userName` and `hour` (using 24-hour time).
3. Use an `if/else` block to return "Good morning," "Good afternoon," or "Good evening" followed by the `userName`.
4. Call the function and `console.log` the result.

---

## Summary Slide: Key Takeaways
- **Data Storage:** Always start with `const`. Only use `let` if the value changes.
- **Type Safety:** Be careful adding numbers to strings!
- **Branching:** Use `if/else` to make your code "smart."
- **DRY Principle:** "Don't Repeat Yourself." If you write the same code twice, make it a function.

---

## Common Student Pitfalls (Troubleshooting)
- **Missing Quotes:** Writing `let name = Gemini;` instead of `let name = "Gemini";`.
- **Assignment vs. Equality:** Using `=` (sets a value) instead of `===` (compares a value).
- **Scope Errors:** Trying to log a variable outside the function where it was created.
- **Forgetting the `return`:** Functions that do work but don't "give back" a result.

---

## Next Step
**Next Module:** DOM Manipulation (Connecting this JS logic to our HTML/CSS).
