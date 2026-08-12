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

A practical frontend learning path is:

```text
HTML
  ↓
CSS
  ↓
JavaScript
  ↓
DOM
  ↓
ES6+
  ↓
React
  ↓
React Hooks
  ↓
API Integration
  ↓
State Management
  ↓
Next.js
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
