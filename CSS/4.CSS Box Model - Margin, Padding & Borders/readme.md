# CSS Box Model - Margin, Padding & Borders

This repository contains a simple HTML and CSS example demonstrating the CSS Box Model, focusing on the concepts of margin, padding, and borders.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Box Model Explanation](#box-model-explanation)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The HTML file (`index.html`) in this repository serves as a practical example to understand the CSS Box Model and its properties, such as margin, padding, and borders. The styling is applied to two boxes (`box1` and `box2`) to demonstrate how these properties affect the layout and appearance of elements.

## Getting Started

To view the example, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/css-box-model.git
   ```

2. Open the `index.html` file in a web browser.

## Box Model Explanation

The CSS in this example defines two classes: `box1` and `box2`. The properties include:

- **margin:** Sets the margin for all sides to 5 pixels.
- **padding:** Adds internal padding of 20 pixels to the content of the box.
- **border:** Creates a red, solid border with a width of 2 pixels.
- **height:** Sets the height of the box to 200 pixels.
- **width:** Sets the width of the box to 400 pixels.
- **box-sizing:** Ensures that padding and border are included in the specified width and height.

## Folder Structure

- `index.html`: The main HTML file containing the example.
- `style.css`: CSS file with styling for the example.

## Contributing

If you find issues or have improvements, feel free to open an [issue](https://github.com/your-username/css-box-model/issues) or submit a [pull request](https://github.com/your-username/css-box-model/pulls).

## License

This project is licensed under the [MIT License](LICENSE).

---

# Margin Collapse

In CSS, **margin collapse** refers to the behavior where the vertical margins of adjacent block-level elements are collapsed into a single margin. This collapsing behavior is important to understand when dealing with the layout of HTML elements.

## How Margin Collapse Works

- **Adjacent Siblings:** Margin collapse occurs between adjacent block-level elements that are siblings (i.e., they share the same parent).

- **Largest Margin Wins:** The final margin between two elements is the larger of the two margins. If one margin is larger than the other, it "wins" and becomes the shared margin.

- **Empty Blocks:** If an element has no content or height, its top and bottom margins can still collapse with adjacent margins.

- **Parent-Child Relationship:** Margin collapse does not occur between a parent and its child, or between an element and its floated children.

## Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Margin Collapse Example</title>
</head>
<style>
    .box {
        margin: 20px 0;
        padding: 10px;
        border: 1px solid #ccc;
    }
</style>
<body>
    <div class="box">
        <p>This is a paragraph inside a box.</p>
    </div>
    <div class="box">
        <p>Another paragraph in a different box.</p>
    </div>
</body>
</html>
```

In this example, the vertical margin between the two `.box` elements will collapse, and the larger margin will be applied.

Understanding margin collapse is crucial for creating consistent and predictable layouts in CSS.

For more detailed information on margin collapse, refer to the [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Mastering_margin_collapsing).