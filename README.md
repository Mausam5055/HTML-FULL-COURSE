---

# HTML Full Course

Welcome to the **HTML Full Course**! This repository contains all the materials and code examples you need to learn HTML from the ground up. Whether you're a beginner or looking to refresh your skills, this course will help you master HTML to build websites.

## Table of Contents

1. [Course Overview](#course-overview)
2. [Prerequisites](#prerequisites)
3. [Installation](#installation)
4. [Course Structure](#course-structure)
5. [Code Examples](#code-examples)
6. [Exercises](#exercises)
7. [License](#license)

---

## Course Overview

This repository is designed to guide you through learning HTML. The course covers the following topics:

- Introduction to HTML
- HTML structure and elements
- Text formatting and links
- Images, lists, and tables
- Forms and input elements
- HTML5 semantic elements
- Multimedia in HTML (audio, video)
- Accessibility in HTML
- HTML best practices and optimization

Each section includes code examples with explanations and exercises to help you practice and understand the concepts.

---

## Prerequisites

Before starting this course, you should have:

- A text editor (e.g., VS Code, Sublime Text)
- A web browser (e.g., Chrome, Firefox) to test your HTML pages

No prior coding experience is required, but having a basic understanding of how websites work will be helpful.

---

## Installation

### 1. Clone the repository:

```bash
git clone https://github.com/yourusername/html-full-course.git
```

### 2. Navigate to the project directory:

```bash
cd html-full-course
```

### 3. Open the files in your browser to view the HTML content.
- You can open any `.html` file directly in your web browser by double-clicking it, or using the following command:

```bash
open index.html
```

No installation is needed for HTML files.

---

## Course Structure

The course is divided into topics, and each topic contains HTML files demonstrating various concepts. Below is the directory structure:

```
html-full-course/
│
├── 01_introduction/
│   └── index.html
├── 02_text_formatting/
│   └── index.html
├── 03_images_and_links/
│   └── index.html
├── 04_lists_and_tables/
│   └── index.html
├── 05_forms_and_inputs/
│   └── index.html
├── 06_semantic_elements/
│   └── index.html
├── 07_multimedia/
│   └── index.html
└── 08_accessibility/
    └── index.html
```

---

## Code Examples

Here are a few basic examples to get you started with HTML:

### 1. Basic HTML Structure (introduction/index.html)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic HTML Structure</title>
</head>
<body>
    <h1>Welcome to HTML!</h1>
    <p>This is your first HTML document.</p>
</body>
</html>
```

#### Running the example:
1. Open `index.html` in your browser to view the page.

---

### 2. Text Formatting and Links (text_formatting/index.html)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Text Formatting</title>
</head>
<body>
    <h1>Text Formatting in HTML</h1>
    <p>This is <b>bold</b> text, <i>italic</i> text, and <u>underlined</u> text.</p>
    <p>Learn more at <a href="https://www.w3schools.com">W3Schools</a>.</p>
</body>
</html>
```

---

### 3. Images and Links (images_and_links/index.html)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Images and Links</title>
</head>
<body>
    <h1>Images and Links in HTML</h1>
    <img src="https://www.example.com/logo.png" alt="Example Logo" width="300">
    <p>Visit <a href="https://www.example.com">Example Website</a> for more information.</p>
</body>
</html>
```

---

### 4. Forms and Input Elements (forms_and_inputs/index.html)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Forms and Inputs</title>
</head>
<body>
    <h1>HTML Form Example</h1>
    <form action="/submit" method="POST">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        <br><br>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <br><br>
        <button type="submit">Submit</button>
    </form>
</body>
</html>
```

---

## Exercises

Here are a few exercises to practice after going through the examples:

1. **Create a webpage with a heading, paragraph, and an image.**
2. **Build a simple form that asks for the user's name, email, and message.**
3. **Design a webpage with an ordered list of your favorite books and an unordered list of hobbies.**
4. **Create a table with 3 columns: Name, Age, and City, and add 3 rows of data.**
5. **Use semantic HTML5 elements to structure a webpage, including `<header>`, `<footer>`, `<article>`, and `<section>`.**

---

## License

This repository is open-source and available under the MIT License. You can freely use, modify, and distribute the code, but please attribute it to the author.

---

Happy coding! ✨

---

