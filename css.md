Here's your full **Week 2: Advanced HTML** **tutor lecture guide** for **Session 1 (Forms)** and **Session 2 (Multimedia Elements)** in clean **Markdown (`.md`) format**, designed to help you **teach clearly and professionally** with code examples, explanations, and exercises.

---

````md
# 💻 Front-End Web Development – Week 2: Advanced HTML

---

## 📘 SESSION 1: Creating HTML Forms

---

### ✅ What are HTML Forms?

- Forms are used to collect user input.
- The data entered can be sent to a server or processed on the frontend.

### 🔹 Basic Structure

```html
<form action="/submit" method="POST">
  <!-- form elements go here -->
</form>
````

* `action`: Where the form data should be sent
* `method`: HTTP method (`GET` or `POST`)

---

### ✅ Form Elements

#### 1. Input

```html
<label for="name">Name:</label>
<input type="text" id="name" name="name">
```

| Type                 | Use                    |
| -------------------- | ---------------------- |
| `text`               | Single-line text input |
| `email`              | Validates email format |
| `password`           | Hides typed characters |
| `number`             | Accepts only numbers   |
| `date`               | Date picker            |
| `checkbox` / `radio` | Selectable options     |

---

#### 2. Textarea

```html
<label for="message">Your Message:</label>
<textarea id="message" name="message" rows="5" cols="30"></textarea>
```

---

#### 3. Select Dropdown

```html
<label for="gender">Gender:</label>
<select id="gender" name="gender">
  <option value="">--Select--</option>
  <option value="male">Male</option>
  <option value="female">Female</option>
</select>
```

---

#### 4. Button

```html
<button type="submit">Submit</button>
```

---

### ✅ Form Attributes & Validation

| Attribute      | Purpose                          |
| -------------- | -------------------------------- |
| `required`     | Prevents empty submission        |
| `placeholder`  | Shows hint text inside field     |
| `maxlength`    | Limits characters allowed        |
| `pattern`      | Defines input format using regex |
| `type="email"` | Validates email format           |

#### Example with Validation

```html
<form>
  <input type="text" name="name" placeholder="Enter full name" required><br>
  <input type="email" name="email" placeholder="Enter email" required><br>
  <textarea placeholder="Your message" required></textarea><br>
  <button type="submit">Send</button>
</form>
```

---

### 🧪 Practice Task

**Build a Contact Form**

* Name, Email, Message fields
* Use `placeholder` and `required` attributes
* Add a `submit` button

---

## 📘 SESSION 2: Multimedia Elements

---

### ✅ Adding Images

```html
<img src="https://via.placeholder.com/150" alt="Profile Image">
```

* `src`: Image URL
* `alt`: Describes the image (important for accessibility)

---

### ✅ Adding Audio

```html
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
  Your browser does not support the audio tag.
</audio>
```

* `controls`: Adds play/pause
* Replace `audio.mp3` with a valid audio file

---

### ✅ Adding Video

```html
<video width="400" controls>
  <source src="video.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```

* `controls`: Adds video controls
* `width`, `height`: Set size

---

### ✅ Embedding External Content

#### 📺 Embed YouTube Video

```html
<iframe width="560" height="315"
  src="https://www.youtube.com/embed/dQw4w9WgXcQ"
  title="YouTube video player"
  frameborder="0"
  allowfullscreen>
</iframe>
```

> Replace the URL with any YouTube embed link.

---

#### 🗺️ Embed Google Map

```html
<iframe
  src="https://www.google.com/maps/embed?pb=!1m18..."
  width="600" height="450"
  style="border:0;"
  allowfullscreen=""
  loading="lazy">
</iframe>
```

> Go to Google Maps → Share → Embed a map → Copy the `<iframe>` code.

---

### 🧪 Practice Task

**Create a Multimedia Profile Page**
Include:

* A profile image
* An intro audio clip
* A short hobby video
* An embedded YouTube video or Google Map

---

## 🎯 Summary

| Concept       | What You Learned                        |
| ------------- | --------------------------------------- |
| Forms         | Used to collect and validate user input |
| Form Elements | `input`, `textarea`, `select`, `button` |
| Validation    | `required`, `placeholder`, `type`, etc. |
| Multimedia    | Add images, audio, video, and embeds    |
| Embeds        | Use `<iframe>` for YouTube, maps, etc.  |

---

## 📚 Resources

* [W3Schools HTML Forms](https://www.w3schools.com/html/html_forms.asp)
* [MDN Multimedia HTML](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
* [Google Maps Embed Help](https://support.google.com/maps/answer/144361?hl=en)

---