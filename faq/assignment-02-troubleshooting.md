# Student Troubleshooting Guide: Assignment #2
## Project: The Interactive Project Gallery

This guide covers the most common "stuck points" when building the **Interactive Project Gallery**. Use this to debug your code before submitting.

---

### 1. "My Gallery is Empty!" (The Container Issue)
If your code runs but nothing shows up in the browser, check these two things:
* **The ID Match:** Ensure the ID in your HTML (e.g., `<div id="project-container"></div>`) matches your JavaScript selector exactly: `document.getElementById('project-container')`.
* **The Function Call:** A function is just a "recipe" until you cook it. Did you remember to call your function at the bottom of your script? 
  * *Example:* `renderProjects(myProjects);`



---

### 2. "Everything Disappears when I Search!"
This usually happens because you are filtering your data but not "re-painting" the screen correctly.
* **The Logic Flow:** Your search event listener needs to follow these steps:
    1.  Capture the text the user typed (`e.target.value`).
    2.  Create a new array by **filtering** the original `myProjects` array.
    3.  **Clear the old HTML content** inside your container (e.g., `container.innerHTML = "";`).
    4.  Call your `renderProjects` function again using the *new filtered array*.



---

### 3. "The Search is Too Strict" (Case Sensitivity)
If searching for "web" doesn't find a project titled "Web Development," it's because JavaScript treats "W" and "w" as different characters.
* **The Professional Fix:** Convert both the project property and the user's search query to lowercase before comparing them.
  * *Example:* `project.title.toLowerCase().includes(searchTerm.toLowerCase())`

---

### 4. "Error: 'Cannot read property of null'"
This is the #1 error for beginners. It means JavaScript is looking for an HTML element that doesn't exist yet.
* **The Fix:** Ensure your `<script src="app.js"></script>` tag is placed at the **very bottom of your HTML file**, just before the closing `</body>` tag. This ensures the HTML is loaded before the JS tries to find the gallery container.

---

## Checklist for an 'A' Grade (OQF Standards)

| Requirement | Why it matters |
| :--- | :--- |
| **Case-Insensitive Search** | **User Experience (UX):** Users expect search to be flexible. |
| **Template Literals** | **Modern Standards:** Backticks (`` ` ``) make code readable and maintainable. |
| **Zero Console Errors** | **Professionalism:** Shows you have debugged and tested your work. |
| **Commit History** | **Workflow:** Demonstrates an organized development process on GitHub. |

---

### 💡 Pro-Tip for the Lab
Use `console.table(myProjects)` instead of `console.log` to see your array of objects in a beautiful, readable grid inside your browser console!
