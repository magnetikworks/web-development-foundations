# Assignment 2: The Interactive Project Gallery
## Web Development Foundations
1. **Goal** To demonstrate Application of Knowledge by using JavaScript to dynamically render UI components and implement user interactivity. You will transform your static "Project Cards" into a functional, searchable gallery.
2. **Requirements** You will build upon the CSS styles created in Assignment 1. Your task is to replace hard-coded HTML cards with a JavaScript-driven system.
    1. The Data Structure
       - Create a JavaScript Array of Objects named myProjects.
       - Each object must represent a project and include properties for:
         - title (String)
         - description (String)
         - category (e.g., "Frontend", "UI Design")
         - image (URL String)
         - link (URL String)

    2. Dynamic Rendering (DOM Manipulation)
       - Remove the hard-coded cards from your HTML.
       - Write a JavaScript function (e.g., renderProjects) that:
         - Iterates through the myProjects array.
         - Uses Template Literals (backticks `) to create the HTML structure for each card.
         - Injects the resulting HTML into a specific container in your DOM using innerHTML or appendChild.

    3. The Search/Filter Feature
       - Add an `<input>` field to your page for searching.
       - Write an Event Listener for the input event.
       - As the user types, the gallery must filter the projects in real-time, showing only those where the title or category matches the search query.

    4. Professional Workflow (Console & Debugging)
       - Use `console.log()` to verify your data is being filtered correctly.
       - Ensure there are no JavaScript errors in the browser console.
