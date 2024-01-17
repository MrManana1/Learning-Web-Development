# CSS Overflow Property

This HTML document showcases the use of the CSS Overflow property to control the behavior of content that overflows its container.

## HTML Structure

The HTML document contains a `<div>` element with the class "box." This div represents a container with specified width and height.

## CSS Styling

The styles applied to the document are as follows:

```css
.box {
    width: 20vw;
    height: 10vh;
    border: 2px solid black;

    /* Overflow auto adds a vertical scrollbar if content overflows. */
    overflow: auto;

    /* Uncomment one of the following styles to observe different overflow behaviors: */

    /* Overflow scroll adds both horizontal and vertical scrollbars. */
    /* overflow: scroll; */

    /* Overflow hidden hides the extra content that overflows the container. */
    /* overflow: hidden; */

    /* Overflow auto on the x-axis and scroll on the y-axis. */
    /* overflow: auto scroll; */

    /* Overflow scroll on the x-axis and auto on the y-axis. */
    /* overflow: scroll auto; */

    /* Overflow clip doesn't add scrollbars programmatically. */
    /* overflow: clip; */
}
```

### Explanation

- The "box" class represents a container with a specified width, height, and a border.

- The `overflow` property is used to control the overflow behavior of the container.

- Different values of `overflow` are commented out. Uncomment one at a time to observe the corresponding overflow behavior.

## Usage

Feel free to experiment with the values of the `overflow` property to see how it affects the display of content within the container. This can be useful for handling overflow in various design scenarios.

Happy coding!