# README: Inline & Block Elements in HTML

This HTML document provides a demonstration of both inline and block elements, showcasing their styling using embedded CSS. Additionally, it includes a quick quiz for creating a vertically aligned form without using the `<br>` tag.

## Styling with CSS

### Block Elements:

- `<h1>`: Styled with a background color of `blueviolet`.

### Inline Elements:

- `<a>`: Styled with a background color of `springgreen`.
- `<div>`: Styled with a background color of `burlywood`.
- `<span>`: Styled with a background color of `gray`.

## HTML Elements

1. `<p>`: Represents a paragraph, styled with a background color of `aqua`. It is a block-level element.
2. `<h1>`: Represents a heading, styled with a background color of `blueviolet`. It is a block-level element.
3. `<a>`: Represents a hyperlink, styled with a background color of `springgreen`. It is an inline element.
4. `<div>`: Represents a division or section, styled with a background color of `burlywood`. It is a block-level element containing inline elements.
5. `<span>`: Represents an inline container, styled with a background color of `gray`. It is an inline element.
6. `<form>`: Represents an HTML form for user input, containing:
    - `<input>` elements for collecting user data (Name, City, Pin Code).

## Quick Quiz

The document concludes with a quick quiz challenge:

Without using the `<br>` tag, a vertically aligned form is created asking for the user's Name, City, and Pin Code.

```html
<form action="">
    <p>
        Name: <input type="text" name="name">
    </p>
    <p>
        City: <input type="text" name="city">
    </p>
    <p>
        Pin Code: <input type="number" name="pin">
    </p>
</form>
```

This HTML code demonstrates how to structure a form vertically, enhancing user readability without relying on line breaks. Feel free to explore and modify the code for educational purposes.