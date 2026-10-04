# Assignment 3 — Responsive Web Design
**Name:** Alish Medina  
**Group:** SE-2538

This project demonstrates responsive web design using CSS Media Queries and the Bootstrap 5 Grid System. The final page is a small portfolio that adapts to desktop, tablet, and mobile screen sizes.

---

## Part 1 — Media Queries
### Task 0. Responsive Typography

Created a simple page with a heading and paragraphs. Font sizes change based on screen width using CSS media queries:

- Desktop (default): h1 = 42px, p = 20px
- Tablet (max-width: 991px): h1 = 32px, p = 18px
- Mobile (max-width: 599px): h1 = 26px, p = 16px

Desktop view:
<img width="1920" height="1080" alt="Снимок экрана 2026-10-04 183201" src="https://github.com/user-attachments/assets/27c1a729-7148-4359-ba76-9c8e495ff49d" />

Mobile view:
<img width="645" height="987" alt="Снимок экрана 2026-10-04 183234" src="https://github.com/user-attachments/assets/a2b45553-8dc2-4396-83d9-6ced6b07fb8d" />

---

### Task 1. Responsive Layout with Media Queries

Created three boxes using pure CSS flexbox (no Bootstrap). The layout changes with screen size:

- Desktop: all three boxes side by side
- Tablet (max-width: 991px): two boxes per row
- Mobile (max-width: 599px): boxes stacked vertically

Desktop view:
<img width="1917" height="566" alt="Снимок экрана 2026-10-04 183318" src="https://github.com/user-attachments/assets/194cc718-b0f2-4a27-b1d3-b37864a70efe" />

Tablet view:
<img width="1006" height="688" alt="Снимок экрана 2026-10-04 183341" src="https://github.com/user-attachments/assets/a3a1d62c-ecf1-435a-8aa2-06308f501850" />

Mobile view:
<img width="587" height="812" alt="Снимок экрана 2026-10-04 183413" src="https://github.com/user-attachments/assets/38696a76-0e4f-4e67-ad42-507c14862881" />

---

## Part 2 — Bootstrap Grid System
### Task 2. Bootstrap Responsive Columns

Built a three-column layout using Bootstrap's 12-column grid:

- Mobile: col-12, each column takes the full width (stacked)
- Tablet (md): col-md-6, 2 columns per row, third wraps to a second row
- Desktop (lg): col-lg-4, 3 equal columns per row

Desktop view:
<img width="1917" height="566" alt="Снимок экрана 2026-10-04 183318" src="https://github.com/user-attachments/assets/200a9fee-31ad-4213-96da-7a66663b1d35" />

Tablet view:
<img width="1006" height="688" alt="Снимок экрана 2026-10-04 183341" src="https://github.com/user-attachments/assets/57eef9d1-56aa-49f0-a558-c1b8a1d2bec3" />

Mobile view:
<img width="587" height="812" alt="Снимок экрана 2026-10-04 183413" src="https://github.com/user-attachments/assets/152c20c8-6411-4f4e-8a71-4467505ff06c" />

---

### Task 3. Bootstrap Navigation Bar

Created a responsive navbar using Bootstrap components:

- Logo on the left
- Links pushed to the right with ms-auto
- Collapses into a hamburger menu on small screens using navbar-toggler with data-bs-toggle and data-bs-target

Expanded view:
<img width="1883" height="306" alt="Снимок экрана 2026-10-04 184313" src="https://github.com/user-attachments/assets/b53fcab4-fa25-439b-9b98-52c03c556a28" />


Collapsed with hamburger view:
<img width="598" height="221" alt="Снимок экрана 2026-10-04 184318" src="https://github.com/user-attachments/assets/64578e1d-54ce-4174-b976-fd339be3e623" />


---

## Part 3 — Combined Project
### Task 4. Responsive Portfolio Page

Combined media queries and the Bootstrap Grid into a single portfolio page.

Structure:

1. Header — Bootstrap navbar with logo, links, and hamburger toggle
2. Home section — intro text with responsive typography
3. Boxes section — three boxes using pure CSS flexbox with media queries
4. Skills section — Bootstrap grid (col-12 col-md-6 col-lg-4)
5. Main section — split using Bootstrap grid: left side (col-12 col-lg-8) with project cards, right side (col-12 col-lg-4) with sidebar info
6. Footer — contact info across the bottom

Desktop view:
<img width="1812" height="872" alt="Снимок экрана 2026-10-04 184424" src="https://github.com/user-attachments/assets/b86a56e6-8a43-4d00-b834-320bd1fd6143" />

Tablet view:
<img width="977" height="826" alt="Снимок экрана 2026-10-04 184434" src="https://github.com/user-attachments/assets/6dc21d4b-61fe-4fe4-aa7c-a3419d2227c7" />

Mobile view:
<img width="712" height="847" alt="Снимок экрана 2026-10-04 184521" src="https://github.com/user-attachments/assets/03ad32da-8739-4cc4-882c-86765f79e712" />

---

## Summary
In this assignment I practiced two ways of making a page responsive. First, CSS media queries, where I wrote my own breakpoints at 991px and 599px to change font sizes and box layouts. Second, the Bootstrap Grid, where I used pre-built responsive classes like col-12 col-md-6 col-lg-4 to control how columns stack at different screen sizes, plus the collapsible navbar component. I learned that Bootstrap is basically media queries packaged into reusable class names, and that combining both approaches gives the most control. I also practiced using flex with calc() to make the pure-CSS boxes reflow correctly at each breakpoint.

---

## Files
- index.html
- style.css
- project images (4 jpg files)
- README.md
- screenshots/ folder

---

## How to Run
1. Clone or download the repository
2. Open index.html in any browser
3. Resize the window or use Chrome DevTools Device Toolbar to see the responsive behavior
