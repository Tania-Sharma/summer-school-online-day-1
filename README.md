# Summer school online day 1

This repository contains a personal portfolio website built using **pure HTML** as part of my **Web Development Internship** project.

It includes three main pages:
- `portfolio.html` – Homepage with skills, education, image, and experience
- `about.html` – A brief introduction about me with internal and external links
- `contact.html` – A contact form with multiple input types and validation

---

## 📌 What Each HTML Element Does

- `<!DOCTYPE html>`: Declares the document as HTML5.
- `<html>`: Root element of the entire page.
- `<head>`: Contains meta info like title, character encoding, and favicon.
- `<title>`: Sets the page name seen on browser tab.
- `<link rel="icon">`: Adds a custom favicon.
- `<meta charset="utf-8">`: Supports Unicode characters.
- `<body>`: Main visible content of the page.
- `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`: Semantic elements that help in structuring the webpage meaningfully.
- `<h1>` to `<h6>`: Headings for creating content hierarchy.
- `<a href="">`: Creates hyperlinks to other pages or external sites.
- `<ul>`, `<ol>`, `<li>`: Unordered and ordered lists to display skills and education.
- `<img>`: Displays images with `alt` text for accessibility.
- `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`: Used to show experience in a tabular format.
- `<form>`: Wraps all user input elements for contact.
- `<input>`: Various fields like text, email, tel, date, radio, checkbox, and range.
- `<label>`: Associates text with input fields, improves accessibility.
- `<select>`, `<option>`: Dropdown for choosing subject.
- `<textarea>`: Multiline input box for messages.
- `<button>`: Submit button for the form.

---

## 🧾 Why I Chose Specific Input Types

- `type="text"`: For free-text inputs like Name.
- `type="email"`: Ensures correct email format.
- `type="tel"` with `pattern="[0-9]{10}"`: Validates 10-digit phone numbers.
- `type="date"`: Lets users pick date of birth easily.
- `select` dropdown: Limits subject input to predefined choices.
- `radio`: Used for mutually exclusive inquiry types (only one can be selected).
- `checkbox`: Allows multiple contact methods to be selected.
- `textarea`: For longer messages or queries.
- `range`: Added for urgency level – gives interactive experience.
- `required`: Ensures important fields must be filled before submitting.
- `pattern`: Used to enforce format in fields like phone number.

These input types improve **form usability**, **data accuracy**, and **user experience**.

---

## 🔗 How My Navigation Structure Works

- I used a `<nav>` element inside `<header>` on each page.
- It includes three consistent links:
  - `Home` → portfolio.html  
  - `About` → about.html  
  - `Contact` → contact.html  
- This allows the user to navigate between pages easily.
- External links (like LinkedIn) are placed in the about page using `<a>` with `target="_blank"` so they open in a new tab without leaving the website.
- The structure is semantic and easy to maintain or scale in future.

---



> Built with ❤️ using only HTML (No CSS or JS yet — styling will come later!)

---


