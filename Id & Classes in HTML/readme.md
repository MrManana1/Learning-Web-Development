# README: Class and ID Example

This HTML and CSS code demonstrates the use of class and id attributes to apply styling to specific elements on a webpage.

## HTML and CSS Code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Class and ID Example</title>
    <style>
       .container {
        background-color: blueviolet;
       }
       #para {
        background-color: brown;
       }
    </style>
</head>
<body>
    <div class="container">
        This is an example of a class.
    </div>
    <p id="para">This is a paragraph with the id "para."</p>
</body>
</html>
```

## Description:

### Class (`container`):

- The class "container" is applied to the `<div>` element, setting its background color to blueviolet. Classes are used to group multiple elements and apply a common style.

### ID (`para`):

- The id "para" is applied to the `<p>` element, setting its background color to brown. IDs are used to uniquely identify a specific element on the page and apply a unique style.

## How to Use:

1. Open the HTML file in a web browser.
2. Observe the styled container with the class and the styled paragraph with the id "para."

## Difference between Class and ID in HTML:

- **Class:**
  - Used to group and style multiple elements that share a common style.
  - Can be applied to multiple elements on the same page.
  - Applied using the `class` attribute (`class="container"`).

- **ID:**
  - Used to uniquely identify and style a specific element on the page.
  - Should be unique within the HTML document.
  - Applied using the `id` attribute (`id="para"`).

### Note:

- Both class and id attributes are essential tools in CSS for styling HTML elements. Understanding the difference between them helps in organizing and applying styles to elements efficiently.