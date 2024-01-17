# CSS Container Styles

This simple HTML document showcases the usage of CSS to style container elements. The primary focus is on creating containers with different widths, borders, and margins.

## HTML Structure

The HTML document contains two main container `<div>` elements:

1. **Container without Margin:**
   - Class: `container`
   - Properties:
     - `box-sizing: border-box;` ensures that padding and border are included in the element's total width and height.
     - `border: 2px solid black;` adds a black border with a thickness of 2 pixels.
     - `width: 100vw;` sets the width to 100% of the viewport width.

2. **Container with Margin:**
   - Class: `container1`
   - Properties:
     - `box-sizing: border-box;` for consistent box model sizing.
     - `border: 2px solid black;` creates a black border with a thickness of 2 pixels.
     - `width: 80vw;` sets the width to 80% of the viewport width.
     - `margin: 20px auto;` applies a 20-pixel margin on the top and bottom, auto margin on the left and right for centering.

## CSS Reset

The `*` selector with `margin: 0;` and `padding: 0;` serves as a CSS reset, ensuring that default margin and padding are removed from all elements.

Feel free to use and modify this code as a starting point for your own projects.

**Note:** Adjust the styles according to your design preferences and layout requirements.

Enjoy coding! 🚀