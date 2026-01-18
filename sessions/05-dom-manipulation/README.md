# Session 05 - DOM Manipulation

## Overview
In this session, students move from "Static Pages" to "Web Apps." Focus on the concept that JavaScript "listens" for user actions and "responds" by updating the DOM.

## Hour 1: Selecting & Changing
- **Key Visual:** The DOM Tree.
- **Teaching Tip:** Emphasize `querySelector` because it uses the same syntax as CSS selectors, which they already know.
- **Common Error:** Forgetting that `querySelectorAll` returns a list (NodeList), not a single element.

## Hour 2: The Event Listener
- **Key Concept:** The "Callback Function." JS doesn't run the code until the user clicks.
- **Live Demo:** Show why `e.preventDefault()` is needed on forms to stop the page from refreshing.

## Hour 3: Dynamic Elements
- **Logic:** `Create` -> `Configure` -> `Append`. 
- **Storage:** Briefly show `localStorage.setItem('key', 'value')`. This feels like "magic" to students.

## Summary Slide Points
1. **The DOM is a Map:** Use JS to find elements and change their properties.
2. **Events are Triggers:** Users interact (Click/Type), and JS reacts.
3. **Class Over Style:** Don't change `element.style.color`. Change `element.classList` and let CSS do the heavy lifting.
4. **Persistence:** Use `localStorage` to make your web apps remember user data.
