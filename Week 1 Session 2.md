# 🧑‍🏫 Front-End Web Development - Week 1 Lecture Guide

---

## 📘 SESSION 2: HTML Document Structure

### ✅ 1. DOCTYPE, `<html>`, `<head>`, `<body>` Tags

#### 🔹 `<!DOCTYPE html>`
- Declares the document as HTML5.
- Always placed at the very top of the document.

```html
<!DOCTYPE html>
````

#### 🔹 `<html>`

* Root element of the HTML document.

#### 🔹 `<head>`

* Contains **metadata**: title, links, scripts, styles, meta info.
* Not rendered visually on the webpage.

#### 🔹 `<body>`

* Contains all visible elements of the webpage: text, images, links, etc.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Web Page</title>
  </head>
  <body>
    <h1>Hello World</h1>
    <p>This is a paragraph.</p>
  </body>
</html>
```

---

### ✅ 2. Meta Tags and Their Importance

Meta tags provide information about the page to browsers and search engines.

#### Examples:

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="This is a beginner HTML tutorial.">
```

| Tag               | Purpose                     |
| ----------------- | --------------------------- |
| `charset="UTF-8"` | Character encoding          |
| `viewport`        | Responsive design on mobile |
| `description`     | SEO snippet                 |

---

### ✅ 3. Semantic HTML Elements

Semantic elements describe the **meaning** of the content.

| Element     | Purpose                               |
| ----------- | ------------------------------------- |
| `<header>`  | Top section, logo/navigation          |
| `<footer>`  | Bottom section, copyright             |
| `<article>` | Independent content (e.g., blog post) |
| `<section>` | Thematic group of content             |
| `<nav>`     | Navigation links                      |
| `<main>`    | Primary content                       |
| `<aside>`   | Side content, ads, sidebars           |

#### Example:

```html
<main>
  <header>
    <h1>Welcome to My Blog</h1>
  </header>

  <article>
    <h2>HTML Basics</h2>
    <p>This article explains basic HTML tags.</p>
  </article>

  <footer>
    <p>&copy; 2025 My Blog</p>
  </footer>
</main>
```

---

# 📘 WEEK 2: Advanced HTML

---

## 🧪 SESSION 1: Creating HTML Forms

### ✅ 1. Form Elements

```html
<form>
  <label for="name">Name:</label>
  <input type="text" id="name" name="name"><br><br>

  <label for="bio">About You:</label><br>
  <textarea id="bio" name="bio"></textarea><br><br>

  <label for="gender">Gender:</label>
  <select id="gender" name="gender">
    <option value="male">Male</option>
    <option value="female">Female</option>
  </select><br><br>

  <button type="submit">Submit</button>
</form>
```

### ✅ 2. Form Attributes and Validation

| Attribute     | Description              |
| ------------- | ------------------------ |
| `action`      | URL to send form data to |
| `method`      | `GET` or `POST`          |
| `required`    | Makes a field mandatory  |
| `placeholder` | Shows hint text          |
| `maxlength`   | Max character length     |

```html
<form action="/submit" method="POST">
  <input type="email" placeholder="Email" required>
  <input type="text" maxlength="30">
  <button type="submit">Send</button>
</form>
```

---

## 🎵 SESSION 2: Multimedia Elements

### ✅ 1. Adding Images

```html
<img src="https://via.placeholder.com/200" alt="Placeholder Image">
```

### ✅ 2. Adding Audio

```html
<audio controls>
  <source src="music.mp3" type="audio/mpeg">
  Your browser does not support audio.
</audio>
```

### ✅ 3. Adding Video

```html
<video width="320" height="240" controls>
  <source src="video.mp4" type="video/mp4">
  Your browser does not support video.
</video>
```

### ✅ 4. Embedding Content (Iframes)

```html
<iframe src="https://www.wikipedia.org" width="600" height="400" title="Wikipedia"></iframe>
```

#### 🔹 Embedding Maps (Google Maps Example)

```html
<iframe 
  src="https://www.google.com/maps/embed?pb=!1m18..." 
  width="600" height="450" 
  style="border:0;" allowfullscreen="" 
  loading="lazy">
</iframe>
```

---

## 📝 Suggested Practice Exercises

### 1. Create a “Contact Us” form

* Fields: Name, Email, Message
* Add validation and placeholders

### 2. Embed a YouTube video into a basic HTML page

* Use `<iframe>` to embed the video

### 3. Build a multimedia profile page

* Add a profile image, intro audio, and a short video about a hobby

---