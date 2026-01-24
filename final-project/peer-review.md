# Peer Review Rubric
Here is a professional Peer Review Rubric. This is designed to be used in the final session (Session 09), allowing students to evaluate each other’s work through the lens of a "Senior Developer" or "Hiring Manager."

This rubric ensures that the OQF standards (Professional Capacity, Methodology, and Autonomy) are measured objectively.

## Final Project Peer Review Rubric
Reviewer: ____________________ | Project Owner: ____________________

1. Technical Functionality (The "Does it Work?" Test)

| Criteria         | Excellent (5)                                           | Satisfactory (3)                                         | Needs Work (1)                                   |
|------------------|----------------------------------------------------------|-----------------------------------------------------------|--------------------------------------------------|
| API Integration  | Projects fetch perfectly from GitHub/External source.    | Data is present but lacks loading states or error handling.| Projects are hard-coded in HTML.                 |
| Search/Filter    | Real-time filtering is smooth and case-insensitive.      | Search works but requires exact case or is buggy.          | Search bar exists but does not function.         |
| Form Validation  | Prevents empty/invalid submissions with clear user feedback.| Form submits but validation is weak or alerts are used. | No validation; form allows empty submissions.    |

2. UI/UX & Responsive Design

| Criteria        | Excellent (5)                                                                 | Satisfactory (3)                                                      | Needs Work (1)                                                   |
|-----------------|-------------------------------------------------------------------------------|------------------------------------------------------------------------|------------------------------------------------------------------|
| Responsiveness  | Flawless on Mobile, Tablet, and Desktop. No horizontal scroll.                | Works on mobile but some elements overlap or look "off."              | Broken on mobile; requires zooming or horizontal scrolling.      |
| Navigation      | Global Navbar is identical and functional on all pages.                       | Nav exists on all pages but has broken links or styling gaps.          | Navbar missing on some pages or links are broken.                |
| Aesthetics      | Professional color palette, clear typography, and consistent spacing.        | Site is readable but lacks visual "polish" or hierarchy.              | Default browser styles used; poor contrast or unreadable text.   |

3. Professional Workflow (The GitHub Audit)

| Criteria         | Excellent (5)                                                              | Satisfactory (3)                                                      | Needs Work (1)                                               |
|------------------|-----------------------------------------------------------------------------|------------------------------------------------------------------------|--------------------------------------------------------------|
| GitHub Issues     | Issues used to track all features; issues are closed via commits.           | Issues exist but are mostly empty or were all closed at once.          | No GitHub Issues found.                                      |
| Commit History    | 10+ atomic commits with clear messages (feat:, fix:, docs:).                | Fewer than 10 commits or vague messages ("updated code").              | 1 or 2 giant commits ("final project").                      |
| Documentation     | README includes project description, tech stack, and live link.            | README exists but is missing key information.                          | README is the default "Hello World" or blank.                |

4. Security & Best Practices

| Criteria    | Excellent (5)                                      | Satisfactory (3)                                             | Needs Work (1)                                           |
|-------------|-----------------------------------------------------|----------------------------------------------------------------|----------------------------------------------------------|
| Data Safety | Uses .textContent for DOM injection. Live HTTPS URL.| Site is HTTPS but uses .innerHTML for user-controllable data. | Site is HTTP only or has visible console errors.         |

## Reviewer Feedback
One thing I loved: __________________________________________________________________

One technical suggestion for improvement: ___________________________________________

A "Stretch Goal" for the future: _____________________________________________________
