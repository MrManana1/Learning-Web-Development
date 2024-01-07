
# List Styling

This HTML document demonstrates a simple navigation menu with styled list items. The provided styles enhance the visual presentation of the list.

## HTML Structure

The HTML document consists of a navigation menu (`<nav>`) containing an unordered list (`<ul>`) with list items (`<li>`). The list items represent typical navigation links such as Home, About, and Contact Us.

## CSS Styling

The styles applied to the document are as follows:

```css
* {
    padding: 0;
    margin: 0;
}

nav ul {
    display: flex;
}

nav ul li {
    list-style: none;
    list-style-position: inside;
    margin: 10px;
}
```

### Explanation

- The universal selector `*` is used to remove default padding and margin from all elements.

- The navigation menu is styled with a flex display to arrange list items horizontally.

- List items (`nav ul li`) are styled to remove default list styles, set the list style position inside the box, and provide margin for spacing.

## Usage

Feel free to use or modify this code for your projects. Customize the list items, add links, or adjust styling according to your design preferences.

Explore different CSS properties to further enhance the appearance of your navigation menu.

Happy coding!