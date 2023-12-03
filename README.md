# myntra-webpage-using-html-and-css

Certainly! Here's a description of each HTML tag and element in your code:

<!DOCTYPE html>: Declares the document type and version of HTML being used, in this case, HTML5.

<html lang="en">: The root element of the HTML document, specifying the language as English.

<head>: Contains meta-information about the HTML document, such as character set, viewport settings, and links to external resources like stylesheets.

<meta charset="UTF-8">: Specifies the character encoding as UTF-8.

<meta name="viewport" content="width=device-width, initial-scale=1.0">: Sets the viewport settings for better responsiveness on various devices.

<title>Myntra</title>: Sets the title of the HTML document, which is typically displayed in the browser tab.

<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200">: Links to an external stylesheet from Google Fonts for a particular font.

<link rel="stylesheet" href="styles.css">: Links to an external stylesheet named "styles.css."

<body>: Contains the content of the HTML document, including headers, paragraphs, images, etc.

<header>: Represents the header section of the document, often containing logos, navigation menus, and other header-related content.

<div class="logo_container">: A container for the logo image.

<img src="images\myntra_logo.svg" alt="">: Displays the Myntra logo with an empty alt attribute.

<nav class="nav_bar">: Defines a navigation menu.

<a href="#">men</a>, <a href="#">women</a>, <a href="#">kids</a>, <a href="#">beauty</a>, <a href="#">studio <sup>New</sup></a>: Navigation links for various categories.
<div class="search_bar">: Container for the search bar.

<span class="Material-Symbols-Outlined search_icon"></span>: Placeholder for a search icon.
<input>: Placeholder for the input field.
<nav class="action_container">: Container for action buttons (placeholder).

<main>: Represents the main content of the document.

<footer>: Represents the footer section of the document.


#CSS
*: Targets all elements on the page.
margin: 0;: Removes default margins.
padding: 0;: Removes default paddings.
box-sizing: border-box;: Applies the border-box box-sizing model to all elements.
font-family: Assistant, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica, Arial, sans-serif;: Specifies the font stack for text.

header: Styles for the header element.
display: flex;: Uses flexbox for layout.
height: 80px;: Sets the height of the header.
align-items: center;: Centers items vertically.
justify-content: space-between;: Distributes items with space between them.
padding: 0 2%;: Adds padding on the left and right sides of the header.

.logo_container: Styles for the logo container.
height: 40px;: Sets the height of the logo container.

.logo_container img: Styles for the logo image within the container.
height: 100%;: Sets the height of the logo image to 100% of its container.

.nav_bar: Styles for the navigation bar.
display: flex;: Uses flexbox for layout.
font-size: 14px;: Sets the font size.
font-weight: 700;: Sets the font weight to bold.
text-transform: uppercase;: Transforms text to uppercase.
justify-content: space-between;: Distributes items with space between them.
min-width: 500px;: Sets the minimum width of the navigation bar.

.nav_bar a: Styles for the navigation links.
text-decoration: none;: Removes underlines from links.
color: #282c3f;: Sets the text color.

.nav_bar a sup: Styles for the superscript within navigation links.
color: #ff3f6c;: Sets the text color.
font-size: 10px;: Sets the font size.

.search_bar: Styles for the search bar.
display: flex;: Uses flexbox for layout.
height: 40px;: Sets the height of the search bar.
min-width: 400px;: Sets the minimum width of the search bar.
background-color: #f5f5f6;: Sets the background color.
border-radius: 4px;: Sets border radius for rounded corners.

.search_icon: Styles for the search icon.
box-sizing: content-box;: Uses content-box box-sizing.
padding: 10px;: Adds padding.
color: #282c3f;: Sets the text color.

.search_text: Styles for the search text input.
flex-grow: 1;: Allows the input to grow within the flex container.
background-color: #f5f5f6;: Sets the background color.
border-radius: 4px;: Sets border radius for rounded corners.
border: 0;: Removes the border.

.action_bar: Styles for the action bar.
display: flex;: Uses flexbox for layout.
min-width: 200px;: Sets the minimum width of the action bar.
justify-content: space-evenly;: Distributes items with space evenly.

.action_container: Styles for the action container.
display: flex;: Uses flexbox for layout.
flex-direction: column;: Arranges items in a column.
align-items: center;: Centers items horizontally.
font-size: 12px;: Sets the font size.
font-weight: 700;: Sets the font weight to bold.