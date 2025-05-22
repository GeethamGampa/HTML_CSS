# Personal Webpage - Geetham Gampa

This is a personal webpage created using **HTML5** and **CSS** to showcase my profile, skills, and projects.

##  What I Did (Step by Step)

### 1. Created the `index.html` file

- Used `<!DOCTYPE html>` to declare the HTML5 version.
- Added `<head>` with:
  - Page title (`Geetham Gampa | Personal Webpage`)
  - Link to the external CSS file using `<link rel="stylesheet" href="style.css">`


### 2. Built the Webpage Sections

#### Header
```html
<header>
  <h1>Geetham Gampa</h1>
  <p><strong>Welcome To My Personal Webpage</strong></p>
</header>
```
- shows my name and welcome message.

#### Navigation Bar
```html
<nav>
  <ul>
    <li><a href="#projects">My Projects</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>
```
- Links to Projects and Contact sections.

#### About Me Box
```html
<div class="box">
  <h2>About Me</h2>
  <p>...</p>
</div>
```
- Used a box class in CSS for yellow background and styling.
- Wrote about my interests and goals.

#### Added Projects Section
```html
<div class="portfolio">
  <div class="project">...</div>
  <div class="project">...</div>
  <div class="project">...</div>
</div>
```
- Each .project box has a heading and bullet points.
- Used Flexbox with .portfolio to align projects side by side.
- Added 3 projects: Personal Website, Library System, E-commerce Site.

#### Added Skills Table
```html
<table border="2">
  <thead><tr><th>Skill</th>...</tr></thead>
  <tbody><tr><td>Python</td>...</tr></tbody>
</table>
```
- Simple table showing skills, experience level, and tools.

#### Listed My Hobbies
```html
<ul>
  <li>Learning new technologies</li>
  <li>Building small projects</li>
  <li>Reading about AI and innovation</li>
</ul>
```

#### Added Two More Boxes (Learning & Goals)
```html
<div class="box2">...</div>
<div class="box3">...</div>
```
- Styled with different background colors using .box2 and .box3 classes.

#### Used a Container for Extra Info
```html
<div class="container">
  <div>...</div>
  <div>...</div>
</div>
```
- Flex container showing two boxes side by side.
- Changed to column layout on small screens using media query.

#### Contact Form
```html
<form>
  <label for="name">Your Name:</label>
  <input type="text" id="name" name="name" required>
</form>
```
- A simple form with name, email, and message fields.

####  Added My Photo
```html
<img src="1.jpg" alt="Geetham's Photo" width="250">
```

####  Wrote CSS in style.css
- Styled each section: .box, .project, .portfolio, .container, etc.
- Used Flexbox for alignment.
- Used media queries for responsive layout:
```html
@media (max-width: 600px) {
  .container {
    flex-direction: column;
    align-items: center;
  }
}
```


#### What I Learned
- How to structure a personal webpage using HTML
- How to use Flexbox to arrange content side by side
- How to use media queries for mobile responsiveness
- How to style boxes, tables, and form elements using CSS
