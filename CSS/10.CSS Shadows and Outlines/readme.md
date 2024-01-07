# CSS Shadows and Outlines

This simple HTML document showcases the usage of CSS shadows and outlines. Let's understand the concepts and differences between shadows and outlines.

## CSS Shadows
In CSS, shadows are used to create visual depth and dimensionality for elements. In your code, the `.box` class has a box shadow applied using the `box-shadow` property. The parameters `2px 20px 10px -15px black` represent the horizontal offset, vertical offset, blur radius, and spread radius of the shadow, respectively. Adjust these values to achieve different shadow effects.

```css
.box {
    border: 2px solid black;
    margin: 10px;
    padding: 10px;
    box-shadow: 2px 20px 10px -15px black;
}
```

## CSS Outlines
Outlines are similar to borders but have some key differences. They don't impact the element's layout and don't change the size or position of the element. In your code, the `.box1` class has an outline applied with the `outline` property and an outline offset with `outline-offset`. This creates a visual border outside the element.

```css
.box1 {
    outline: 2px solid red;
    outline-offset: 20px;
}
```

## HTML Structure
- The HTML document contains three main elements: a `.box` div, a paragraph (`<p>`) with a text shadow, and a `.box1` div with an outline.
- The styles applied enhance the visual presentation of these elements.

Feel free to experiment with the values in the CSS to see how they affect the appearance of shadows and outlines.

**Note:** Ensure that you have a clear understanding of how shadows and outlines impact the visual design of your webpage. Adjust the values based on your design preferences and requirements.

Feel free to explore and modify the code to see how different values impact the visual presentation of shadows and outlines.

