
# CSS Structure

In this file, we'll go over the basic CSS code for the web-page we are creating, look below and feel free to experiemnt with each design element when creating your own web page

First, we want to create the CSS Style Sheet. Enter this code within your HTML code:

<head>
    <link rel="stylesheet" href="styles.css">
</head>

Next, we get to the actual styling element. Under this style sheet, utilize the code below, but feel free to experiment with each design element/values when creating your own web page


# This sets the default font for the entire webpage)
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

# Style for the page title
h1 {
    color: #333;
    font-size: 2.5em;
    text-align: center;
    margin-top: 20px;
}

# Style for the section titles
h2 {
    color: #555;
    font-size: 2em;
    margin-top: 30px;
}

# Adding some padding and margin to paragraphs
p {
    padding: 10px 20px;
    margin: 20px 0;
    color: #666;
}

# Add a background color and padding to the tutorial content
.container {
    width: 80%;
    margin: 0 auto;
    background-color: #ffffff;
    padding: 20px;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
}

# Link styles for navigation
a {
    color: #0066cc;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

# Add a footer with a dark background and white text
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    width: 100%;
    bottom: 0;
}
