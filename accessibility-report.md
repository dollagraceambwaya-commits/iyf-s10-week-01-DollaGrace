# Accessibility Audit Report

## Issues Found
- WAVE flagged an alert: "No page regions" — the page did not use semantic landmarks like <main>, <header>, or <footer> to define structure.
- Heading hierarchy not consistent (only h1 used, added h2).
- Image had alt text but no associated label.
- 

## Fixes Applied
- Kept one <h1> for the page title and added <h2> headings for Interests, Favorite Website, and Contact sections.
- Added a <label> linked to the profile image to demonstrate label usage.
- Added a <main> element to wrap the core content of page, resolving WAVE’s “No page regions” alert.
- This resolved the "No page regions" alert by providing a semantic landmark for assistive technologies, improving navigation for screen readers.

## Final Lighthouse Accessibility Score
Accessibility: 100/100

## Final WAVE AIM Score 
Accessibility: 10/10



