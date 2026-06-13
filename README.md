# Day 1 - HTML Basics & Text Formatting

📚 Introduction

HTML (HyperText Markup Language) is used to create the structure of web pages. It uses tags to display content like headings, paragraphs, images, links, and more.

🧱 HTML Structure Tags

1. <!DOCTYPE html>

Defines that the document is an HTML5 document.

<!DOCTYPE html>

2. <html>

Root element of an HTML page.

<html>
</html>

3. <head>

Contains metadata such as title, styles, and links.

<head>
    <title>My Website</title>
</head>

4. <title>

Sets the title shown in the browser tab.

<title>My First Webpage</title>

5. <body>

Contains all visible content of the webpage.

<body>
    <h1>Hello World</h1>
</body>

✍️ Text Formatting Tags
## Heading Tags

Used to create headings.

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>

## Paragraph Tag
<p>This is a paragraph.</p>

## Line Break Tag
Hello<br>World

Output:

Hello
World

## Horizontal Line Tag
<hr>

Creates a horizontal line.

## Bold Tags
<b>Bold Text</b>

<strong>Important Text</strong>

## Italic Tags

<i>Italic Text</i>

<em>Emphasized Text</em>

## Underline Tag
<u>Underlined Text</u>

## Highlight Tag
<mark>Highlighted Text</mark> 

## Small Text Tag
<small>Small Text</small>

# Day 1 Summary

Today I learned:

- HTML document structure
- DOCTYPE declaration
- html, head, title and body tags
- Heading tags (h1 to h6)
- Paragraph tag
- Line break tag
- Horizontal rule tag
- Bold and Strong tags
- Italic and Emphasis tags
- Underline tag
- Mark tag
- Small tag

I also created a simple About Myself webpage.


## Day 2 - Links, Lists & Media

📚 Introduction

In this lesson, we learn how to create links, organize content using lists, and add media such as images, audio, and videos to a webpage.

🔗 Links
<a> Tag

Used to create hyperlinks.

<a href="https://www.google.com">Visit Google</a>

Open Link in New Tab

<a href="https://www.google.com" target="_blank">Visit Google</a>

## 📃 Lists

### Unordered List <ul>

Displays items with bullet points.

<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>
Output
HTML
CSS
JavaScript

### Ordered List <ol>

Displays items with numbers.

<ol>
    <li>Wake Up</li>
    <li>Study HTML</li>
    <li>Practice Coding</li>
</ol>
Output
Wake Up
Study HTML
Practice Coding

List Item <li>

Used inside <ul> and <ol>.

<li>HTML</li>

Description List
<dl> - Description List
<dt> - Description Term
<dd> - Description Definition
<dl>
    <dt>HTML</dt>
    <dd>HyperText Markup Language</dd>

    <dt>CSS</dt>
    <dd>Cascading Style Sheets</dd>
</dl>

## 🖼 Media Tags
Image Tag <img>

Used to display images.

<img src="profile.jpg" alt="Profile Image" width="200">

## Important Attributes

src → Image path
alt → Alternative text
width → Image width
height → Image height

## Audio Tag <audio>

Used to play audio files.

<audio controls>
    <source src="song.mp3" type="audio/mpeg">
</audio>

## Video Tag <video>

Used to play videos.

<video width="400" controls>
    <source src="video.mp4" type="video/mp4">
</video>

## Source Tag <source>

Used inside audio and video tags.

<source src="song.mp3" type="audio/mpeg">

## Track Tag <track>

Used for subtitles and captions.

<video controls>
    <source src="movie.mp4" type="video/mp4">

    <track
        src="subtitle.vtt"
        kind="subtitles"
        srclang="en"
        label="English">
</video>

# Day 2 Summary

Today I learned:

- Hyperlinks using the anchor tag
- Unordered lists
- Ordered lists
- List items
- Description lists
- Image tag
- Audio tag
- Video tag
- Source tag
- Track tag

I also created a My Profile Page using links, images, and lists.




# 📅 Day 3 - HTML Tables and Forms

## 📖 Introduction

On Day 3, I learned how to create tables and forms in HTML.

Tables help organize data into rows and columns, while forms allow users to enter and submit information.

---

# 📚 HTML Table Tags

## 1. `<table>`

### Definition

The `<table>` tag is used to create a table in HTML.

### Syntax

```html
<table>
  ...
</table>
```

### Example

```html
<table>
  <tr>
    <td>Name</td>
    <td>Age</td>
  </tr>
</table>
```

---

## 2. `<tr>`

### Definition

The `<tr>` tag stands for Table Row. It creates a row inside a table.

### Syntax

```html
<tr>
  ...
</tr>
```

### Example

```html
<tr>
  <td>John</td>
  <td>20</td>
</tr>
```

---

## 3. `<td>`

### Definition

The `<td>` tag stands for Table Data. It creates a normal cell inside a row.

### Syntax

```html
<td>Data</td>
```

### Example

```html
<td>John</td>
```

---

## 4. `<th>`

### Definition

The `<th>` tag stands for Table Header. It creates a heading cell.

### Syntax

```html
<th>Heading</th>
```

### Example

```html
<th>Name</th>
<th>Age</th>
```

---

## 5. `<thead>`

### Definition

The `<thead>` tag groups the header section of a table.

### Syntax

```html
<thead>
  ...
</thead>
```

### Example

```html
<thead>
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
</thead>
```

---

## 6. `<tbody>`

### Definition

The `<tbody>` tag contains the main table data.

### Syntax

```html
<tbody>
  ...
</tbody>
```

### Example

```html
<tbody>
  <tr>
    <td>John</td>
    <td>20</td>
  </tr>
</tbody>
```

---

## 7. `<tfoot>`

### Definition

The `<tfoot>` tag defines the footer section of a table.

### Syntax

```html
<tfoot>
  ...
</tfoot>
```

### Example

```html
<tfoot>
  <tr>
    <td colspan="2">End of Table</td>
  </tr>
</tfoot>
```

---

## 8. `<caption>`

### Definition

The `<caption>` tag provides a title for a table.

### Syntax

```html
<caption>Table Title</caption>
```

### Example

```html
<caption>Student Data</caption>
```

---

# 📚 HTML Form Tags

## 9. `<form>`

### Definition

The `<form>` tag is used to collect user input.

### Syntax

```html
<form>
  ...
</form>
```

### Example

```html
<form>
  <input type="text">
</form>
```

---

## 10. `<input>`

### Definition

The `<input>` tag creates input fields for users.

### Syntax

```html
<input type="text">
```

### Example

```html
<input type="email" placeholder="Enter Email">
```

---

## 11. `<label>`

### Definition

The `<label>` tag provides a text label for form elements.

### Syntax

```html
<label>Name</label>
```

### Example

```html
<label for="name">Student Name</label>
```

---

## 12. `<button>`

### Definition

The `<button>` tag creates a clickable button.

### Syntax

```html
<button>Submit</button>
```

### Example

```html
<button type="submit">Register</button>
```

---

## 13. `<textarea>`

### Definition

The `<textarea>` tag creates a multi-line text input area.

### Syntax

```html
<textarea></textarea>
```

### Example

```html
<textarea placeholder="Write here"></textarea>
```

---

# 🛠 Practice Project 1 - Student Registration Form

### Features

* Student Name
* Email
* Phone Number
* Course
* Address
* Submit Button

---

# 🛠 Practice Project 2 - Student Data Table

### Features

* Student ID
* Name
* Course
* Age
* Marks
* Footer Row


# 📋 Day 3 Summary

Today I learned:

✅ Creating tables using `<table>`

✅ Creating rows using `<tr>`

✅ Adding table data using `<td>`

✅ Creating table headings using `<th>`

✅ Organizing tables using `<thead>`, `<tbody>`, and `<tfoot>`

✅ Adding table titles using `<caption>`

✅ Creating forms using `<form>`

✅ Taking user input using `<input>`

✅ Adding labels using `<label>`

✅ Creating buttons using `<button>`

✅ Creating multi-line text areas using `<textarea>`




# 📅 Day 4 - Advanced Forms & Semantic HTML

* Advanced Form Elements
* Semantic HTML Tags
* Building a complete Blog Page Layout
* Creating structured and meaningful web pages

---

# 📖 Notes

## 🧩 Advanced Form Elements

Advanced form elements help users enter data more efficiently and improve the user experience.

---

## 1️⃣ `<select>`

### Definition

The `<select>` tag creates a dropdown list.

### Purpose

Allows users to choose one option from multiple choices.

### Syntax

```html
<select>
  <option>Option 1</option>
  <option>Option 2</option>
</select>
```

### Example

```html
<label for="course">Choose a Course:</label>

<select id="course">
  <option>HTML</option>
  <option>CSS</option>
  <option>JavaScript</option>
</select>
```

---

## 2️⃣ `<option>`

### Definition

The `<option>` tag defines an item inside a dropdown list.

### Purpose

Represents a selectable value.

### Syntax

```html
<option>HTML</option>
```

### Example

```html
<select>
  <option>HTML</option>
  <option>CSS</option>
  <option>JavaScript</option>
</select>
```

---

## 3️⃣ `<optgroup>`

### Definition

The `<optgroup>` tag groups related options inside a dropdown.

### Purpose

Makes long dropdown lists more organized.

### Syntax

```html
<optgroup label="Group Name">
  <option>Item</option>
</optgroup>
```

### Example

```html
<select>

  <optgroup label="Asia">
    <option>India</option>
    <option>Japan</option>
  </optgroup>

  <optgroup label="Europe">
    <option>France</option>
    <option>Germany</option>
  </optgroup>

</select>
```

---

## 4️⃣ `<fieldset>`

### Definition

The `<fieldset>` tag groups related form fields.

### Purpose

Improves form structure and readability.

### Syntax

```html
<fieldset>
  Form Elements
</fieldset>
```

### Example

```html
<fieldset>

  <input type="text" placeholder="Name">

  <input type="email" placeholder="Email">

</fieldset>
```

---

## 5️⃣ `<legend>`

### Definition

The `<legend>` tag provides a title for a fieldset.

### Purpose

Describes the grouped form fields.

### Syntax

```html
<fieldset>
  <legend>User Information</legend>
</fieldset>
```

### Example

```html
<fieldset>

  <legend>Personal Details</legend>

  <input type="text" placeholder="Name">

</fieldset>
```

---

## 6️⃣ `<datalist>`

### Definition

The `<datalist>` tag provides suggested values for an input field.

### Purpose

Helps users by showing autocomplete suggestions.

### Syntax

```html
<input list="skills">

<datalist id="skills">
  <option value="HTML">
</datalist>
```

### Example

```html
<input type="text" list="languages">

<datalist id="languages">
  <option value="HTML">
  <option value="CSS">
  <option value="JavaScript">
</datalist>
```

---

# 🧠 Semantic HTML Tags

Semantic tags clearly describe the meaning of the content.

They help:

* Developers
* Search Engines
* Screen Readers
* Accessibility Tools

understand the structure of a webpage.

---

## 1️⃣ `<header>`

### Definition

Represents the top section of a webpage or section.

### Purpose

Contains logo, title, navigation, etc.

### Syntax

```html
<header>
  Content
</header>
```

### Example

```html
<header>
  <h1>My Blog</h1>
</header>
```

---

## 2️⃣ `<footer>`

### Definition

Represents the bottom section of a webpage.

### Purpose

Contains copyright information, contact details, links, etc.

### Syntax

```html
<footer>
  Content
</footer>
```

### Example

```html
<footer>
  <p>© 2025 My Blog</p>
</footer>
```

---

## 3️⃣ `<section>`

### Definition

Represents a standalone section of content.

### Purpose

Groups related content together.

### Syntax

```html
<section>
  Content
</section>
```

### Example

```html
<section>
  <h2>About Us</h2>
</section>
```

---

## 4️⃣ `<article>`

### Definition

Represents independent content.

### Purpose

Used for blogs, news articles, posts, etc.

### Syntax

```html
<article>
  Content
</article>
```

### Example

```html
<article>
  <h2>HTML Basics</h2>
</article>
```

---

## 5️⃣ `<aside>`

### Definition

Represents sidebar or related content.

### Purpose

Displays extra information.

### Syntax

```html
<aside>
  Content
</aside>
```

### Example

```html
<aside>
  Related Posts
</aside>
```

---

## 6️⃣ `<nav>`

### Definition

Represents navigation links.

### Purpose

Provides website navigation.

### Syntax

```html
<nav>
  Links
</nav>
```

### Example

```html
<nav>
  <a href="#">Home</a>
  <a href="#">Blog</a>
</nav>
```

---

## 7️⃣ `<main>`

### Definition

Represents the primary content of the page.

### Purpose

Contains the most important content.

### Syntax

```html
<main>
  Main Content
</main>
```

### Example

```html
<main>
  <h2>Welcome</h2>
</main>
```

---

# ❓ Why Semantic HTML is Important

| Benefit                  | Description                              |
| ------------------------ | ---------------------------------------- |
| Better Readability       | Easier to understand code                |
| SEO Friendly             | Search engines understand content better |
| Accessibility            | Helps screen readers                     |
| Easier Maintenance       | Cleaner code structure                   |
| Professional Development | Industry best practice                   |

---

# ⚖️ Semantic vs Non-Semantic Tags

| Semantic Tags        | Non-Semantic Tags     |
| -------------------- | --------------------- |
| `<header>`           | `<div>`               |
| `<footer>`           | `<span>`              |
| `<nav>`              | `<div>`               |
| `<article>`          | `<div>`               |
| Meaningful           | No meaning            |
| Better SEO           | Less SEO-friendly     |
| Better Accessibility | Limited accessibility |

### Example

❌ Non-Semantic

```html
<div class="header">
  My Blog
</div>
```

✅ Semantic

```html
<header>
  My Blog
</header>
```

---

# 🛠 Practice Project

Create a blog website that includes:

* Header
* Navigation
* Articles
* Sidebar
* Footer
* Category Dropdown
* Country Dropdown using optgroup
* Search Suggestions using datalist
* User Information Form using fieldset and legend

---

# 📰 Blog Page Layout Project

### Features

✅ Header

✅ Navigation Menu

✅ Main Content

✅ Multiple Blog Articles

✅ Sidebar

✅ Footer

✅ Advanced Form Elements


# 📋 Day Summary

| Topic    | Learned             |
| -------- | ------------------- |
| select   | Dropdown Menu       |
| option   | Dropdown Items      |
| optgroup | Group Options       |
| fieldset | Form Grouping       |
| legend   | Fieldset Title      |
| datalist | Input Suggestions   |
| header   | Top Section         |
| nav      | Navigation          |
| main     | Main Content        |
| section  | Content Group       |
| article  | Independent Content |
| aside    | Sidebar             |
| footer   | Bottom Section      |

---

# 🎯 Key Takeaways

✅ Semantic tags give meaning to content.

✅ Semantic HTML improves SEO.

✅ Semantic HTML improves accessibility.

✅ `fieldset` groups related form controls.

✅ `legend` labels a fieldset.

✅ `datalist` provides suggestions.

✅ `select` creates dropdown menus.

✅ `optgroup` organizes dropdown options.

✅ Professional websites use semantic structure.

---

# ❌ Common Beginner Mistakes

| Mistake                           | Solution                     |
| --------------------------------- | ---------------------------- |
| Using too many divs               | Use semantic tags            |
| Forgetting legend inside fieldset | Always provide a title       |
| Using option outside select       | Keep option inside select    |
| Confusing datalist with select    | datalist allows typing       |
| Multiple headers everywhere       | Use logically                |
| Missing nav tag                   | Wrap navigation links in nav |
| Using section without heading     | Add meaningful headings      |


