# 📋 GitHub Issues Template: Portfolio Project

Copy and paste these into your GitHub repository under the "Issues" tab to track your progress.

---

### 🟢 Issue 1: Project Setup & Architecture
**Title:** `task: Initialize repository and multi-page structure`  
**Description:** - Initialize a local Git repository and connect to GitHub.  
- Create three HTML files: `index.html`, `projects.html`, and `contact.html`.  
- Create a global `style.css` and a `shared.js` file.  
- Link all files and verify they are connected in the browser console.  
**Labels:** `setup`, `high-priority`

---

### 🟢 Issue 2: Shared Navigation & Layout
**Title:** `feat: Build responsive navigation and footer`  
**Description:** - Build a navigation bar that is consistent across all 3 pages.  
- Implement a "Hamburger Menu" for mobile screens (max-width: 768px).  
- Create a shared footer with social links and copyright info.  
- Use CSS Variables for the color palette and typography.  
**Labels:** `ui/ux`, `css`

---

### 🟢 Issue 3: Deployment Pipeline
**Title:** `ops: Connect to Vercel for Continuous Deployment`  
**Description:** - Import GitHub repository into Vercel.  
- Verify the build settings.  
- Ensure every push to the `main` branch triggers a new deployment.  
- Add the Live URL to the GitHub repository "About" section.  
**Labels:** `deployment`



---

### 🟢 Issue 4: Dynamic Project Gallery (GitHub API)
**Title:** `feat: Fetch and render live projects from GitHub API`  
**Description:** - Create a JavaScript function to fetch repository data from `https://api.github.com/users/YOUR_USERNAME/repos`.  
- Map through the data and use Template Literals to create cards.  
- Inject the cards into the `projects.html` gallery container.  
- Add a loading spinner or "loading..." text while the data is fetching.  
**Labels:** `javascript`, `api`



---

### 🟢 Issue 5: Search & Filter Functionality
**Title:** `feat: Implement real-time search for projects`  
**Description:** - Add a search `<input>` to the gallery page.  
- Write an event listener to filter the fetched projects by name or language.  
- Ensure the gallery re-renders automatically as the user types.  
- Handle the "No results found" state.  
**Labels:** `javascript`, `logic`

---

### 🟢 Issue 6: Contact Form & Validation
**Title:** `feat: Contact form validation and submission handling`  
**Description:** - Build a form with Name, Email, and Message fields.  
- Write JavaScript validation to check for empty fields and valid email formats.  
- Prevent default form submission and show a "Success Message" in the DOM.  
- (Optional) Use `localStorage` to remember the user's name for a personalized thank you.  
**Labels:** `forms`, `javascript`

---

### 🟢 Issue 7: Documentation & Final Polish
**Title:** `docs: Complete README and final UI audit`  
**Description:** - Write a professional `README.md` with:
  - Project description.
  - Tech stack used.
  - Link to the live site.
- Perform a final responsive check (check mobile vs desktop).
- Ensure all console logs are removed for production.  
**Labels:** `documentation`
