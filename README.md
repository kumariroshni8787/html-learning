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
