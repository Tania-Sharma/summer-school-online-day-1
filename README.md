# summer-school-online-day-1

1. What Each HTML Element Does:

<!DOCTYPE html>
- Declares that this file is an HTML5 document.

<html> ... </html>
- Root element that wraps the entire webpage content.

<head> ... </head>
- Contains meta-information like title, favicon, and character encoding.

<title>
- Sets the title of the web page shown in the browser tab.

<link rel="icon">
- Sets a custom icon (favicon) for the website.

<meta charset="utf-8">
- Ensures proper text rendering with UTF-8 character encoding.

<body> ... </body>
- Contains all the visible content of the web page.

<header>, <main>, <section>, <footer>
- Semantic HTML5 tags that structure the page meaningfully.
- <header>: Top section (usually for title and nav).
- <main>: Core content of the page.
- <section>: Divides main content into logical parts.
- <footer>: Bottom of the page, usually for copyright/links.

<h1> to <h6>
- Headings with decreasing importance (h1 = highest).

<nav>
- Tag used to wrap navigation menus.

<a href="...">
- Creates hyperlinks to other pages or websites.

<ul>, <ol>, <li>
- Lists: unordered (bullets) or ordered (numbered).

<img src="..." alt="...">
- Displays images; alt is for accessibility if image doesn't load.

<table>, <thead>, <tbody>, <tr>, <th>, <td>
- Structure used to display data in tabular form.

<form> ... </form>
- Tag used to create an interactive form.

<input>
- Input fields (text, email, tel, etc.)

<select>, <option>
- Dropdown menu for selecting one option.

<textarea>
- Multiline text input field.

<button>
- Clickable button, typically used to submit the form.

<input type="range">
- Slider to choose a numeric value.

<input type="date">
- Date picker input field.

<input type="radio"> and <input type="checkbox">
- Used to select one or multiple options.

<label>
- Associates text with an input field for accessibility and clarity.


2. Why I Chose Specific Input Types:

- `type="text"` for name to allow any text entry.
- `type="email"` ensures a valid email format.
- `type="tel"` for phone numbers, with a 10-digit pattern.
- `type="date"` for date of birth (easily usable with calendar).
- `select` dropdown to give clean pre-defined options.
- `radio` for mutually exclusive inquiry types (user can pick only one).
- `checkbox` for preferred contact method (can pick multiple).
- `textarea` for message input since it's usually longer.
- `range` input to let user specify urgency level in a visual slider format.
- `required` ensures that important fields must be filled before submitting.
- `pattern` ensures correct phone number formatting.


3. How My Navigation Structure Works:

- Every page (`portfolio.html`, `about.html`, and `contact.html`) contains the same set of navigation links using the `<a>` tag:
   - Home → portfolio.html
   - About → about.html
   - Contact → contact.html

- This ensures the user can move between all pages from any page.
- All links are **relative**, meaning they work as long as files are in the same folder.
- The nav bar is placed inside a `<nav>` element (and wrapped in `<header>`), which improves both structure and accessibility.
- External links like LinkedIn open in a new tab using `target="_blank"` for better user experience.
