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


# CSS Notes

## Font Import

```css
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@900&display=swap');

- Imports the Montserrat font with a weight of 900 for the entire document.

## Global Styles
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
