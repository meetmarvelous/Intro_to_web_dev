# 🌐 Front-End Web Development - Week 1

## 📘 Session 1: Introduction to HTML

---

## ✅ 1. What is HTML?

- HTML stands for **HyperText Markup Language**.
- It is used to **structure content** on the web.
- HTML is the **foundation** of every web page.

---

## ✅ 2. Structure of an HTML Document

Every HTML page follows this basic structure:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Web Page</title>
  </head>
  <body>
    <!-- Visible content goes here -->
  </body>
</html>
````

### 🔍 Explanation:

| Tag               | Role                                          |
| ----------------- | --------------------------------------------- |
| `<!DOCTYPE html>` | Tells the browser the version of HTML (HTML5) |
| `<html>`          | Root of the document                          |
| `<head>`          | Contains metadata like title, links, SEO      |
| `<title>`         | Page title (shown on browser tab)             |
| `<body>`          | All the visible content                       |

---

## ✅ 3. Basic HTML Tags & Elements

### 🔹 a. Headings

Headings are used to define titles and subheadings.

```html
<h1>This is a Main Heading</h1>
<h2>This is a Subheading</h2>
<h3>Smaller Subheading</h3>
```

🧠 Tip: Use only **one `<h1>`** per page for SEO and accessibility.

---

### 🔹 b. Paragraphs

Paragraphs are used to write blocks of text.

```html
<p>This is a paragraph of text. HTML ignores extra spaces or line breaks.</p>
```

---

### 🔹 c. Links

Links allow you to navigate to other pages or websites.

```html
<a href="https://www.google.com">Visit Google</a>
```

* `href` is the **attribute** that stores the destination URL.
* The text inside `<a>` is clickable.

---

### 🔹 d. Images

Images are inserted using the `<img>` tag.

```html
<img src="https://via.placeholder.com/150" alt="Placeholder image">
```

* `src` is the image URL.
* `alt` is the alternative text (important for accessibility).

---

## 🛠️ Complete Mini Example

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Bio Page</title>
  </head>
  <body>
    <h1>Hi, I'm Jane Doe</h1>
    <p>I love designing beautiful websites.</p>

    <h2>My Favorite Website</h2>
    <a href="https://www.wikipedia.org">Visit Wikipedia</a>

    <h2>Here's What I Look Like</h2>
    <img src="https://via.placeholder.com/200" alt="Jane's profile picture">
  </body>
</html>
```

---

## 💻 Practice Exercise (For Students)

**Create a Simple “About Me” Page**

* Use the following tags: `<h1>`, `<p>`, `<a>`, `<img>`
* Add:

  * Your name
  * A short paragraph about you
  * A link to your favorite website
  * A profile photo (or placeholder)

🎯 Save it as `about-me.html` and test it in your browser.

---

## 🎯 Key Takeaways

* HTML uses **tags** to organize and format content.
* Every page has a **head** and **body**.
* Learn the purpose of each basic tag.
* Always **nest tags properly** and close them.

---

## 🧠 Fun Tip:

Try opening your `.html` file in the browser, then right-click and choose **"View Page Source"** — that's HTML in action!

---

## 📚 Extra Resources

* [W3Schools HTML Tutorial](https://www.w3schools.com/html/)
* [MDN HTML Docs (Mozilla)](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [HTML Cheat Sheet](https://web.stanford.edu/group/csp/cs21/htmlcheatsheet.pdf)

---