# README: Inline, Internal & External CSS

## Overview

This HTML document provides an introduction to different ways of adding CSS (Cascading Style Sheets) to HTML: Inline, Internal, and External CSS. It also includes a code example demonstrating the application of each method.

## Inline, Internal & External CSS - Differences

| Feature                | Inline CSS                               | Internal (Embedded) CSS                 | External CSS                          |
|------------------------|------------------------------------------|------------------------------------------|---------------------------------------|
| **Location**           | Applied directly to a single element.    | Applied within the `<style>` tag in the `<head>` section of the HTML document. | Stored in a separate CSS file (e.g., style.css) and linked to the HTML document using `<link>` tag. |
| **Usage**              | Ideal for small, one-off styling changes. | Suitable for styling a specific HTML document. | Recommended for consistent styling across multiple pages or a website. |
| **Flexibility**        | Limited flexibility and scalability.      | Offers better scalability than inline CSS but may still lead to code duplication. | Highly scalable and promotes code reusability. Changes made in one file reflect across multiple pages. |
| **Readability**        | Decreases readability within HTML tags.  | Separates HTML structure from styling, enhancing readability. | Enhances code organization and readability, making it easier to manage styles. |
| **Maintenance**        | Hard to maintain and update.              | Moderately easy to maintain. Changes can be made in one place. | Easier to maintain. Centralized styles in an external file. |
| **Example Code**       | `<div style="color: blue;">Content</div>` | `<style>p { color: blue; }</style>` | `<link rel="stylesheet" type="text/css" href="style.css">` |
| **When to Use**        | For quick, specific styling adjustments. | For small to medium-sized projects or when styling is specific to one document. | For larger projects, maintaining consistency, and reusability of styles across multiple pages. |
| **When to Avoid**      | In large projects where maintainability is crucial. | In larger projects, as it may lead to code duplication. | In smaller projects with minimal styling requirements. |

## Example Code Explanation

### Inline CSS:

```html
<div style="color: blue; font-size: 24px;">This is a paragraph with inline CSS.</div>
```

### Internal (Embedded) CSS:

```html
<style>
    h1 {
        color: blue;
    }
</style>
```

### External CSS:

```html
<link rel="stylesheet" type="text/css" href="style.css">
```

## How to Use

1. Open the HTML file in a web browser.
2. Observe the different styling methods applied to various elements on the page.

## Note

- The code includes examples of inline, internal, and external CSS to demonstrate their usage and differences.
- Customize the content and styles based on your needs.
- The provided CSS files (`style.css`) are for reference and can be modified as required.