# 🎓 Front-End Web Development – Week 4

## 📘 Session 1: Advanced CSS Techniques

In this session, students will learn:

- How to build grid-based layouts using **CSS Grid**
- How to make responsive designs using **media queries**
- How to add interactivity with **transitions and animations**

---

## ✅ 1. CSS Grid Layout

CSS Grid is a powerful tool for creating two-dimensional layouts (rows & columns).

### 🔹 Basic Grid Example

```html
<style>
  .grid-container {
    display: grid;
    grid-template-columns: 1fr 2fr 1fr;
    gap: 10px;
  }

  .grid-item {
    background-color: #cce5ff;
    padding: 20px;
    text-align: center;
    border: 1px solid #007bff;
  }
</style>

<div class="grid-container">
  <div class="grid-item">Column 1</div>
  <div class="grid-item">Column 2</div>
  <div class="grid-item">Column 3</div>
</div>
````

### 🔹 Explanation:

* `display: grid` activates grid layout.
* `grid-template-columns: 1fr 2fr 1fr` defines 3 columns (fractions).
* `gap` adds spacing between grid items.

---

### 🔹 Grid Auto Layout (Repeat + Minmax)

```css
grid-template-columns: repeat(3, minmax(100px, 1fr));
```

* `repeat(3, ...)`: repeats the column 3 times.
* `minmax(100px, 1fr)`: ensures columns shrink/grow responsively.

---

## ✅ 2. Media Queries for Responsive Design

Media queries make your website adapt to different screen sizes.

### 🔹 Basic Syntax:

```css
@media (max-width: 768px) {
  body {
    background-color: lightgray;
  }

  .grid-container {
    grid-template-columns: 1fr; /* Stack columns vertically */
  }
}
```

### 🔹 Common Breakpoints

| Device   | Max Width |
| -------- | --------- |
| Phones   | 600px     |
| Tablets  | 768px     |
| Laptops  | 992px     |
| Desktops | 1200px    |

---

## ✅ 3. CSS Transitions and Animations

### 🔹 Transitions

```css
.button {
  background-color: #007bff;
  color: white;
  padding: 10px 20px;
  transition: background-color 0.3s ease;
}

.button:hover {
  background-color: #0056b3;
}
```

* Smoothly transitions between the two background colors on hover.

---

### 🔹 Basic Animation

```html
<style>
  .box {
    width: 100px;
    height: 100px;
    background: tomato;
    animation: slide 2s infinite alternate;
  }

  @keyframes slide {
    from {
      transform: translateX(0);
    }
    to {
      transform: translateX(200px);
    }
  }
</style>

<div class="box"></div>
```

---

## 💻 Practice Exercises

### 1. **Create a 3-column Grid Layout**

* Use `CSS Grid` to build a section with three side-by-side cards.

### 2. **Make the Layout Responsive**

* Add a `media query` that stacks the grid columns on mobile.

### 3. **Add Transitions and Hover Effects**

* Create a button that changes color or size on hover using `transition`.

### 4. **Build a Simple Animation**

* Animate a box that moves left to right using `@keyframes`.

---

## 🎯 Key Takeaways

| Concept       | Summary                               |
| ------------- | ------------------------------------- |
| CSS Grid      | Great for 2D layouts (rows + columns) |
| Media Queries | Used for responsive design            |
| Transitions   | Smooth changes between states         |
| Animations    | Moving elements with keyframes        |

---

## 📚 Recommended Resources

* [CSS Grid – MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout)
* [Responsive Design – W3Schools](https://www.w3schools.com/css/css_rwd_mediaqueries.asp)
* [CSS Animations – MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations)

---