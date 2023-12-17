# README: Entities, Code Tag, and More in HTML

## HTML Entities:

HTML entities are special codes used to represent reserved characters and symbols in HTML. These characters, such as `<`, `>`, and `&`, have special meanings in HTML markup. Using entities ensures that these characters are displayed correctly on the web page.

## Code Tag:

The `<code>` tag in HTML is used to define a piece of computer code. It is typically used to display inline code snippets within a paragraph. It's a way to present code in a monospace font without interpreting the HTML markup inside.

## Canvas in HTML:

The `<canvas>` element in HTML is used to draw graphics, animations, or interactive content on a web page. It provides a drawing surface defined by width and height attributes. JavaScript is often used to manipulate and draw on the canvas.

## HTML Code Example:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Entities, Code Tag and more in HTML</title>
</head>
<body>
    <!-- Paragraph with HTML Entities -->
    <p>This is a paragraph. If we want to write a tag </p> 
    <p>We can't write it as it is reserved in HTML. To display the tag, we have to use <strong>HTML Entities</strong>.</p>

    <!-- Preformatted Text with Code Snippets -->
    <pre>
        <code>
            <p>This is a paragraph within a code block.</p>

            <p>This is another paragraph with extra spaces</p>
        </code>
    </pre>

    <!-- Copyright Symbol with HTML Entity -->
    <p>Copyright &copy; Manan</p>

    <!-- Paragraph with Extra Spaces Using Non-Breaking Spaces -->
    <p>If we want to add extra spaces within a paragraph, we have to use &nbsp;&nbsp; extra spaces are added.</p>
    
</body>
</html>
```

### HTML Structure:

- The code includes examples of using HTML entities, the `<code>` tag within a `<pre>` tag for code snippets, the `<canvas>` tag is not utilized in this example.
- HTML entities such as `&copy;` are used for special characters.

### How to Use:

1. Open the HTML file in a web browser.
2. Observe the examples of HTML entities, the code tag, and the preformatted text block.

### Note:

- Customize the content and styles based on your needs.
- Entities and the code tag are crucial for displaying reserved characters and code snippets accurately.
- The canvas tag is not demonstrated in this example but is essential for drawing graphics and interactive content using JavaScript.