# README: CSS Basics - Selectors and Declarations

## Overview

This simple HTML document demonstrates the use of CSS (Cascading Style Sheets) to apply styling to HTML elements. The focus is on understanding selectors and declarations to style different elements on the page.

## HTML Structure

The HTML structure consists of several `<div>`, `<span>`, and `<p>` elements, each serving as a container for content.

## CSS Styles

### 1. Styling `<div>` Elements:

```css
div {
    color: white;
    background-color: black;
}
```

- This selector (`div`) targets all `<div>` elements on the page.
- The declarations within the curly braces define styles for text color and background color.

### 2. Selecting Multiple Elements at Once:

```css
span, p {
    background-color: yellow;
}
```

- This rule selects both `<span>` and `<p>` elements at once.
- The shared declaration sets the background color to yellow for both elements.

## Example Content

1. **First `<div>`:**

```html
<div>
    I am Abdul-Manan. Today I have started CSS.
</div>
```

2. **Second `<div>` with Nested `<div>`:**

```html
<div>
    This is another div
    <div>This is another div inside the div</div>
</div>
```

3. **`<span>` Element:**

```html
<span>This is a span</span>
```

4. **`<p>` Element:**


```html
<p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis odit sunt neque eius dolorem consequuntur, eos aliquid voluptatibus, dolorum placeat eum. Pariatur saepe totam sequi optio fuga aliquid asperiores, esse iste cumque, dolores voluptates.
</p>
```

## How to Use

1. Open the HTML file in a web browser.
2. Observe the styling applied to different elements as per the CSS rules.

## Note

- This example provides a basic understanding of CSS selectors and declarations.
- Customize the content and experiment with additional styles to further explore the capabilities of CSS.