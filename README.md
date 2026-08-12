# 🚀 Frontend Interview Handbooks

<div align="center">

### The Ultimate Frontend Interview Preparation Guide

Master Frontend Development with carefully curated interview questions, practical explanations, coding challenges, and real-world examples.

**React • Next.js • JavaScript • TypeScript • HTML • CSS • Redux Toolkit • APIs • JWT • Testing • Vite • Webpack**

⭐ Star this repository if it helps you.

</div>

---

# 📖 About

Frontend Interview Handbook is a free and open-source repository created to help developers prepare for frontend interviews with confidence.

Whether you're a beginner starting your frontend journey or an experienced developer preparing for product-based companies, this repository provides interview-focused learning with practical explanations, real-world examples, coding challenges, and best practices.

Unlike traditional interview repositories, every topic is organized to help you understand the concept instead of simply memorizing answers.

---

# HTML — Questions & Answers

HTML stands for **HyperText Markup Language**. It is the standard markup language used to structure web pages.

---

## 1. What is HTML?

HTML is a **markup language** used to create and structure content on web pages.

```html
<!DOCTYPE html>
<html>
<head>
    <title>My Website</title>
</head>
<body>
    <h1>Hello World</h1>
    <p>Welcome to my website.</p>
</body>
</html>
```

### Key Point

* HTML → Structure
* CSS → Styling
* JavaScript → Behavior

---

## 2. What does HTML stand for?

HTML stands for:

**HyperText Markup Language**

* HyperText → Text containing links to other resources.
* Markup → Uses tags to structure content.
* Language → Uses defined syntax and rules.

---

## 3. Is HTML a programming language?

No.

HTML is a **markup language**, not a programming language.

HTML does not provide programming concepts such as:

* Variables
* Loops
* Conditions
* Functions
* Algorithms

JavaScript is used for programming and application logic in web pages.

---

## 4. What is an HTML tag?

An HTML tag is a keyword enclosed inside angle brackets.

```html
<h1>Hello World</h1>
```

Here:

* `<h1>` → Opening tag
* `</h1>` → Closing tag

---

## 5. What is an HTML element?

An HTML element generally consists of an opening tag, content, and a closing tag.

```html
<p>Hello World</p>
```

The complete structure is an HTML element.

Some elements do not have closing tags. These are called **void elements**.

```html
<img src="image.jpg" alt="Image">
<br>
<input type="text">
```

---

## 6. What is an HTML attribute?

An attribute provides additional information about an HTML element.

```html
<a href="https://example.com">Visit Website</a>
```

Here:

```text
href
```

is an attribute.

Another example:

```html
<img src="photo.jpg" alt="Profile photo">
```

Attributes:

* `src`
* `alt`

---

## 7. What is `<!DOCTYPE html>`?

`<!DOCTYPE html>` tells the browser that the document uses the HTML standard.

```html
<!DOCTYPE html>
```

It should normally be placed at the beginning of an HTML document.

---

## 8. What is the basic structure of HTML?

```html
<!DOCTYPE html>

<html>
<head>
    <title>Page Title</title>
</head>

<body>

    <h1>Heading</h1>
    <p>Paragraph</p>

</body>
</html>
```

### Main Parts

| Element           | Purpose                 |
| ----------------- | ----------------------- |
| `<!DOCTYPE html>` | Defines document type   |
| `<html>`          | Root element            |
| `<head>`          | Metadata and resources  |
| `<title>`         | Browser tab title       |
| `<body>`          | Visible webpage content |

---

## 9. What is the `<head>` element?

The `<head>` contains information about the webpage that is generally not displayed directly as page content.

Example:

```html
<head>
    <meta charset="UTF-8">

    <meta
        name="viewport"
        content="width=device-width, initial-scale=1.0"
    >

    <title>My Website</title>

    <link rel="stylesheet" href="style.css">
</head>
```

It commonly contains:

* `<title>`
* `<meta>`
* `<link>`
* `<style>`
* `<script>`

---

## 10. What is the `<body>` element?

The `<body>` contains the visible content of a webpage.

```html
<body>
    <h1>Welcome</h1>
    <p>This content is visible on the page.</p>
</body>
```

---

## 11. What are headings in HTML?

HTML provides six heading levels:

```html
<h1>Main Heading</h1>
<h2>Section Heading</h2>
<h3>Subsection</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

`<h1>` represents the highest-level heading and `<h6>` the lowest.

---

## 12. What is a paragraph?

The `<p>` element defines a paragraph.

```html
<p>
    HTML is used to structure web pages.
</p>
```

---

## 13. What is the difference between `<div>` and `<span>`?

### `<div>`

`<div>` is a generic block-level container.

```html
<div>
    <h2>About Us</h2>
    <p>Our company information.</p>
</div>
```

### `<span>`

`<span>` is a generic inline container.

```html
<p>
    Welcome to <span>our website</span>.
</p>
```

### Difference

| `<div>`                       | `<span>`                              |
| ----------------------------- | ------------------------------------- |
| Block-level                   | Inline                                |
| Used for larger sections      | Used for small pieces of content      |
| Normally starts on a new line | Normally remains within the same line |

---

## 14. What are semantic HTML elements?

Semantic elements clearly describe the purpose of their content.

Common semantic elements:

```html
<header>
<nav>
<main>
<section>
<article>
<aside>
<footer>
```

Example:

```html
<header>
    <h1>My Website</h1>
</header>

<nav>
    <a href="/">Home</a>
    <a href="/about">About</a>
</nav>

<main>
    <section>
        <h2>Services</h2>
        <p>Our services.</p>
    </section>
</main>

<footer>
    <p>Copyright 2026</p>
</footer>
```

### Benefits

* Better accessibility
* Better SEO
* Better document structure
* Easier maintenance

---

## 15. What is the difference between semantic and non-semantic elements?

### Semantic

```html
<header>
<section>
<article>
<footer>
```

These elements communicate meaning.

### Non-semantic

```html
<div>
<span>
```

These elements do not communicate a specific meaning by themselves.

---

## 16. What is the difference between `id` and `class`?

### ID

An `id` identifies an element uniquely within a document.

```html
<div id="header">
    Header
</div>
```

### Class

A class can be reused on multiple elements.

```html
<p class="text">First paragraph</p>
<p class="text">Second paragraph</p>
```

CSS:

```css
.text {
    color: blue;
}
```

### Difference

| ID                          | Class                       |
| --------------------------- | --------------------------- |
| Should be unique            | Can be reused               |
| `#header` in CSS            | `.text` in CSS              |
| Used for a specific element | Used for groups of elements |

---

## 17. What is an HTML comment?

Comments are ignored by the browser and are useful for documenting code.

```html
<!-- This is an HTML comment -->
```

Comments are not displayed as normal page content.

---

## 18. What is the `<a>` tag?

The `<a>` element creates a hyperlink.

```html
<a href="https://example.com">
    Visit Website
</a>
```

Common attributes include:

```html
href
target
rel
download
```

Example:

```html
<a
    href="https://example.com"
    target="_blank"
    rel="noopener noreferrer"
>
    Open Website
</a>
```

---

## 19. What is the `<img>` tag?

The `<img>` element displays an image.

```html
<img
    src="profile.jpg"
    alt="Profile photo"
>
```

Important attributes:

* `src`
* `alt`
* `width`
* `height`
* `loading`

---

## 20. Why is the `alt` attribute important?

The `alt` attribute provides alternative text for an image.

```html
<img
    src="laptop.jpg"
    alt="Developer working on a laptop"
>
```

It helps with:

* Accessibility
* Screen readers
* Image loading failures
* Search engine understanding

---

## 21. What are HTML lists?

HTML provides three common types of lists.

### Unordered List

```html
<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>
```

### Ordered List

```html
<ol>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ol>
```

### Description List

```html
<dl>
    <dt>HTML</dt>
    <dd>Markup language for web structure.</dd>
</dl>
```

---

## 22. What is an HTML table?

Tables display structured tabular data.

```html
<table>
    <thead>
        <tr>
            <th>Name</th>
            <th>Age</th>
        </tr>
    </thead>

    <tbody>
        <tr>
            <td>John</td>
            <td>25</td>
        </tr>
    </tbody>
</table>
```

Important elements:

* `<table>`
* `<thead>`
* `<tbody>`
* `<tfoot>`
* `<tr>`
* `<th>`
* `<td>`

---

## 23. What are HTML forms?

Forms collect information from users.

```html
<form>
    <label for="email">Email</label>

    <input
        type="email"
        id="email"
        name="email"
    >

    <button type="submit">
        Submit
    </button>
</form>
```

Common form elements:

```html
<form>
<input>
<label>
<textarea>
<select>
<option>
<button>
```

---

## 24. What are common HTML input types?

Examples:

```html
<input type="text">

<input type="email">

<input type="password">

<input type="number">

<input type="date">

<input type="file">

<input type="checkbox">

<input type="radio">

<input type="submit">

<input type="search">

<input type="tel">

<input type="url">
```

---

## 25. Why is `<label>` important?

`<label>` describes a form control and improves accessibility.

```html
<label for="email">
    Email
</label>

<input
    type="email"
    id="email"
>
```

The `for` attribute should match the input's `id`.

---

## 26. What is the difference between GET and POST?

Forms can submit data using different HTTP methods.

### GET

```html
<form method="GET">
```

Data is generally included in the URL.

Commonly used for:

* Searches
* Filters
* Retrieving resources

### POST

```html
<form method="POST">
```

Data is sent in the HTTP request body.

Commonly used for:

* Creating resources
* Submitting forms
* Sending larger or sensitive form payloads

**Important:** POST does not by itself make data secure. Use HTTPS for transport security.

---

## 27. What is the viewport meta tag?

The viewport meta tag helps webpages render properly on different screen sizes.

```html
<meta
    name="viewport"
    content="width=device-width, initial-scale=1.0"
>
```

It is important for responsive web development.

---

## 28. What is HTML5?

HTML5 is the modern HTML standard and introduced many features for modern web development.

Important features include:

* Semantic elements
* Audio
* Video
* Canvas
* Improved forms
* New input types
* Web APIs

Example:

```html
<video controls>
    <source
        src="video.mp4"
        type="video/mp4"
    >
</video>
```

---

## 29. What is the difference between `<strong>` and `<b>`?

### `<strong>`

Indicates strong importance.

```html
<strong>Important information</strong>
```

### `<b>`

Draws attention to text without adding the same semantic meaning.

```html
<b>Bold text</b>
```

For meaningful importance, `<strong>` is generally preferred.

---

## 30. What is the difference between `<em>` and `<i>`?

### `<em>`

Provides semantic emphasis.

```html
<em>Very important</em>
```

### `<i>`

Represents text in an alternate voice or mood, or text conventionally rendered in italics.

```html
<i>Technical term</i>
```

---

## 31. What is the difference between `<section>` and `<article>`?

### `<section>`

Represents a thematic section of a document.

```html
<section>
    <h2>Our Services</h2>
</section>
```

### `<article>`

Represents self-contained content.

```html
<article>
    <h2>How to Learn HTML</h2>
    <p>HTML is the foundation of web development.</p>
</article>
```

Examples of articles:

* Blog posts
* News articles
* Forum posts

---

## 32. What is the difference between `<header>` and `<footer>`?

### `<header>`

Contains introductory content or navigation.

```html
<header>
    <h1>My Website</h1>
</header>
```

### `<footer>`

Contains footer information.

```html
<footer>
    <p>Copyright 2026</p>
</footer>
```

---

## 33. What is the difference between `<a>` and `<link>`?

### `<a>`

Creates a clickable hyperlink.

```html
<a href="/about">
    About Us
</a>
```

### `<link>`

Connects the document with an external resource.

```html
<link
    rel="stylesheet"
    href="style.css"
>
```

---

## 34. What are void elements?

Void elements do not contain content and do not require closing tags.

Examples:

```html
<img>
<br>
<hr>
<input>
<meta>
<link>
```

Example:

```html
<img src="image.jpg" alt="Example">
```

---

## 35. What is accessibility in HTML?

Accessibility means making websites usable by people with different abilities, including users who rely on assistive technologies.

Good practices include:

```html
<img src="logo.png" alt="Company logo">

<label for="email">Email</label>

<input id="email" type="email">

<button type="submit">
    Submit
</button>
```

Use semantic HTML whenever possible before reaching for ARIA.

---

## 36. What is ARIA?

ARIA stands for **Accessible Rich Internet Applications**.

ARIA provides additional accessibility information when native HTML semantics are insufficient.

Example:

```html
<button aria-label="Close menu">
    X
</button>
```

Native HTML elements should generally be preferred over unnecessary ARIA.

---

## 37. What is SEO-friendly HTML?

SEO-friendly HTML helps search engines understand the structure and meaning of a webpage.

Important practices include:

* Use meaningful `<title>`
* Use proper headings
* Use semantic HTML
* Use descriptive links
* Add useful image `alt` text
* Use appropriate metadata
* Create logical page structure

Example:

```html
<title>Web Development Services | Company Name</title>

<h1>Web Development Services</h1>

<p>
    We build modern websites and web applications.
</p>
```

---

## 38. What is the difference between block-level and inline elements?

### Block-level

A block-level element generally takes up the available horizontal space and starts on a new line.

Examples:

```html
<div>
<p>
<h1>
<section>
<header>
<footer>
```

### Inline

Inline elements generally remain within the current line.

Examples:

```html
<span>
<a>
<strong>
<em>
```

---

## 39. What is HTML entity encoding?

HTML entities represent reserved or special characters.

Examples:

```html
&lt;
&gt;
&amp;
&quot;
&nbsp;
```

For example:

```html
<p>
    5 &lt; 10
</p>
```

Displays:

```text
5 < 10
```

---

## 40. How do you add CSS to HTML?

There are three common approaches.

### Inline CSS

```html
<p style="color: red;">
    Hello
</p>
```

### Internal CSS

```html
<style>
    p {
        color: red;
    }
</style>
```

### External CSS

```html
<link
    rel="stylesheet"
    href="style.css"
>
```

External CSS is generally preferred for maintainability.

---

## 41. How do you add JavaScript to HTML?

Using the `<script>` element.

```html
<script src="app.js"></script>
```

For modern applications, JavaScript is often loaded with:

```html
<script
    src="app.js"
    defer
></script>
```

`defer` allows the script to download while HTML parsing continues and executes it after parsing is complete.

---

## 42. What is the difference between `async` and `defer`?

Both are commonly used with external scripts.

### `defer`

```html
<script
    src="app.js"
    defer
></script>
```

The script downloads while HTML parsing continues and executes after parsing is complete.

Deferred scripts maintain their document order.

### `async`

```html
<script
    src="analytics.js"
    async
></script>
```

The script executes as soon as it finishes downloading, so execution order relative to other async scripts is not guaranteed.

---

## 43. What is the `<iframe>` element?

`<iframe>` embeds another browsing context inside a webpage.

Example:

```html
<iframe
    src="https://example.com"
    title="Example website"
>
</iframe>
```

It can be used for things such as:

* Embedded maps
* Videos
* External documents

---

## 44. What are `<audio>` and `<video>`?

HTML provides native media elements.

### Audio

```html
<audio controls>
    <source
        src="song.mp3"
        type="audio/mpeg"
    >
</audio>
```

### Video

```html
<video controls>
    <source
        src="video.mp4"
        type="video/mp4"
    >
</video>
```

---

## 45. What is the `<canvas>` element?

`<canvas>` provides a drawing surface that JavaScript can manipulate.

```html
<canvas
    id="myCanvas"
    width="500"
    height="300"
>
</canvas>
```

JavaScript is used to draw graphics on the canvas.

---

## 46. What is the difference between HTML and CSS?

| HTML                      | CSS                                  |
| ------------------------- | ------------------------------------ |
| Defines structure         | Defines presentation                 |
| Creates headings          | Styles headings                      |
| Creates forms             | Styles forms                         |
| Creates links             | Styles links                         |
| Defines content structure | Controls layout, colors, fonts, etc. |

Example:

```html
<h1 class="title">
    Hello
</h1>
```

```css
.title {
    color: blue;
    font-size: 40px;
}
```

---

## 47. What is the difference between HTML and JavaScript?

| HTML              | JavaScript            |
| ----------------- | --------------------- |
| Markup language   | Programming language  |
| Creates structure | Adds behavior         |
| Defines elements  | Manipulates elements  |
| Static structure  | Dynamic functionality |

Example HTML:

```html
<button id="btn">
    Click Me
</button>
```

JavaScript:

```javascript
document
    .getElementById("btn")
    .addEventListener("click", function () {
        alert("Button clicked!");
    });
```

---

# Complete HTML Example

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">

    <meta
        name="viewport"
        content="width=device-width, initial-scale=1.0"
    >

    <meta
        name="description"
        content="Example HTML webpage"
    >

    <title>My Website</title>

    <link
        rel="stylesheet"
        href="style.css"
    >
</head>

<body>

    <header>
        <h1>My Website</h1>

        <nav>
            <a href="/">Home</a>
            <a href="/about">About</a>
            <a href="/contact">Contact</a>
        </nav>
    </header>

    <main>

        <section>
            <h2>About Us</h2>

            <p>
                We build modern websites and web applications.
            </p>

            <img
                src="team.jpg"
                alt="Our development team"
            >
        </section>

        <section>
            <h2>Contact Us</h2>

            <form method="POST">

                <label for="name">
                    Name
                </label>

                <input
                    type="text"
                    id="name"
                    name="name"
                    required
                >

                <label for="email">
                    Email
                </label>

                <input
                    type="email"
                    id="email"
                    name="email"
                    required
                >

                <label for="message">
                    Message
                </label>

                <textarea
                    id="message"
                    name="message"
                ></textarea>

                <button type="submit">
                    Submit
                </button>

            </form>
        </section>

    </main>

    <footer>
        <p>
            Copyright 2026 My Website
        </p>
    </footer>

    <script
        src="app.js"
        defer
    ></script>

</body>

</html>
```

# HTML Quick Revision

```text
HTML
│
├── Document Structure
│   ├── <!DOCTYPE html>
│   ├── <html>
│   ├── <head>
│   └── <body>
│
├── Text
│   ├── <h1> - <h6>
│   ├── <p>
│   ├── <strong>
│   ├── <em>
│   └── <span>
│
├── Structure
│   ├── <header>
│   ├── <nav>
│   ├── <main>
│   ├── <section>
│   ├── <article>
│   ├── <aside>
│   └── <footer>
│
├── Media
│   ├── <img>
│   ├── <audio>
│   ├── <video>
│   ├── <iframe>
│   └── <canvas>
│
├── Forms
│   ├── <form>
│   ├── <input>
│   ├── <label>
│   ├── <textarea>
│   ├── <select>
│   ├── <option>
│   └── <button>
│
├── Lists
│   ├── <ul>
│   ├── <ol>
│   └── <dl>
│
└── Tables
    ├── <table>
    ├── <thead>
    ├── <tbody>
    ├── <tr>
    ├── <th>
    └── <td>
```

# HTML Interview Preparation Order

1. HTML basics
2. Tags and elements
3. Attributes
4. Document structure
5. Headings and paragraphs
6. Links
7. Images
8. Lists
9. Tables
10. Forms
11. Input types
12. Semantic HTML
13. `id` vs `class`
14. Block vs inline elements
15. Accessibility
16. ARIA
17. HTML5
18. SEO-friendly HTML
19. Audio and video
20. Canvas
21. iframe
22. CSS integration
23. JavaScript integration
24. Responsive HTML
25. HTML interview questions

# HTML → CSS → JavaScript → React

# CSS — Questions & Answers

CSS stands for **Cascading Style Sheets**. It is used to control the presentation, layout, appearance, and responsive behavior of HTML elements.

---

# 1. What is CSS?

**Answer:**

CSS stands for **Cascading Style Sheets**.

CSS is used to style HTML elements.

It controls:

* Colors
* Fonts
* Spacing
* Layout
* Width and height
* Responsive design
* Animations
* Transitions
* Positioning

Example:

```css
h1 {
    color: blue;
    font-size: 40px;
}
```

---

# 2. Why is CSS used?

**Answer:**

CSS separates the **presentation** of a webpage from its HTML structure.

For example:

```html
<h1 class="title">Hello World</h1>
```

```css
.title {
    color: blue;
    font-size: 40px;
}
```

HTML defines the structure, while CSS controls how it looks.

---

# 3. What are the three ways to add CSS?

**Answer:**

There are three common ways.

## Inline CSS

```html
<p style="color: red;">
    Hello
</p>
```

## Internal CSS

```html
<style>
    p {
        color: red;
    }
</style>
```

## External CSS

```html
<link rel="stylesheet" href="style.css">
```

External CSS is generally preferred for maintainability and reuse.

---

# 4. What is CSS syntax?

**Answer:**

CSS syntax consists of:

```css
selector {
    property: value;
}
```

Example:

```css
p {
    color: red;
    font-size: 20px;
}
```

Here:

* `p` → Selector
* `color` → Property
* `red` → Value
* `color: red;` → Declaration

---

# 5. What is a CSS selector?

**Answer:**

A selector identifies the HTML elements that CSS should style.

Example:

```css
p {
    color: blue;
}
```

Here `p` is the selector.

---

# 6. What are the different types of CSS selectors?

**Answer:**

Common selectors include:

```css
/* Universal */
* {}

/* Element */
p {}

/* Class */
.box {}

/* ID */
#header {}

/* Attribute */
input[type="text"] {}

/* Descendant */
div p {}

/* Child */
div > p {}

/* Adjacent sibling */
h1 + p {}

/* General sibling */
h1 ~ p {}
```

---

# 7. What is the universal selector?

**Answer:**

The universal selector `*` selects all elements.

```css
* {
    margin: 0;
    padding: 0;
}
```

It is commonly used in CSS resets.

---

# 8. What is an element selector?

**Answer:**

An element selector selects HTML elements by their tag name.

```css
p {
    color: red;
}
```

This applies to all `<p>` elements.

---

# 9. What is a class selector?

**Answer:**

A class selector starts with `.`.

HTML:

```html
<p class="text">
    Hello
</p>
```

CSS:

```css
.text {
    color: blue;
}
```

The same class can be used on multiple elements.

---

# 10. What is an ID selector?

**Answer:**

An ID selector starts with `#`.

HTML:

```html
<div id="header">
    Header
</div>
```

CSS:

```css
#header {
    background: black;
}
```

An ID should normally be unique within a document.

---

# 11. What is the difference between ID and class?

**Answer:**

| ID                                      | Class                              |
| --------------------------------------- | ---------------------------------- |
| `#header`                               | `.header`                          |
| Intended to identify one unique element | Can be reused                      |
| Higher specificity than class           | Lower specificity than ID          |
| Commonly used for unique elements       | Commonly used for reusable styling |

Example:

```css
#header {
    color: red;
}

.text {
    color: blue;
}
```

---

# 12. What is a descendant selector?

**Answer:**

A descendant selector selects elements inside another element.

```css
div p {
    color: red;
}
```

This selects `<p>` elements anywhere inside a `<div>`.

---

# 13. What is a child selector?

**Answer:**

The `>` selector selects direct children.

```css
div > p {
    color: blue;
}
```

It selects only `<p>` elements that are direct children of `<div>`.

---

# 14. What is an adjacent sibling selector?

**Answer:**

The `+` selector selects the immediately following sibling.

```css
h1 + p {
    color: red;
}
```

This selects the first `<p>` immediately after an `<h1>`.

---

# 15. What is a general sibling selector?

**Answer:**

The `~` selector selects following siblings.

```css
h1 ~ p {
    color: blue;
}
```

It selects all matching `<p>` siblings that appear after the `<h1>`.

---

# 16. What is an attribute selector?

**Answer:**

Attribute selectors select elements based on attributes.

```css
input[type="text"] {
    border: 1px solid black;
}
```

Other examples:

```css
input[required] {}

a[target="_blank"] {}

img[alt] {}
```

---

# 17. What is the CSS box model?

**Answer:**

Every CSS element is represented by a box consisting of:

```text
+---------------------------+
|          Margin           |
|  +---------------------+  |
|  |       Border        |  |
|  | +-----------------+ |  |
|  | |     Padding     | |  |
|  | | +-------------+ | |  |
|  | | |   Content   | | |  |
|  | | +-------------+ | |  |
|  | +-----------------+ |  |
|  +---------------------+  |
+---------------------------+
```

The four parts are:

1. Content
2. Padding
3. Border
4. Margin

---

# 18. What is padding?

**Answer:**

Padding is the space between the content and the border.

```css
.box {
    padding: 20px;
}
```

---

# 19. What is margin?

**Answer:**

Margin is the space outside the border.

```css
.box {
    margin: 20px;
}
```

---

# 20. What is border?

**Answer:**

Border surrounds the padding and content.

```css
.box {
    border: 1px solid black;
}
```

---

# 21. What is `box-sizing`?

**Answer:**

`box-sizing` controls how width and height are calculated.

Two common values are:

```css
box-sizing: content-box;
```

and

```css
box-sizing: border-box;
```

With:

```css
* {
    box-sizing: border-box;
}
```

the declared width and height include content, padding, and border.

This is a common CSS reset pattern.

---

# 22. What is the difference between `content-box` and `border-box`?

**Answer:**

### content-box

The declared width applies to the content area.

```css
box-sizing: content-box;
```

Padding and border are added outside that width.

### border-box

The declared width includes content, padding, and border.

```css
box-sizing: border-box;
```

---

# 23. What is `display` in CSS?

**Answer:**

The `display` property determines how an element participates in layout.

Common values:

```css
display: block;
display: inline;
display: inline-block;
display: flex;
display: grid;
display: none;
```

---

# 24. What is `display: block`?

**Answer:**

A block-level element generally starts on a new line and can take available horizontal space.

```css
div {
    display: block;
}
```

Examples include:

* `<div>`
* `<p>`
* `<section>`
* `<header>`

---

# 25. What is `display: inline`?

**Answer:**

Inline elements generally remain in the same line.

```css
span {
    display: inline;
}
```

Examples include:

* `<span>`
* `<a>`
* `<strong>`

---

# 26. What is `display: inline-block`?

**Answer:**

`inline-block` combines characteristics of inline and block layout.

It can:

* Remain inline with surrounding content
* Accept width and height
* Accept padding and margin

```css
.button {
    display: inline-block;
    width: 150px;
    padding: 10px;
}
```

---

# 27. What does `display: none` do?

**Answer:**

It removes the element from the layout.

```css
.menu {
    display: none;
}
```

The element does not occupy layout space.

---

# 28. What is the difference between `display: none` and `visibility: hidden`?

**Answer:**

### display: none

```css
display: none;
```

The element is removed from the layout.

### visibility: hidden

```css
visibility: hidden;
```

The element is invisible but normally still occupies its layout space.

---

# 29. What is CSS positioning?

**Answer:**

The `position` property controls how an element is positioned.

Common values:

```css
static
relative
absolute
fixed
sticky
```

---

# 30. What is `position: static`?

**Answer:**

`static` is the default positioning behavior.

```css
.box {
    position: static;
}
```

The `top`, `right`, `bottom`, and `left` properties do not reposition a statically positioned element.

---

# 31. What is `position: relative`?

**Answer:**

The element remains in the normal document flow but can be offset relative to its normal position.

```css
.box {
    position: relative;
    top: 20px;
    left: 10px;
}
```

It also establishes a positioning reference for absolutely positioned descendants.

---

# 32. What is `position: absolute`?

**Answer:**

An absolutely positioned element is removed from normal flow and positioned relative to its containing block.

```css
.box {
    position: absolute;
    top: 20px;
    right: 20px;
}
```

A common pattern is:

```css
.parent {
    position: relative;
}

.child {
    position: absolute;
    top: 0;
    right: 0;
}
```

---

# 33. What is `position: fixed`?

**Answer:**

A fixed element is positioned relative to the viewport and generally remains in place while the page scrolls.

```css
.header {
    position: fixed;
    top: 0;
    width: 100%;
}
```

---

# 34. What is `position: sticky`?

**Answer:**

`sticky` behaves like a relatively positioned element until a specified scroll threshold is reached, after which it sticks within its scrolling context.

```css
.header {
    position: sticky;
    top: 0;
}
```

---

# 35. What is `z-index`?

**Answer:**

`z-index` controls stacking order for positioned elements and certain other stacking contexts.

```css
.modal {
    position: fixed;
    z-index: 1000;
}
```

A larger `z-index` does not universally guarantee that an element appears above everything; stacking contexts also matter.

---

# 36. What is Flexbox?

**Answer:**

Flexbox is a one-dimensional CSS layout system.

It is useful for arranging elements in a:

* Row
* Column

Example:

```css
.container {
    display: flex;
}
```

---

# 37. What is the main axis in Flexbox?

**Answer:**

The main axis is determined by `flex-direction`.

```css
flex-direction: row;
```

Main axis:

```text
→
```

With:

```css
flex-direction: column;
```

Main axis:

```text
↓
```

---

# 38. What is the cross axis in Flexbox?

**Answer:**

The cross axis is perpendicular to the main axis.

If:

```css
flex-direction: row;
```

the cross axis is vertical.

If:

```css
flex-direction: column;
```

the cross axis is horizontal.

---

# 39. What is `justify-content`?

**Answer:**

`justify-content` aligns flex items along the main axis.

Common values:

```css
justify-content: flex-start;
justify-content: center;
justify-content: flex-end;
justify-content: space-between;
justify-content: space-around;
justify-content: space-evenly;
```

Example:

```css
.container {
    display: flex;
    justify-content: center;
}
```

---

# 40. What is `align-items`?

**Answer:**

`align-items` aligns flex items along the cross axis.

```css
.container {
    display: flex;
    align-items: center;
}
```

---

# 41. What is `align-content`?

**Answer:**

`align-content` controls the distribution of multiple flex lines or grid tracks along the cross axis.

It is relevant when there is extra cross-axis space and multiple lines/tracks.

```css
.container {
    display: flex;
    flex-wrap: wrap;
    align-content: center;
}
```

It is different from `align-items`.

---

# 42. What is `flex-direction`?

**Answer:**

It defines the direction of the main axis.

```css
flex-direction: row;
flex-direction: row-reverse;
flex-direction: column;
flex-direction: column-reverse;
```

---

# 43. What is `flex-wrap`?

**Answer:**

It determines whether flex items can move onto multiple lines.

```css
.container {
    display: flex;
    flex-wrap: wrap;
}
```

Values:

```css
nowrap
wrap
wrap-reverse
```

---

# 44. What is `gap`?

**Answer:**

`gap` creates spacing between flex or grid items.

```css
.container {
    display: flex;
    gap: 20px;
}
```

It is generally cleaner than using margins solely to create inter-item spacing.

---

# 45. What is the `flex` shorthand?

**Answer:**

The `flex` property is shorthand for:

```text
flex-grow
flex-shrink
flex-basis
```

Example:

```css
.item {
    flex: 1;
}
```

---

# 46. What is `flex-grow`?

**Answer:**

It determines how much an item can grow relative to other flex items when extra space is available.

```css
.item {
    flex-grow: 1;
}
```

---

# 47. What is `flex-shrink`?

**Answer:**

It determines how much a flex item can shrink when there is insufficient space.

```css
.item {
    flex-shrink: 1;
}
```

---

# 48. What is `flex-basis`?

**Answer:**

It defines the initial main-size contribution of a flex item before remaining space is distributed.

```css
.item {
    flex-basis: 200px;
}
```

---

# 49. What is CSS Grid?

**Answer:**

CSS Grid is a two-dimensional layout system.

It works with:

* Rows
* Columns

Example:

```css
.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}
```

---

# 50. What is `grid-template-columns`?

**Answer:**

It defines the grid columns.

```css
.container {
    display: grid;
    grid-template-columns: 200px 1fr 1fr;
}
```

Another example:

```css
grid-template-columns: repeat(3, 1fr);
```

---

# 51. What is `grid-template-rows`?

**Answer:**

It defines the grid rows.

```css
.container {
    display: grid;
    grid-template-rows: 100px 200px;
}
```

---

# 52. What is the `fr` unit?

**Answer:**

`fr` represents a fraction of the available space in a CSS Grid container.

```css
grid-template-columns: 1fr 2fr;
```

The available space is distributed in a 1:2 ratio.

---

# 53. What is `repeat()` in CSS Grid?

**Answer:**

`repeat()` avoids repeating the same track definition.

Instead of:

```css
grid-template-columns: 1fr 1fr 1fr;
```

you can write:

```css
grid-template-columns: repeat(3, 1fr);
```

---

# 54. What is `grid-column`?

**Answer:**

It controls which grid columns an item occupies.

```css
.item {
    grid-column: 1 / 3;
}
```

This places the item across the grid lines from 1 to 3.

---

# 55. What is `grid-row`?

**Answer:**

It controls which grid rows an item occupies.

```css
.item {
    grid-row: 1 / 3;
}
```

---

# 56. Flexbox vs Grid?

**Answer:**

| Flexbox                           | Grid                                 |
| --------------------------------- | ------------------------------------ |
| One-dimensional                   | Two-dimensional                      |
| Row or column                     | Rows and columns                     |
| Excellent for component alignment | Excellent for page/layout structures |
| Content-oriented                  | Layout-oriented                      |

They can also be used together.

---

# 57. What are CSS units?

**Answer:**

CSS units define sizes.

Common units:

```text
px
%
em
rem
vw
vh
vmin
vmax
ch
fr
```

---

# 58. What is `px`?

**Answer:**

`px` is a CSS pixel unit.

```css
font-size: 16px;
```

It is commonly used for precise dimensions.

---

# 59. What is `%`?

**Answer:**

Percentage values are generally relative to a relevant containing dimension.

```css
width: 50%;
```

The exact reference depends on the property and layout context.

---

# 60. What is `em`?

**Answer:**

`em` is relative to the font size of the relevant element or inherited context.

Example:

```css
.parent {
    font-size: 20px;
}

.child {
    font-size: 2em;
}
```

The child would resolve to 40px in this simple example.

---

# 61. What is `rem`?

**Answer:**

`rem` is relative to the root element's font size.

```css
html {
    font-size: 16px;
}

h1 {
    font-size: 2rem;
}
```

Here `2rem` resolves to 32px.

---

# 62. `em` vs `rem`?

**Answer:**

| `em`                                     | `rem`                                  |
| ---------------------------------------- | -------------------------------------- |
| Relative to relevant element font sizing | Relative to root font size             |
| Can compound through nesting             | More predictable for global sizing     |
| Useful for component-relative sizing     | Useful for consistent page-wide sizing |

---

# 63. What are `vw` and `vh`?

**Answer:**

`vw` is based on viewport width.

```css
width: 50vw;
```

`vh` is based on viewport height.

```css
height: 50vh;
```

---

# 64. What is `clamp()`?

**Answer:**

`clamp()` allows a value to have a minimum, preferred, and maximum value.

```css
font-size: clamp(1.5rem, 4vw, 3rem);
```

It is useful for responsive typography.

---

# 65. What is a CSS variable?

**Answer:**

CSS variables are custom properties.

```css
:root {
    --primary-color: #2563eb;
    --spacing: 20px;
}
```

Use them with:

```css
.button {
    background: var(--primary-color);
    padding: var(--spacing);
}
```

---

# 66. What is `var()`?

**Answer:**

`var()` retrieves the value of a CSS custom property.

```css
:root {
    --main-color: blue;
}

h1 {
    color: var(--main-color);
}
```

A fallback can also be provided:

```css
color: var(--main-color, black);
```

---

# 67. What is CSS specificity?

**Answer:**

Specificity determines which competing CSS selector has greater priority when declarations conflict.

A simplified ordering is:

```text
Inline styles
    ↓
ID
    ↓
Class / attribute / pseudo-class
    ↓
Element / pseudo-element
```

Example:

```css
p {
    color: blue;
}

.text {
    color: green;
}

#title {
    color: red;
}
```

If all apply to the same element, the ID selector has greater specificity than the class and element selectors.

---

# 68. What is the CSS cascade?

**Answer:**

The cascade is the mechanism browsers use to determine which CSS declarations apply when multiple rules target the same element.

Factors include:

* Origin and importance
* Cascade layers
* Specificity
* Source order

---

# 69. What is `!important`?

**Answer:**

`!important` increases the priority of a declaration within the cascade.

```css
.title {
    color: red !important;
}
```

It should be used sparingly because excessive use makes CSS harder to maintain.

---

# 70. What is inheritance in CSS?

**Answer:**

Some CSS properties are inherited from parent elements by default.

Example:

```css
body {
    color: blue;
}
```

Many text-related properties can be inherited by descendants.

Not all CSS properties are inherited.

---

# 71. What is a pseudo-class?

**Answer:**

A pseudo-class targets an element based on a state or condition.

Examples:

```css
:hover
:focus
:active
:visited
:first-child
:last-child
:nth-child()
:not()
```

Example:

```css
button:hover {
    background: black;
}
```

---

# 72. What is a pseudo-element?

**Answer:**

A pseudo-element styles a specific part of an element or creates generated content.

Examples:

```css
::before
::after
::first-letter
::first-line
::selection
```

Example:

```css
.title::before {
    content: "★ ";
}
```

---

# 73. What is `:hover`?

**Answer:**

`:hover` applies styles when the pointing device is over an element.

```css
button:hover {
    background: black;
    color: white;
}
```

---

# 74. What is `:focus`?

**Answer:**

`:focus` applies styles when an element receives focus.

```css
input:focus {
    border-color: blue;
}
```

It is especially important for keyboard accessibility.

---

# 75. What is `:nth-child()`?

**Answer:**

It selects elements based on their position among siblings.

```css
li:nth-child(2) {
    color: red;
}
```

This selects the second `<li>` if it is the second child of its parent.

---

# 76. What is `:not()`?

**Answer:**

`:not()` excludes elements matching the selector inside it.

```css
p:not(.special) {
    color: gray;
}
```

This targets paragraphs that do not have the `special` class.

---

# 77. What is a CSS transition?

**Answer:**

A transition creates a smooth change between CSS property values.

```css
button {
    background: blue;
    transition: background 0.3s ease;
}

button:hover {
    background: black;
}
```

---

# 78. What is a CSS animation?

**Answer:**

CSS animations allow properties to change over time using `@keyframes`.

```css
.box {
    animation: move 2s infinite;
}

@keyframes move {
    from {
        transform: translateX(0);
    }

    to {
        transform: translateX(100px);
    }
}
```

---

# 79. Transition vs Animation?

**Answer:**

| Transition                          | Animation                  |
| ----------------------------------- | -------------------------- |
| Usually triggered by a state change | Can run automatically      |
| Requires starting and ending states | Uses `@keyframes`          |
| Good for hover effects              | Good for complex sequences |

---

# 80. What is `transform`?

**Answer:**

`transform` changes the visual geometry of an element.

Examples:

```css
transform: translateX(20px);
transform: translateY(20px);
transform: scale(1.2);
transform: rotate(45deg);
```

Multiple transforms can be combined.

---

# 81. What is `overflow`?

**Answer:**

`overflow` controls what happens when content exceeds an element's box.

Common values:

```css
overflow: visible;
overflow: hidden;
overflow: auto;
overflow: scroll;
```

Example:

```css
.container {
    overflow: auto;
}
```

---

# 82. What is `opacity`?

**Answer:**

`opacity` controls the transparency of an element.

```css
.box {
    opacity: 0.5;
}
```

Values range from:

```text
0 → fully transparent
1 → fully opaque
```

---

# 83. What is `object-fit`?

**Answer:**

`object-fit` controls how replaced content such as images and videos fits inside its box.

Example:

```css
img {
    width: 300px;
    height: 200px;
    object-fit: cover;
}
```

Common values:

```css
cover
contain
fill
none
scale-down
```

---

# 84. What is `object-position`?

**Answer:**

It controls the position of replaced content inside its box.

```css
img {
    object-fit: cover;
    object-position: center;
}
```

---

# 85. What is `background-size: cover`?

**Answer:**

`cover` scales a background image so the container is completely covered.

```css
.hero {
    background-image: url("hero.jpg");
    background-size: cover;
    background-position: center;
}
```

Some portions of the image may be cropped.

---

# 86. What is `background-size: contain`?

**Answer:**

`contain` scales the background image so the entire image fits inside the container.

```css
.hero {
    background-size: contain;
}
```

This may leave empty space around the image.

---

# 87. What are media queries?

**Answer:**

Media queries apply CSS based on conditions such as viewport size.

```css
@media (max-width: 768px) {
    .container {
        flex-direction: column;
    }
}
```

They are commonly used for responsive design.

---

# 88. What is responsive web design?

**Answer:**

Responsive web design allows a website to adapt to different screen sizes and devices.

Common techniques:

* Flexible layouts
* Flexbox
* Grid
* Relative units
* Media queries
* Responsive images
* `clamp()`

---

# 89. What is mobile-first design?

**Answer:**

Mobile-first design means writing the base CSS for smaller screens first and progressively enhancing the layout for larger screens.

Example:

```css
.container {
    display: block;
}

@media (min-width: 768px) {
    .container {
        display: flex;
    }
}
```

---

# 90. What is `min-width`?

**Answer:**

`min-width` defines the minimum width an element can have.

```css
.container {
    min-width: 300px;
}
```

---

# 91. What is `max-width`?

**Answer:**

`max-width` defines the maximum width.

```css
.container {
    max-width: 1200px;
    margin: 0 auto;
}
```

This is commonly used for centered page containers.

---

# 92. What is `min-height` and `max-height`?

**Answer:**

They define minimum and maximum height constraints.

```css
.box {
    min-height: 200px;
    max-height: 500px;
}
```

---

# 93. What is `calc()`?

**Answer:**

`calc()` performs calculations in CSS.

```css
.container {
    width: calc(100% - 40px);
}
```

It can combine compatible units.

---

# 94. What is `min()`?

**Answer:**

`min()` chooses the smallest value from its arguments.

```css
width: min(90%, 1200px);
```

---

# 95. What is `max()`?

**Answer:**

`max()` chooses the largest value.

```css
width: max(300px, 50%);
```

---

# 96. What is `@media`?

**Answer:**

`@media` creates conditional CSS rules.

```css
@media (max-width: 600px) {
    body {
        font-size: 14px;
    }
}
```

---

# 97. What is `@keyframes`?

**Answer:**

`@keyframes` defines the stages of a CSS animation.

```css
@keyframes fadeIn {
    from {
        opacity: 0;
    }

    to {
        opacity: 1;
    }
}
```

---

# 98. What is `@import`?

**Answer:**

`@import` loads another CSS stylesheet.

```css
@import url("theme.css");
```

For production CSS, using HTML `<link>` for external stylesheets is often preferable because it generally gives the browser more direct opportunities to discover stylesheets and can avoid some dependency-chain costs.

---

# 99. What is CSS reset?

**Answer:**

A CSS reset removes or normalizes browser default styles.

Example:

```css
*,
*::before,
*::after {
    box-sizing: border-box;
}

body {
    margin: 0;
}

h1,
h2,
h3,
p {
    margin: 0;
}
```

---

# 100. What is Normalize CSS?

**Answer:**

Normalize CSS aims to make default browser styles more consistent across browsers while preserving useful defaults.

A reset usually removes more defaults.

---

# 101. What is the difference between reset and normalize?

**Answer:**

### Reset

Removes many browser defaults.

### Normalize

Keeps useful defaults while making rendering more consistent.

---

# 102. What is `currentColor`?

**Answer:**

`currentColor` refers to the element's computed `color` value.

```css
.button {
    color: blue;
    border: 1px solid currentColor;
}
```

The border becomes blue.

---

# 103. What is `inherit`?

**Answer:**

`inherit` explicitly tells a property to use the parent's computed value.

```css
.child {
    color: inherit;
}
```

---

# 104. What is `initial`?

**Answer:**

`initial` resets a property to its CSS-defined initial value.

```css
.box {
    color: initial;
}
```

---

# 105. What is `unset`?

**Answer:**

`unset` behaves like `inherit` for inherited properties and like `initial` for non-inherited properties.

```css
.box {
    color: unset;
}
```

---

# 106. What is `revert`?

**Answer:**

`revert` rolls a property back toward the value provided by an earlier cascade origin, such as the user-agent stylesheet, depending on the cascade.

```css
button {
    all: revert;
}
```

---

# 107. What is the `all` property?

**Answer:**

The `all` property resets most CSS properties at once.

```css
.element {
    all: unset;
}
```

It does not reset certain properties such as `unicode-bidi` and `direction`.

---

# 108. What is CSS nesting?

**Answer:**

Modern CSS supports nesting related rules inside another rule.

```css
.card {
    padding: 20px;

    & .title {
        font-size: 24px;
    }

    &:hover {
        transform: translateY(-5px);
    }
}
```

Browser support should be considered when targeting older environments.

---

# 109. What are CSS cascade layers?

**Answer:**

Cascade layers allow authors to explicitly organize CSS priority.

```css
@layer reset, base, components, utilities;
```

Example:

```css
@layer components {
    .button {
        padding: 10px 20px;
    }
}
```

Layers can make large CSS systems easier to manage.

---

# 110. What is `aspect-ratio`?

**Answer:**

`aspect-ratio` controls the preferred width-to-height ratio of an element.

```css
.video {
    width: 100%;
    aspect-ratio: 16 / 9;
}
```

This is useful for images, videos, cards, and media containers.

---

# 111. What is `accent-color`?

**Answer:**

`accent-color` allows certain form controls to use a custom accent color.

```css
input[type="checkbox"] {
    accent-color: blue;
}
```

---

# 112. What is `appearance`?

**Answer:**

`appearance` controls the native appearance of certain form controls.

```css
select {
    appearance: none;
}
```

Use it carefully because removing native styling can affect usability and accessibility.

---

# 113. What is `cursor`?

**Answer:**

`cursor` controls the mouse pointer appearance.

```css
button {
    cursor: pointer;
}
```

Common values:

```css
pointer
default
not-allowed
wait
text
grab
```

---

# 114. What is `white-space`?

**Answer:**

`white-space` controls how whitespace and line breaks are handled.

Common values:

```css
white-space: normal;
white-space: nowrap;
white-space: pre;
white-space: pre-wrap;
```

Example:

```css
.title {
    white-space: nowrap;
}
```

---

# 115. What is `text-overflow`?

**Answer:**

`text-overflow` controls how overflowing text is indicated.

Common pattern:

```css
.title {
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
}
```

This can display:

```text
This is a very long...
```

---

# 116. What is `line-height`?

**Answer:**

`line-height` controls the height of a line box and affects vertical spacing between lines of text.

```css
p {
    line-height: 1.6;
}
```

Unitless values are often useful for scalable typography.

---

# 117. What is `letter-spacing`?

**Answer:**

It controls the spacing between characters.

```css
h1 {
    letter-spacing: 1px;
}
```

---

# 118. What is `word-spacing`?

**Answer:**

It controls spacing between words.

```css
p {
    word-spacing: 5px;
}
```

---

# 119. What is `text-align`?

**Answer:**

It controls inline content alignment within a block container.

```css
text-align: left;
text-align: center;
text-align: right;
text-align: justify;
```

---

# 120. What is `text-transform`?

**Answer:**

It changes the capitalization of text.

```css
text-transform: uppercase;
text-transform: lowercase;
text-transform: capitalize;
```

---

# 121. What is `font-weight`?

**Answer:**

It controls the thickness of text.

```css
font-weight: 400;
font-weight: 700;
```

Common meanings:

```text
400 → normal
700 → bold
```

Available weights depend on the selected font.

---

# 122. What is `font-family`?

**Answer:**

It specifies the font used for text.

```css
body {
    font-family: Arial, sans-serif;
}
```

A fallback list can be provided.

---

# 123. What is a web-safe font?

**Answer:**

A web-safe font is a font likely to be available across many systems.

Examples include:

```text
Arial
Verdana
Georgia
Times New Roman
Courier New
```

Modern websites can also use web fonts.

---

# 124. What is `@font-face`?

**Answer:**

`@font-face` allows a custom font to be declared for use in a webpage.

```css
@font-face {
    font-family: "MyFont";
    src: url("myfont.woff2") format("woff2");
}

body {
    font-family: "MyFont", sans-serif;
}
```

---

# 125. What is CSS shorthand?

**Answer:**

Shorthand allows multiple related properties to be written in one declaration.

Instead of:

```css
margin-top: 10px;
margin-right: 20px;
margin-bottom: 10px;
margin-left: 20px;
```

you can write:

```css
margin: 10px 20px;
```

---

# 126. What is margin collapsing?

**Answer:**

In certain normal-flow block layouts, vertical margins of adjacent block elements can collapse into a single margin rather than adding together.

Example:

```css
.box1 {
    margin-bottom: 20px;
}

.box2 {
    margin-top: 30px;
}
```

The resulting vertical separation can be 30px rather than 50px, depending on the layout context.

Margin collapsing does not generally occur inside flex or grid containers.

---

# 127. What is a containing block?

**Answer:**

A containing block is the reference rectangle used for calculating the size and position of certain elements.

For example, an absolutely positioned child commonly uses its positioned ancestor as its containing block.

```css
.parent {
    position: relative;
}

.child {
    position: absolute;
}
```

---

# 128. What is a stacking context?

**Answer:**

A stacking context is a conceptual group in the rendering order that is stacked independently from surrounding contexts.

It can be created by properties such as:

```css
position + z-index
opacity < 1
transform
filter
isolation: isolate
```

Stacking contexts explain many unexpected `z-index` problems.

---

# 129. What is `isolation: isolate`?

**Answer:**

It creates a new stacking context for an element.

```css
.container {
    isolation: isolate;
}
```

It can help prevent z-index interactions from escaping a component.

---

# 130. What is `position: absolute` relative to?

**Answer:**

An absolutely positioned element is positioned relative to its containing block.

A common pattern is:

```css
.parent {
    position: relative;
}

.child {
    position: absolute;
    top: 0;
    left: 0;
}
```

The child is positioned relative to the parent's padding box in the relevant positioning model.

---

# 131. What is `overflow-x` and `overflow-y`?

**Answer:**

They independently control horizontal and vertical overflow.

```css
.container {
    overflow-x: auto;
    overflow-y: hidden;
}
```

---

# 132. What is `scroll-behavior`?

**Answer:**

It controls scrolling behavior for scroll operations.

```css
html {
    scroll-behavior: smooth;
}
```

Consider accessibility preferences before forcing smooth scrolling globally.

---

# 133. What is `scroll-snap`?

**Answer:**

CSS Scroll Snap allows scrolling to snap to defined positions.

Example:

```css
.container {
    scroll-snap-type: x mandatory;
}

.item {
    scroll-snap-align: start;
}
```

It is useful for carousels and horizontal scrolling interfaces.

---

# 134. What is `object-fit` vs `background-size`?

**Answer:**

`object-fit` applies to replaced elements such as `<img>` and `<video>`.

```css
img {
    object-fit: cover;
}
```

`background-size` applies to CSS background images.

```css
.hero {
    background-size: cover;
}
```

---

# 135. What is CSS specificity order?

**Answer:**

A simplified mental model is:

```text
Inline style
    ↓
ID
    ↓
Class / attribute / pseudo-class
    ↓
Element / pseudo-element
```

Example:

```css
p {
    color: blue;
}

.text {
    color: green;
}

#title {
    color: red;
}
```

If all selectors match the same element, the ID rule generally wins because it has higher specificity.

---

# 136. What happens when two selectors have the same specificity?

**Answer:**

The rule appearing later in the relevant cascade order generally wins.

Example:

```css
.title {
    color: red;
}

.title {
    color: blue;
}
```

The text will generally be blue.

---

# 137. What is CSS performance optimization?

**Answer:**

Common techniques include:

* Remove unused CSS
* Minify production CSS
* Avoid unnecessarily complex selectors
* Reduce stylesheet size
* Load critical styles efficiently
* Use modern image formats
* Avoid excessive animations
* Prefer efficient properties for animations
* Use caching
* Avoid unnecessary `!important`

---

# 138. Which CSS properties are generally better for animation performance?

**Answer:**

For many animations, `transform` and `opacity` are preferable because browsers can often optimize them efficiently.

Example:

```css
.card {
    transition:
        transform 0.3s ease,
        opacity 0.3s ease;
}

.card:hover {
    transform: translateY(-5px);
    opacity: 0.9;
}
```

Actual performance depends on the browser, device, and surrounding layout.

---

# 139. What is `prefers-reduced-motion`?

**Answer:**

It is a media feature that detects whether the user has requested reduced motion.

```css
@media (prefers-reduced-motion: reduce) {
    * {
        animation-duration: 0.01ms;
        animation-iteration-count: 1;
        transition-duration: 0.01ms;
        scroll-behavior: auto;
    }
}
```

It is useful for accessibility.

---

# 140. What is `prefers-color-scheme`?

**Answer:**

It detects whether the user prefers a light or dark color scheme.

```css
@media (prefers-color-scheme: dark) {
    body {
        background: #111;
        color: white;
    }
}
```

---

# 141. What is CSS architecture?

**Answer:**

CSS architecture is the organization of CSS so that large projects remain maintainable.

Common approaches include:

* BEM
* Utility-first CSS
* Component-based CSS
* CSS Modules
* Cascade Layers
* Design tokens

---

# 142. What is BEM?

**Answer:**

BEM stands for:

**Block Element Modifier**

Example:

```html
<div class="card">
    <h2 class="card__title">
        Product
    </h2>

    <button class="card__button card__button--primary">
        Buy
    </button>
</div>
```

Structure:

```text
card              → Block
card__title       → Element
card__button      → Element
card__button--primary → Modifier
```

---

# 143. What are CSS Modules?

**Answer:**

CSS Modules scope class names to a component/module.

They are commonly used in JavaScript frameworks such as React.

Example:

```css
.title {
    color: blue;
}
```

The build system generates a locally scoped class name, reducing accidental global CSS collisions.

---

# 144. What is utility-first CSS?

**Answer:**

Utility-first CSS uses small classes that represent individual styling rules.

Conceptually:

```html
<div class="p-4 flex items-center gap-4">
    Content
</div>
```

Frameworks such as Tailwind CSS use this approach.

---

# 145. What are CSS custom properties useful for?

**Answer:**

They are useful for:

* Design tokens
* Themes
* Reusable values
* Dynamic styling
* Component customization

Example:

```css
:root {
    --primary: #2563eb;
    --radius: 8px;
    --space: 16px;
}

.button {
    background: var(--primary);
    border-radius: var(--radius);
    padding: var(--space);
}
```

---

# 146. What is a design token?

**Answer:**

A design token is a reusable value representing a design decision.

Examples:

```css
:root {
    --color-primary: #2563eb;
    --color-text: #111827;
    --spacing-md: 16px;
    --radius-md: 8px;
}
```

Tokens help maintain consistency across a design system.

---

# 147. What is CSS Grid `auto-fit`?

**Answer:**

`auto-fit` allows the grid to fit as many columns as possible into the available space.

Example:

```css
.grid {
    display: grid;
    grid-template-columns:
        repeat(auto-fit, minmax(250px, 1fr));

    gap: 20px;
}
```

This is a powerful pattern for responsive card layouts.

---

# 148. What is CSS Grid `auto-fill`?

**Answer:**

`auto-fill` creates as many tracks as can fit, including potentially empty tracks when there is extra space.

```css
.grid {
    grid-template-columns:
        repeat(auto-fill, minmax(250px, 1fr));
}
```

`auto-fit` can collapse empty tracks, allowing existing items to expand.

---

# 149. What is `minmax()`?

**Answer:**

`minmax()` defines a minimum and maximum size for a grid track.

```css
grid-template-columns:
    repeat(3, minmax(200px, 1fr));
```

---

# 150. What is the difference between `auto-fit` and `auto-fill`?

**Answer:**

Both are commonly used with `repeat()` and `minmax()`.

```css
repeat(auto-fit, minmax(250px, 1fr))
```

allows empty tracks to collapse so existing items can expand.

```css
repeat(auto-fill, minmax(250px, 1fr))
```

keeps as many possible tracks available, including empty tracks.

---

# 151. What is `place-items`?

**Answer:**

`place-items` is shorthand for:

```text
align-items
justify-items
```

Example:

```css
.container {
    display: grid;
    place-items: center;
}
```

---

# 152. What is `place-content`?

**Answer:**

`place-content` is shorthand for:

```text
align-content
justify-content
```

Example:

```css
.container {
    place-content: center;
}
```

---

# 153. What is `place-self`?

**Answer:**

`place-self` controls the alignment of an individual grid item.

```css
.item {
    place-self: center;
}
```

---

# 154. How can you center an element using Flexbox?

**Answer:**

```css
.container {
    display: flex;
    justify-content: center;
    align-items: center;
}
```

This centers items along both axes when the container's main and cross axes correspond to the intended directions.

---

# 155. How can you center an element using Grid?

**Answer:**

```css
.container {
    display: grid;
    place-items: center;
}
```

---

# 156. How do you create a responsive three-column layout?

**Answer:**

Using Grid:

```css
.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}

@media (max-width: 768px) {
    .container {
        grid-template-columns: 1fr;
    }
}
```

---

# 157. How do you create a responsive card grid without a media query?

**Answer:**

A common Grid pattern is:

```css
.container {
    display: grid;
    grid-template-columns:
        repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}
```

The browser automatically adjusts the number of columns based on available space.

---

# 158. How do you create a full-screen section?

**Answer:**

A common approach is:

```css
.hero {
    min-height: 100vh;
}
```

Modern viewport units can also be useful:

```css
.hero {
    min-height: 100dvh;
}
```

`dvh` represents the dynamic viewport height and can behave better on mobile browsers where browser UI changes the viewport.

---

# 159. What are `svh`, `lvh`, and `dvh`?

**Answer:**

They are modern viewport height units:

* `svh` → Small viewport height
* `lvh` → Large viewport height
* `dvh` → Dynamic viewport height

Example:

```css
.hero {
    min-height: 100dvh;
}
```

They help address mobile browser viewport behavior.

---

# 160. What is the difference between `width: 100%` and `width: 100vw`?

**Answer:**

`100%` is generally relative to the containing block.

```css
width: 100%;
```

`100vw` is based on the viewport width.

```css
width: 100vw;
```

`100vw` can cause horizontal overflow in some situations because viewport units can include scrollbar-related width.

---

# 161. What is `min-content`?

**Answer:**

`min-content` represents a minimum intrinsic size based on the content's ability to wrap.

Example:

```css
width: min-content;
```

---

# 162. What is `max-content`?

**Answer:**

`max-content` represents the intrinsic size needed to display content without wrapping where possible.

```css
width: max-content;
```

---

# 163. What is `fit-content()`?

**Answer:**

`fit-content()` allows a size to grow up to a specified limit while respecting intrinsic sizing.

```css
width: fit-content(300px);
```

---

# 164. What is CSS logical property?

**Answer:**

Logical properties describe layout based on writing direction rather than physical left/right/top/bottom directions.

Example:

```css
margin-inline: auto;
padding-block: 20px;
```

Instead of:

```css
margin-left: auto;
margin-right: auto;
```

Logical properties are useful for internationalization and different writing modes.

---

# 165. What are `margin-inline` and `padding-block`?

**Answer:**

They are logical shorthand properties.

```css
margin-inline: auto;
```

controls the inline-start and inline-end margins.

```css
padding-block: 20px;
```

controls block-start and block-end padding.

---

# 166. What is `:is()`?

**Answer:**

`:is()` groups selectors.

Instead of:

```css
h1,
h2,
h3 {
    color: blue;
}
```

you can write:

```css
:is(h1, h2, h3) {
    color: blue;
}
```

Its specificity is based on the most specific argument in the `:is()` list.

---

# 167. What is `:where()`?

**Answer:**

`:where()` also groups selectors but always has **zero specificity**.

```css
:where(h1, h2, h3) {
    margin: 0;
}
```

This makes it useful for low-specificity defaults.

---

# 168. What is `:has()`?

**Answer:**

`:has()` is a relational pseudo-class that allows selecting an element based on its descendants or related elements.

Example:

```css
.card:has(img) {
    padding: 20px;
}
```

This selects `.card` elements containing an image.

---

# 169. What is `:empty`?

**Answer:**

`:empty` selects elements that have no child nodes.

```css
.box:empty {
    display: none;
}
```

Whitespace/text nodes can affect whether an element is considered empty.

---

# 170. What is `:root`?

**Answer:**

`:root` selects the document's root element.

For HTML documents, it normally selects `<html>`.

It is commonly used for CSS variables:

```css
:root {
    --primary-color: blue;
}
```

---

# 171. What is `::before`?

**Answer:**

It creates a generated pseudo-element before an element's content.

```css
.title::before {
    content: "★ ";
}
```

---

# 172. What is `::after`?

**Answer:**

It creates a generated pseudo-element after an element's content.

```css
.title::after {
    content: "";
    display: block;
}
```

---

# 173. Why is `content` required for `::before` and `::after`?

**Answer:**

Generated pseudo-elements normally require a `content` declaration to generate their box.

Example:

```css
.box::before {
    content: "";
}
```

---

# 174. What is CSS containment?

**Answer:**

CSS containment allows authors to isolate parts of a page for layout, paint, size, or style containment.

Example:

```css
.card {
    contain: layout paint;
}
```

Containment can improve performance in appropriate use cases but should be applied carefully.

---

# 175. What is `will-change`?

**Answer:**

`will-change` tells the browser that an element is likely to change certain properties.

```css
.box {
    will-change: transform;
}
```

It should not be applied everywhere because excessive use can increase memory usage and hurt performance.

---

# 176. What is `backdrop-filter`?

**Answer:**

`backdrop-filter` applies graphical effects to the content behind an element.

Example:

```css
.modal {
    backdrop-filter: blur(10px);
}
```

Browser support and visual fallbacks should be considered.

---

# 177. What is `filter`?

**Answer:**

`filter` applies graphical effects.

Examples:

```css
filter: blur(5px);
filter: grayscale(100%);
filter: brightness(80%);
filter: contrast(120%);
```

---

# 178. What is `mix-blend-mode`?

**Answer:**

It controls how an element's content blends with the content behind it.

```css
.title {
    mix-blend-mode: multiply;
}
```

---

# 179. What is `clip-path`?

**Answer:**

`clip-path` defines a clipping region.

Example:

```css
.circle {
    clip-path: circle(50%);
}
```

Another example:

```css
.shape {
    clip-path: polygon(
        50% 0,
        100% 100%,
        0 100%
    );
}
```

---

# 180. What is `mask-image`?

**Answer:**

CSS masking controls which parts of an element are visible using a mask image or gradient.

Example:

```css
.box {
    mask-image: linear-gradient(
        black,
        transparent
    );
}
```

Browser support should be checked for production requirements.

---

# 181. What is `linear-gradient()`?

**Answer:**

It creates a linear gradient.

```css
background: linear-gradient(
    90deg,
    blue,
    purple
);
```

---

# 182. What is `radial-gradient()`?

**Answer:**

It creates a radial gradient.

```css
background: radial-gradient(
    circle,
    white,
    blue
);
```

---

# 183. What is `conic-gradient()`?

**Answer:**

It creates a gradient around a center point.

```css
background: conic-gradient(
    red,
    yellow,
    green,
    red
);
```

---

# 184. What is CSS `color-mix()`?

**Answer:**

`color-mix()` creates a color by mixing colors in a specified color space.

Example:

```css
color: color-mix(
    in srgb,
    blue 70%,
    white
);
```

---

# 185. What is `currentColor` useful for?

**Answer:**

It allows related properties to automatically use the element's text color.

```css
.icon {
    color: blue;
    border: 2px solid currentColor;
}
```

If `color` changes, the border follows it.

---

# 186. What is the CSS cascade layer?

**Answer:**

Cascade layers provide an explicit way to organize author styles.

```css
@layer reset, base, components, utilities;
```

Example:

```css
@layer reset {
    * {
        box-sizing: border-box;
    }
}

@layer components {
    .button {
        padding: 10px;
    }
}
```

---

# 187. What is CSS specificity vs source order?

**Answer:**

Specificity is considered before source order.

Example:

```css
.text {
    color: blue;
}

p {
    color: red;
}
```

The class selector has greater specificity than the element selector, so blue wins even though the element selector appears later.

If specificity is equal, later applicable rules generally win.

---

# 188. How do you debug CSS?

**Answer:**

Use browser DevTools.

Common techniques:

1. Inspect the element.
2. Check the Styles panel.
3. Look for overridden properties.
4. Check computed styles.
5. Inspect the box model.
6. Check layout information.
7. Disable rules temporarily.
8. Inspect stacking contexts and z-index.
9. Test responsive breakpoints.

---

# 189. Why is CSS not applying?

**Answer:**

Common causes include:

* Incorrect selector
* CSS file not loaded
* Incorrect file path
* Syntax error
* Specificity conflict
* Rule overridden later
* Wrong media-query condition
* Invalid property/value
* Browser cache
* Incorrect cascade layer

---

# 190. How do you avoid CSS specificity problems?

**Answer:**

Good practices include:

* Prefer classes over IDs for styling
* Avoid deeply nested selectors
* Keep selectors simple
* Avoid unnecessary `!important`
* Use consistent naming
* Use cascade layers when appropriate
* Use component-scoped styles where appropriate

---

# 191. What is the difference between `opacity: 0` and `visibility: hidden`?

**Answer:**

```css
opacity: 0;
```

makes an element fully transparent but it can still participate in layout and may still receive interaction depending on the situation.

```css
visibility: hidden;
```

hides the element while normally preserving layout space and prevents it from being interactable as a visible element.

If you want to remove it from layout:

```css
display: none;
```

---

# 192. What is the difference between `relative`, `absolute`, `fixed`, and `sticky`?

**Answer:**

| Position   | Behavior                                            |
| ---------- | --------------------------------------------------- |
| `static`   | Normal flow                                         |
| `relative` | Normal flow + visual offset/reference               |
| `absolute` | Removed from normal flow                            |
| `fixed`    | Positioned relative to viewport in typical cases    |
| `sticky`   | Sticks within its scrolling context after threshold |

---

# 193. What is the difference between Flexbox `align-items` and `align-content`?

**Answer:**

`align-items` aligns individual flex items along the cross axis.

```css
.container {
    display: flex;
    align-items: center;
}
```

`align-content` distributes multiple flex lines along the cross axis.

```css
.container {
    display: flex;
    flex-wrap: wrap;
    align-content: center;
}
```

`align-content` has no meaningful effect when there is only one flex line.

---

# 194. What is the difference between `justify-items` and `justify-content`?

**Answer:**

`justify-items` controls the alignment of items inside their grid areas.

`justify-content` controls how the grid or flex content is distributed within the container.

Example:

```css
.container {
    display: grid;
    justify-items: center;
}
```

---

# 195. What is the difference between `gap` and margin?

**Answer:**

`gap` creates spacing between items in flex and grid layouts.

```css
.container {
    display: flex;
    gap: 20px;
}
```

Margin creates external spacing around an individual element.

```css
.item {
    margin: 20px;
}
```

`gap` is often preferable for consistent inter-item spacing.

---

# 196. How do you create a CSS triangle?

**Answer:**

One traditional approach uses borders.

```css
.triangle {
    width: 0;
    height: 0;

    border-left: 50px solid transparent;
    border-right: 50px solid transparent;
    border-bottom: 100px solid black;
}
```

---

# 197. How do you make an image responsive?

**Answer:**

A common pattern is:

```css
img {
    max-width: 100%;
    height: auto;
}
```

This prevents the image from exceeding its containing block while preserving its intrinsic aspect ratio.

---

# 198. How do you make a circular image?

**Answer:**

```css
img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
}
```

---

# 199. How do you create a CSS shadow?

**Answer:**

Use `box-shadow`.

```css
.card {
    box-shadow:
        0 4px 20px rgba(0, 0, 0, 0.15);
}
```

---

# 200. What is `text-shadow`?

**Answer:**

It creates a shadow behind text.

```css
h1 {
    text-shadow:
        2px 2px 4px gray;
}
```

---

# CSS Quick Revision

```text
CSS
│
├── Basics
│   ├── Syntax
│   ├── Selectors
│   ├── Properties
│   └── Values
│
├── Box Model
│   ├── Content
│   ├── Padding
│   ├── Border
│   └── Margin
│
├── Layout
│   ├── Block
│   ├── Inline
│   ├── Inline-block
│   ├── Flexbox
│   └── Grid
│
├── Position
│   ├── Static
│   ├── Relative
│   ├── Absolute
│   ├── Fixed
│   └── Sticky
│
├── Responsive
│   ├── Media Queries
│   ├── Mobile First
│   ├── Flexible Units
│   ├── clamp()
│   ├── min()
│   └── max()
│
├── Advanced
│   ├── Specificity
│   ├── Cascade
│   ├── Inheritance
│   ├── Variables
│   ├── Cascade Layers
│   ├── Container Queries
│   ├── Logical Properties
│   └── CSS Nesting
│
├── Effects
│   ├── Transition
│   ├── Animation
│   ├── Transform
│   ├── Filter
│   ├── Gradient
│   └── Shadow
│
└── Accessibility
    ├── Focus
    ├── Reduced Motion
    ├── Color Contrast
    └── Keyboard Navigation
```

# CSS Learning Roadmap

```text
HTML
 ↓
CSS Basics
 ↓
Selectors
 ↓
Box Model
 ↓
Display
 ↓
Position
 ↓
Flexbox
 ↓
Grid
 ↓
Responsive Design
 ↓
Media Queries
 ↓
Pseudo Classes
 ↓
Pseudo Elements
 ↓
Specificity
 ↓
Cascade
 ↓
CSS Variables
 ↓
Transitions
 ↓
Animations
 ↓
Advanced CSS
 ↓
CSS Architecture
 ↓
Performance
 ↓
Accessibility
```

# HTML + CSS + JavaScript

```text
HTML
   ↓
Structure

CSS
   ↓
Design + Layout

JavaScript
   ↓
Logic + Interaction

React
   ↓
Component-Based UI

Next.js
   ↓
Full-Stack React Framework
```

# Most Important CSS Interview Topics

For frontend interviews, prioritize these topics:

1. CSS Box Model
2. `box-sizing`
3. Selectors
4. Specificity
5. Cascade
6. Inheritance
7. `display`
8. Positioning
9. Flexbox
10. Grid
11. `z-index`
12. Responsive design
13. Media queries
14. `px`, `%`, `em`, `rem`, `vw`, `vh`
15. CSS variables
16. Pseudo-classes
17. Pseudo-elements
18. Transitions
19. Animations
20. Transform
21. `overflow`
22. `object-fit`
23. `min()`, `max()`, `clamp()`
24. Grid `auto-fit` / `auto-fill`
25. Accessibility
26. CSS performance
27. BEM
28. Cascade layers
29. Logical properties
30. Modern CSS features

```


# 🤝 Contributing

Contributions are welcome!

You can contribute by:

- Adding interview questions
- Improving explanations
- Fixing mistakes
- Updating outdated content
- Adding coding challenges
- Sharing interview experiences

---

# ⭐ Support

If this repository helped you,

⭐ Star the repository

🍴 Fork it

🐞 Open issues

💡 Suggest improvements

Every contribution helps the community.

---

# 📄 License

Licensed under the MIT License.
