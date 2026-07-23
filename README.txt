UPDATED VERSION OF YOUR ORIGINAL PORTFOLIO

This version keeps your original portfolio design/content but cleans the code.

Main fixes:
1. Corrected HTML <head> structure.
2. Removed duplicate Bootstrap Icons import and unused Django static Font Awesome line.
3. Fixed IDs: HOME/ABOUT ME/SKILS/CONTACT -> home/about/skills/contact.
4. Fixed all navbar and footer anchor links.
5. Fixed About button link.
6. Changed the absolute Windows image path to ./css/img/img8.png.
7. Removed nested repeated classes such as class="dish-card header1".
8. Replaced five separate progress-line classes with one reusable .progress-line class.
9. Separated hero and footer social icon classes to prevent CSS conflicts.
10. Removed invalid CSS such as border-box:fixed, box-sizing:fixed, font-weight:300px/500px.
11. Removed fixed heights that were breaking responsive layouts.
12. Added responsive breakpoints:
    - Desktop: default
    - Tablet/small laptop: 769px–1024px
    - Mobile: up to 768px
    - Small mobile: up to 480px

IMPORTANT:
Keep your images at:
css/img/img7.png
css/img/img8.png

Files:
index.html
css/pro.css
