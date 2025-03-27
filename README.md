# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

**ANSWERS**

/* Styling using IDs */
#header {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 20px;
    font-family: Arial, sans-serif;
    font-size: 24px;
    border-bottom: 5px solid darkgreen;
}

/* Styling using Classes */
.container {
    margin: 20px;
    padding: 20px;
    border: 2px solid #ddd;
    border-radius: 10px;
    background-color: #f9f9f9;
}

.text-highlight {
    color: #ff5722;
    font-weight: bold;
}

/* Typography styling */
p {
    font-family: 'Georgia', serif;
    font-size: 16px;
    line-height: 1.6;
    color: #333;
}

/* Margins, paddings, and borders */
h2 {
    margin-top: 20px;
    margin-bottom: 10px;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    background-color: #e0e0e0;
    text-align: left;
}

/* Styling links */
a {
    color: #3498db;
    text-decoration: none;
}

a:hover {
    color: #1d70b8;
    text-decoration: underline;
}

**HTML**
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <!-- Linking the external CSS file -->
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header styled with an ID -->
    <div id="header">
        Welcome to My Styled Page
    </div>

    <!-- Container with a class -->
    <div class="container">
        <h2>Section Title</h2>
        <p>This is a sample paragraph with <span class="text-highlight">highlighted text</span>.</p>
        <p>Here is a link to <a href="https://example.com">Example Website</a>.</p>
    </div>
</body>
</html>
Happy Coding! 💻✨
