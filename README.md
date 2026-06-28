# Trevon Kiprop Korir — Developer Portfolio

A personal portfolio website built with HTML5, CSS3, and JavaScript, showcasing all projects completed during my web development course. The site is live and fully responsive.

🔗 **Live Site:** [trevonk-coder.github.io/myCV](https://trevonk-coder.github.io/myCV/)

---

## 📋 About This Site

This portfolio serves as my online CV and project showcase. It features:

- **Hero Section** — Introduction with status badge, title, and stats
- **Skills Section** — Technical stack organized by category (Languages, Frameworks, Databases, Tools)
- **Projects Section** — Cards linking to all course projects with descriptions and tech stacks
- **Experience Section** — Timeline of roles and responsibilities
- **Contact Section** — Links for reaching out

---

## 🚀 Course Projects

### HTML & CSS Projects

All HTML/CSS projects are hosted within the [`bootstrap4_project`](https://github.com/TrevonK-coder/bootstrap4_project) repository.

#### 1. Lumina Agency Landing Page — Bootstrap 4
**Live:** [trevonk-coder.github.io/bootstrap4_project](https://trevonk-coder.github.io/bootstrap4_project/)
**Folder:** `bootstrap4_project/` (root `index.html`)

A premium creative agency website built with Bootstrap 4, HTML5, CSS3, and JavaScript.
- Responsive navbar with collapsible mobile menu
- Bootstrap grid layout with cards for services and team members
- Stylized contact form with Bootstrap validation
- Custom CSS animations and Google Fonts integration

---

#### 2. The Space Station — Gallery Page
**Folder:** `bootstrap4_project/Project/`

A themed resort website for a fictional space station featuring an image gallery.
- Sticky navigation with Home, Gallery, and Reservations links
- Responsive CSS Grid photo gallery with 9 space-themed thumbnails
- Semantic HTML5 structure with `<nav>` and `<footer>`

---

#### 3. One-Page Website
**Live:** [trevonk-coder.github.io/bootstrap4_project/One-Page%20Website/one_page_website.html](https://trevonk-coder.github.io/bootstrap4_project/One-Page%20Website/one_page_website.html)
**Folder:** `bootstrap4_project/One-Page Website/`

A complete single-page website with a functional lightbox image gallery.
- Sticky navbar with anchor links (`#home`, `#gallery`, `#video`, `#contact`)
- **Lightbox modal gallery** — click any thumbnail to open full-size view with prev/next navigation, keyboard support (← → Esc), and backdrop-click to close
- Embedded YouTube `<iframe>` video
- Contact form with name, email, and message fields

---

#### 4. Basic HTML & CSS Exercises
**Folder:** `bootstrap4_project/Basic_HTML_and_CSS/`

Foundational exercises covering core HTML and CSS concepts.

| File | Topic |
|---|---|
| `Basic_HTML_3.html` – `Basic_HTML_5.html` | HTML document structure and elements |
| `HTML_Table.html` + `CSS_Table.css` | HTML tables and table styling |
| `HTML_Lists.html` + `CSS_Lists.css` | Ordered and unordered lists |
| `form_assignment.html` | HTML forms with inputs and labels |
| `Basic_CSS_1.css` + `Basic_CSS_2.css` | CSS selectors, properties, and the box model |

---

### JavaScript Projects

All JavaScript projects are hosted in the [`JavaScript-Projects`](https://github.com/TrevonK-coder/JavaScript-Projects) repository.

#### 5. JS Expressions & Alert — Project 1
**Folder:** `JavaScript-Projects/Basic JavaScript Projects/Project1_expressions_alert/`

An interactive page demonstrating core JavaScript output methods and expressions.
- `window.alert()` popup on page load
- `document.write()` output to the page
- Two string variables (`Sent1`, `Sent2`) concatenated with `+`
- Arithmetic expressions: PEMDAS, modulus (`%`), exponentiation (`**`), boolean
- Live calculator with operator select and real-time output
- Live string builder updating via `addEventListener`
- External JS linked with `<script src="main.js">`

---

#### 6. JS Functions & += Operator — Project 2
**Folder:** `JavaScript-Projects/Basic JavaScript Projects/Project2_functions/`

A four-section interactive app demonstrating JavaScript functions and the `+=` operator.
- **Score Tracker** — `addScore(points)` accumulates total with `currentScore += points`
- **Sentence Builder** — `addWord()` grows a string with `sentence += " " + word`
- **Shopping Cart** — `addItem()` builds running total with `cartTotal += itemPrice`
- **Multiplication Table** — `buildTable()` assembles HTML string with `tableHTML +=` in nested loops
- HTML elements (`<button onclick="...">`) call and display each function
- Object literals, arrays, `parseFloat()`, `parseInt()`, `isNaN()` for input validation

---

### C# & .NET Core Projects

All C# console and web applications are hosted in the [`c-projects`](https://github.com/TrevonK-coder/c-projects) repository.

#### 7. Car Insurance Portal
**Folder:** `CarInsurance/`

An ASP.NET Core MVC web application with Entity Framework Core and SQLite.
- Computes monthly premium quotes server-side using a set of custom risk assessment business rules.
- Integrates with an SQLite database schema.
- Features a secure administrative portal detailing all registered policies.
- Seeds database records automatically on first startup.

---

#### 8. Server Time Web App
**Folder:** `ServerTimeWeb/`

An ASP.NET Core Razor Pages application.
- Uses `DateTime.Now` inside page handlers (`OnGet`) to compute server-side time.
- Employs a custom JavaScript event handler in the view to continuously tick the clock.
- Styled with dark-mode glassmorphism.

---

#### 9. Entity Framework Code-First Console App
**Folder:** `EntityFrameworkCodeFirst/`

A console application demonstrating ORM database modeling.
- Employs Entity Framework Core Code-First mappings to generate database tables dynamically.
- Auto-seeds a mock Student entity record.

---

## 🛠 Technologies Used

- **Languages:** HTML5, CSS3, JavaScript (ES6+), C# 12, SQL
- **Frameworks:** React.js, Node.js, Express.js, Bootstrap 4.5.2, ASP.NET Core (MVC & Razor Pages), Entity Framework Core
- **Databases:** SQLite, MySQL, MongoDB
- **Typography:** Google Fonts — Syne, DM Mono, Inter, Outfit
- **Tools:** VS Code, Visual Studio 2022, Git / GitHub, Chrome DevTools, GitHub Pages, postman


---

## 📁 Repository Structure

```
myCV/
└── index.html    # Portfolio website (single-file, all CSS and JS inline)
```
