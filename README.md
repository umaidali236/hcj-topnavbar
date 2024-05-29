# Creating a Top-Navbar

## HTML 
- `<!DOCTYPE html>`: Declaration of the document type and version of HTML being used.
- `<html lang="en">`: The root element of the HTML document, specifying the language as English.

## Head Section:
- `<head>`: Contains meta-information about the HTML document.
  - Meta tags for character set and viewport settings.
  - Link to the favicon (shortcut icon).
  - Link to the Font Awesome library for icons.
  - Link to an external stylesheet (`styles.css`).
  - Title of the webpage, "Umaid's Coffee Shop".

## Body Section:
- `<body>`: Contains the content of the webpage visible to users.
  - `<div class="nav-header">` which contains a logo and an icon.
  - `<nav>`: Navigation section containing links to different pages.
  - `<div class="welcome-msg">`: Displays a welcome message at the top of the page.
  - `<div class="banner-div">`: Div container for the banner image.
   - An `<img>` tag with an ID `banner1` is used to display the banner image.
  - `<script src="script.js"></script>`: Reference to an external JavaScript file (`script.js`).
    
## Navigation:
- Navigation links for "Home", "Menu", "About Us", and "Contact".

## Content:
- Welcome message: "Welcome to our Coffee Shop".
- Banner image with a credit link to Freepik.
- Footer containing a copyright notice.

## Improvements/Issues:
- Ensure proper indentation and organization of the HTML elements for readability.
- Check if all necessary files (`styles.css`, `script.js`, `favicon.ico`, `Banner.PNG`) are present and linked correctly.
- Validate HTML code for any syntax errors.

# CSS

## Font Import

```css
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@900&display=swap');
```
- Imports the Montserrat font with a weight of 900 for the entire document.

## Global Styles

```css
* {
    box-sizing: border-box;
}

body {
    font-family: 'Montserrat', sans-serif;
    margin: 0;
    padding: 0;
    height: 100vh;
    line-height: 2.2;
    font-size: 0.875rem;
}
```
- Applies border-box sizing to all elements.
- Sets font family, margin, padding, height, line height, and font size for the body.

## Heading Styles

```css
h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
    color: #634b01;
}
```
- Sets styles for `<h1>` elements: font size, margin bottom, and color.

## Image Styles

```css
img {
    height: 48px;
    width: 150px;
}
```
- Sets the height and width for all `<img>` elements.

## Icon Styles

```css
i {
    font-size: 3rem;
    color: #1e8cfa;
}
```
- Sets styles for `<i>` elements: font size and color.

## Navigation Styles

```css
nav {
    background: hwb(36 93% 5%);
    box-shadow: 0px 2px 0px #474746, 0px 4px 0px lightgray;
    width: 100%;
}
```
- Styles the navigation bar with background color and box-shadow.

## Menu Styles

```css
.menu {
    height: auto;
    display: flex;
}

.menu a {
    color: #ebf0f5;
    font-weight: lighter;
    font-size: 1rem;
    letter-spacing: 0rem;
    display: block;
    padding: 0;
    margin: 0 1rem;
    transition: all 0.3s linear;
}

.menu a:hover {
    background: #074173;
    color: #9ed1f5;
}
```
- Styles the menu links with colors and hover effects.

## Welcome Message Styles

```css
.welcome-msg {
    display: flex;
    justify-content: center;
}

.welcome-msg h1 {
    font: 2rem sans-serif;
    font-weight: bold;
    color: #896908;
}
```
- Styles the welcome message with centered alignment and specific font styles.

## Banner Styles

```css
.banner-div {
    margin-top: .7rem;
    position: relative;
    text-align: center;
    color: #c89a0e;
}

#banner1 {
    height: 400px;
    width: 100%;
}
```
- Styles the banner with margin, positioning, text alignment, and specific color.

## Footer Styles

```css
.footer {
    background-color: #e7ca6a;
    height: 45px;
    margin-top: 9%;
}

.footer h6 {
    color: #89690a;
    font: 0.9em sans-serif;
    font-weight: bold;
    padding: 16px;
    padding-left: 2px;
}
```
- Styles the footer with background color and specific font styles.

# JavaScript

```js
console.log(`${Date()} :: This is a starter template for a simple web app.`);
```
This line of code is written in JavaScript and uses template literals to log a message to the console along with the current date and time.

Let's break it down:

- `console.log()`: This is a function provided by the JavaScript console object, which is a tool available in most web browsers for logging messages, errors, and other information.
```js
- `${Date()}`: This part uses a template literal, denoted by the backticks (` `), to embed the result of the `Date()` function within the string. `Date()` is a built-in JavaScript function that returns the current date and time as a string.
```
- `::`: This is simply a separator to make the message more readable. It's a common convention to use symbols like `::` or `||` as separators in log messages.

- `This is a starter template for a simple web app.`: This is a static string message that is included in the log.

So when this line of code is executed, it will print something like this to the console:

```
Thu May 30 2024 13:42:20 GMT+0300 (Eastern European Summer Time) :: This is a starter template for a simple web app.
```

The exact date and time will vary depending on when the code is executed.  
