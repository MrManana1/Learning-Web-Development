# Document Styling
## Questions

1. Explain the CSS styles applied to the `div :first-child` selector and the `p` selector.
2. Describe how the background color and text color are set for the first child of each `div` with class `class1`, `class3`, `class2`, `class4`, and `class5`.
3. How is the hover effect implemented for the `h2` element? Explain the changes that occur on hover.
4. Identify the CSS property used to capitalize the text in the `h2` element. Provide an example of its application.
5. Explain the purpose of the `text-indent` property applied to the `h2` element.
6. Describe the CSS properties applied to the `p` element within the `.para` class. How do these properties affect the styling of the `p` element?
7. If you were to add an external CSS file to this HTML document, how would you link it? Provide an example.

This repository contains HTML and CSS code for styling paragraphs with different classes. Each class has specific styles applied to enhance the visual presentation.

## Styles Overview

### 1. `div :first-child` Selector

The `div :first-child` selector is used to style the first child of each `div` element. It sets a yellow background color and red text color.

### 2. Background and Text Color for Paragraphs

- The `p` selector sets a blue background color and white text color for all paragraphs.

### 3. Hover Effect for `h2` Element

The `h2` element has a hover effect implemented using the `:hover` pseudo-class. On hover, the text is underlined, and the underline color changes to red.

### 4. Capitalizing Text in `h2` Element

Text in the `h2` element is capitalized using the `text-transform: capitalize;` property.

### 5. `text-indent` Property for `h2` Element

The `text-indent` property is applied to the `h2` element with a value of `100px`. This indents the text by 100 pixels.

### 6. Styling for `.para` Class

The `.para` class is applied to `p` elements, removing text decoration and setting a line height of 1.



## Usage

Clone the repository and open the HTML file in a web browser to view the styled paragraphs.

## External CSS File

To link an external CSS file, add the following line to the `<head>` section of the HTML document:

```html
<link rel="stylesheet" type="text/css" href="path/to/external/style.css">
