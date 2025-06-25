# 🎓 Front-End Web Development - Week 3: CSS Fundamentals

---

## 🧠 Week Overview
In this week, students will:
- Learn how to write and apply CSS to HTML documents
- Style text, boxes, and layouts
- Understand the CSS box model
- Explore display types and positioning
- Get introduced to Flexbox for responsive design

---

# 📘 Session 1: Introduction to CSS

---

## ✅ 1. CSS Syntax & Selectors

### 🔹 Basic Syntax:
```css
selector {
  property: value;
}
````

### 🔹 Example:

```css
p {
  color: blue;
  font-size: 18px;
}
```

### 🔹 Types of Selectors:

| Selector   | Description                    | Example      |
| ---------- | ------------------------------ | ------------ |
| Type       | Targets all elements of a type | `h1 {}`      |
| Class      | Targets elements with a class  | `.box {}`    |
| ID         | Targets one unique element     | `#header {}` |
| Descendant | Targets nested elements        | `div p {}`   |

---

## ✅ 2. Styling Text and Backgrounds

### 🔹 Text Styling:

```css
h1 {
  color: darkred;
  font-family: Arial, sans-serif;
  text-align: center;
  text-decoration: underline;
}
```

### 🔹 Background Styling:

```css
body {
  background-color: #f5f5f5;
}

div {
  background-image: url('bg.jpg');
  background-size: cover;
}
```

---

## ✅ 3. The Box Model

Every HTML element is a box with:

* **Content**: Text or image
* **Padding**: Space between content and border
* **Border**: Edge of the box
* **Margin**: Space outside the box

### 🔹 Visual Example:

```css
.box {
  width: 300px;
  padding: 20px;
  border: 2px solid black;
  margin: 30px;
  background-color: lightyellow;
}
```

```html
<div class="box">I am a box!</div>
```

### 🔹 Box Model Diagram (Explain using a drawing or diagram in class)

---

## 💻 Practice Exercise 1

**Task**: Style a personal bio page

* Add background color to `body`
* Center `h1` with text color
* Create a `.card` class with padding, margin, and border

---

# 📘 Session 2: Layout with CSS

---

## ✅ 1. Display Properties

### 🔹 `block`

* Takes full width
* Starts on a new line (e.g. `<div>`, `<p>`)

### 🔹 `inline`

* Respects content width
* Stays in line (e.g. `<span>`, `<a>`)

### 🔹 `inline-block`

* Like inline, but allows width/height

### 🔹 Example:

```css
span {
  display: block;
  margin: 10px;
  background-color: lightblue;
}
```

---

## ✅ 2. Positioning Elements

| Property   | Effect                                             |
| ---------- | -------------------------------------------------- |
| `static`   | Default (normal flow)                              |
| `relative` | Positioned relative to itself                      |
| `absolute` | Positioned relative to nearest positioned ancestor |
| `fixed`    | Positioned relative to viewport                    |

### 🔹 Example:

```css
.box {
  position: relative;
  top: 20px;
  left: 30px;
}
```

```html
<div class="box">Moved box</div>
```

---

## ✅ 3. Flexbox Basics

Flexbox allows you to layout items in a row or column, and control spacing, alignment, and sizing.

### 🔹 Parent Container:

```css
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
```

### 🔹 Child Elements:

```html
<div class="container">
  <div class="item">One</div>
  <div class="item">Two</div>
  <div class="item">Three</div>
</div>
```

### 🔹 Key Properties:

| Property          | Description          |
| ----------------- | -------------------- |
| `display: flex`   | Activates flexbox    |
| `justify-content` | Horizontal alignment |
| `align-items`     | Vertical alignment   |
| `flex-direction`  | Row or column        |

---

## 💻 Practice Exercise 2

**Task**: Create a navigation bar using Flexbox

* Items aligned horizontally
* Space between links
* Add hover effect

---

## 🧪 Extra Practice Challenge

**Build a Pricing Card Layout**:

* Use `.card` boxes for 3 plans
* Use Flexbox to align them side-by-side
* Add text, background, and padding styles

---

# 🎯 Key Takeaways

* CSS lets us style and layout HTML pages
* Understanding the box model is crucial
* Flexbox makes layouts flexible and responsive
* Practice is key: build and tweak small UIs regularly

---

# 📚 Resources for Students

* [CSS Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
* [MDN CSS Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)
* [Flexbox Froggy Game](https://flexboxfroggy.com/)

---
